# Project: Revanced APKs

Comprehensive ReVanced builder for Magisk modules and non-root APKs. Automates fetching, patching, and packaging Android apps with ReVanced patches.

## Tech Stack
- **Languages:** Bash (Main logic), C (KernelSU profile helper)
- **Tools:** `jq`, `java` (OpenJDK 17), `zip`, `curl`, `aapt2`, `apksigner`, `htmlq`, `tq`
- **Core Components:** ReVanced CLI, ReVanced Patches, ReVanced Integrations

## Architecture
- `build.sh`: Main entry point for desktop/CI builds.
- `utils.sh`: Core library for downloading (APKMirror, Uptodown, Archive.org), TOML parsing, and patching logic.
- `config.toml`: User configuration for apps, patches, and build modes.
- `bin/`: Platform-specific prebuilt binaries (`aapt2`, `htmlq`, `tq`) and jars.
- `module/`: Magisk/KernelSU module template.
- `ksu_profile/`: Source for `ksu_profile` native binary used in modules.

## Building and Running

### Build All Configured Apps
```bash
./build.sh
```

### Clean Build Artifacts
```bash
./build.sh clean
```

### Build on Termux
```bash
./build-termux.sh
```

### Update Config based on latest releases (CI only)
```bash
./build.sh --config-update
```

## Development Conventions
- **Shell Scripting:** Use `set -euo pipefail`. Avoid global variables where possible; use local and passed arguments.
- **Configuration:** All build-time customizations belong in `config.toml`. Use `CONFIG.md` as reference.
- **Prebuilts:** Binaries in `bin/` are architecture-specific (arm, arm64, x86_64). `utils.sh` handles selection via `set_prebuilts`.
- **Patching:** `build_rv` function in `utils.sh` manages the lifecycle of downloading stock APKs and applying patches via ReVanced CLI.
- **Testing:** No formal test suite. Verification is done via manual builds and CI workflows (`.github/workflows/ci.yml`).

## GitHub Workflows
- `build.yml`: Main build pipeline.
- `ci.yml`: Daily scheduled builds.
- `sync.yml`: Synchronizes with upstream repositories.

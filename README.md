# 🚀 ReVanced APKs

[![CI](https://github.com/znarfm/revanced-apks/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/znarfm/revanced-apks/actions/workflows/ci.yml)
[![GitHub tag](https://img.shields.io/github/tag/znarfm/revanced-apks?include_prereleases=&sort=semver&color=purple)](https://github.com/znarfm/revanced-apks/releases/)
[![License](https://img.shields.io/github/license/znarfm/revanced-apks?color=blue)](LICENSE)

An extensive ReVanced builder designed to automate the patching and packaging of Android apps. Create up-to-date **Magisk modules** (*im not building this*) and **non-root APKs** with ease.

## ✨ Key Features

- **🔄 Comprehensive Support:** Works with all current and future ReVanced/Extended apps.
- **🛠️ Flexible Builds:** Supports both Magisk/KernelSU modules and non-root APKs.
- **📅 Always Fresh:** Scheduled daily builds ensure you have the latest patches and app versions.
- **⚡ Performance Optimized:** Recompiles invalidated odex files for peak performance.
- **🛡️ Stealthy:** Does not trigger root detection or break SafetyNet/Play Integrity.
- **📱 Universal Compatibility:** Seamlessly supports Magisk, KernelSU, and non-root environments.

## 📦 Quick Start

### 1. Download Artifacts
The easiest way to get started is by downloading pre-built assets from the [Latest Releases](https://github.com/znarfm/revanced-apks/releases).

### 2. Automatic Updates with Obtainium
Add these apps to [Obtainium](https://obtainium.imranr.dev/) for seamless automatic updates:

| App | Badge | Quick Add |
| :--- | :---: | :--- |
| **YouTube** | ![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white) | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22app.morphe.android.youtube%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fznarfm%2Frevanced-apks%22%2C%22author%22%3A%22znarfm%22%2C%22name%22%3A%22YouTube%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22youtube-morphe-%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22YouTube%20Morphe%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22znarfm%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D) |
| **YT Music** | ![YT Music](https://img.shields.io/badge/YouTube_Music-FF0000?style=flat&logo=youtube-music&logoColor=white) | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22app.morphe.android.apps.youtube.music%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fznarfm%2Frevanced-apks%22%2C%22author%22%3A%22znarfm%22%2C%22name%22%3A%22YouTube%20Music%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22yt-music-morphe%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22YT%20Music%20Morphe%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22znarfm%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D) |
| **Reddit** | ![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=flat&logo=Reddit&logoColor=white) | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.reddit.frontpage%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fznarfm%2Frevanced-apks%22%2C%22author%22%3A%22znarfm%22%2C%22name%22%3A%22Reddit%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22reddit-morphe-%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22Reddit%20Morphe%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22znarfm%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D) |
| **Photos** | ![Google Photos](https://img.shields.io/badge/Photos-4285F4?style=flat&logo=google-photos&logoColor=white) | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22app.revanced.android.photos%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fznarfm%2Frevanced-apks%22%2C%22author%22%3A%22znarfm%22%2C%22name%22%3A%22Photos%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22gphotos-revanced%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22Google%20Photos%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22znarfm%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22github-creds%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3A%22GitHub%22%7D) |
| **Strava** | ![Strava](https://img.shields.io/badge/Strava-FC4C02?style=flat&logo=strava&logoColor=white) | [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.strava%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fznarfm%2Frevanced-apks%22%2C%22author%22%3A%22znarfm%22%2C%22name%22%3A%22Strava%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22strava-revanced-%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22Strava%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22znarfm%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D) |

## 🧪 Prerequisites

To use ReVanced Google apps (YouTube, YT Music,), MicroG services are required. Choose one:

- ⭐ **[MicroG-RE](https://github.com/MorpheApp/MicroG-RE)**: Material You design fork with various enhancements.
- **[ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases)**: The Official ReVanced GmsCore services.

## 🎛️ Customizing Your Build

Want to include/exclude specific patches or target other apps? Use this repo as your private builder.

1. **Template:** Use this repository as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc).
2. **Configure:** Edit `config.toml` to your liking. Use [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/) for a visual config generator.
3. **Trigger:** Manually run the build workflow in the **Actions** tab.

> [!NOTE]
> See [CONFIG.md](CONFIG.md) for detailed documentation on all available configuration options.

## 💻 Local Building

Build directly on your own hardware or mobile device.

### On Termux (Android)
```sh
bash <(curl -sSf https://raw.githubusercontent.com/znarfm/revanced-apks/main/build-termux.sh)
```

### On Desktop (Linux/macOS)
```bash
git clone https://github.com/znarfm/revanced-apks
cd revanced-apks
./build.sh
```

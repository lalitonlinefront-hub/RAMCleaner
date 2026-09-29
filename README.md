# RAM Cleaner - Vivo Y56 5G

Native Android app with a 2x1 home-screen widget.

## What was fixed
- Added Gradle version catalog.
- Added missing Compose theme/colors.
- Added missing DetailRow composable.
- Added strings, themes, backup/data-extraction resources.
- Added widget background/button/icon/preview resources.
- Added launcher icon resources.
- Added ProGuard file.
- Added GitHub Actions workflow that builds an APK without Android Studio.

## Build in GitHub (no Android Studio required)
1. Create a GitHub repository and upload this project.
2. Open Actions > Build RAM Cleaner APK > Run workflow.
3. After the workflow completes, download the artifact named `RAMCleaner-VivoY56-debug-apk`.
4. Inside it is `app-debug.apk`.

## Android behavior note
Modern Android does not allow a normal third-party app to force-stop arbitrary apps. This app reports real ActivityManager memory data, clears only its own cache, requests GC for its own process, and links to background-app settings for system-level management.

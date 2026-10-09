# Trader Business Control — Build Package

This package is based directly on the uploaded 08/10/2026 Admin + Client ZIP.

## Outputs
- Android Client APK
- Android Admin APK
- Windows Admin installer (.exe)

## Build
The included GitHub Actions workflow builds all three deliverables on GitHub's hosted runners. This is intentional because the supplied workspace does not contain the Android SDK/Gradle toolchain and cannot download it.

1. Create/open a GitHub repository and upload the contents of this package.
2. Open **Actions → Build Trader Business Control Apps → Run workflow**.
3. Wait for the workflow to finish, then open the workflow run and download the three artifacts.

The Android projects include INTERNET permission and launcher icons. The Admin desktop package wraps the supplied Admin `index.html` in Electron and creates a Windows NSIS installer.

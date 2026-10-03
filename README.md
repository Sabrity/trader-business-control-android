# Trader Business Control — Android Client

This project packages the current Sabrity Client dashboard directly into a native Android app shell. It does not depend on Chrome's PWA installation prompt and opens without a browser address bar.

The dashboard continues to read live business data from Supabase using the existing Client Feed configuration and automatic refresh.

## Build
The included GitHub Actions workflow builds a signed debug APK automatically on GitHub-hosted runners.

1. Put this project in a GitHub repository.
2. The workflow runs on push to `main` or can be started manually.
3. Download the artifact named `trader-business-control-client-android` from the completed workflow run.

The APK is installable directly on Android phones.

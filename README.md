# Promenthi

**The one app for useful and effective study.**

This repository contains the launch setup for the Promenthi Android starter project.

## Build the APK without Android Studio
1. Add the file `PromenthiAndroid_ZeroCostLaunch.zip` to the repository root. It should contain the `PromenthiAndroid/` project folder.
2. Open **Actions** and select **Build Promenthi Android APK**.
3. Click **Run workflow** (or push a commit to `main`).
4. When the workflow succeeds, open its run and download the `Promenthi-debug-APK` artifact.
5. Extract the artifact ZIP to get `app-debug.apk`.

## Free download page
The website source is in `docs/index.html`. Enable it at **Settings → Pages → Deploy from a branch → main → /docs**.

## Important
This is an early testing build, not a production-certified release. Test on real devices before public distribution. The current timer is not guaranteed to continue if Android kills the app process. Do not commit passwords, signing keys, API keys, or private data.

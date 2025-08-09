# Laptop Warranty Tracker (Android NDK)

**Developer:** K. Harsha Vardhan Chowdary

This repository contains an Android Studio project that wraps a C-based warranty tracker using the NDK + JNI.
Push this repository to GitHub (public), then run the included GitHub Actions workflow to build a debug APK.

## How to use (quick)
1. Create a **new public repo** on GitHub named `Laptop-Warranty-Tracker` (or any name).
2. Upload the contents of this folder (all files and folders) to your new repo.
3. On GitHub go to **Actions**, find workflow **Android NDK Build** and run it (or push to `main`).
4. After the workflow completes, download the artifact named `apk` containing `app-debug.apk`.
5. Install on your Android device (enable Install from unknown sources).

## Notes
- The app stores records in the app's internal storage as `warranty_data.txt`.
- Commands: Add warranty via UI fields, View All, Check Upcoming Expiries.
- The app will notify via local notification if any warranty is expiring within 30 days.

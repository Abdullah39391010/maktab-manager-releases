# Maktab Manager releases

Android APK files for the Maktab Manager app, and `latest.json`, which the app reads to show "نیا ورژن دستیاب ہے" (new version available).

To publish a new version:
1. Build the APK with a higher `versionCode` in `android/app/build.gradle`.
2. Add the file to `apk/` (for example `apk/maktab-manager-v1.5.apk`).
3. Update `latest.json`: `versionCode`, `versionName`, `sizeMB`, `apk` link, `sha256` and `notes`. Set `force` to `true` only when the old version must not be used any more.

Latest download: [maktab-manager-v1.9.apk](apk/maktab-manager-v1.9.apk)

# Attendance Tracker - Android app

WebView wrapper around app/src/main/assets/www/index.html with a native AdMob
adaptive banner at the bottom of the screen.

- AdMob App ID (AndroidManifest.xml): ca-app-pub-5777744656010390~1325257121
- Banner Ad Unit (release build):     ca-app-pub-5777744656010390/8614563512
- Debug builds automatically use Google's test banner unit.

## Build option A - Android Studio
1. Open this folder in Android Studio (Koala or newer) and let Gradle sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s), choose the release variant.
3. Output: app/build/outputs/apk/release/app-release.apk

## Build option B - GitHub Actions (no local setup)
1. Create a new GitHub repo and upload everything in this folder.
2. Open the Actions tab > "Build APK" > Run workflow.
3. Download the AttendanceTracker-APK artifact when it finishes.

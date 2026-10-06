# Neon Snake

A custom-drawn snake game for Android 10 (API 29) and above. Swipe to steer,
eat apples, avoid walls and yourself. High score is saved on the device.

## Build the APK

**Option 1 - Android Studio (easiest)**
1. Open this folder in Android Studio and let Gradle sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s).
3. The file is at `app/build/outputs/apk/debug/app-debug.apk`.

**Option 2 - command line** (needs JDK 17+ and the Android SDK, `ANDROID_HOME` set)

    ./gradlew assembleDebug

**Option 3 - no setup, in the cloud**
Push this folder to a GitHub repository. The included workflow builds the APK;
download `neon-snake-apk` from the Actions run's Artifacts section.

## Install
Copy `app-debug.apk` to the phone, open it, and allow "install unknown apps"
for your file manager or browser when prompted. The debug APK is already signed,
so it installs directly.

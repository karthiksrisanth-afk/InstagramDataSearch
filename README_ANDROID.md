# Instagram Data Search — Android Project

This is an Android Studio/Gradle project containing the app UI, logo and demo mode.

## Easiest way to create the APK

### On a computer with Android Studio
1. Extract this ZIP.
2. Open the extracted `InstagramDataSearch_Android` folder in Android Studio.
3. Let Gradle sync.
4. Select **Build > Build APK(s)**.
5. The APK will be in:
   `app/build/outputs/apk/debug/app-debug.apk`
6. Send that APK to your Android phone and tap it to install.

### Important
The Android wrapper bundles the frontend UI. The Instagram OAuth/backend from the web project still needs to be hosted on a server for real Instagram connection. The **View Sample** mode works locally in the APK.

For a production release, use a proper HTTPS backend and current Meta/Instagram API requirements.

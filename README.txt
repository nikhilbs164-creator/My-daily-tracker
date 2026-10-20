MY DAILY TRACKER — ANDROID PROJECT

This is an Android Studio project wrapping your light-theme tracker in a native Android WebView shell. It has an app label/icon, launches like an Android app, and keeps the tracker data in the app's WebView local storage on that device.

IMPORTANT: This ZIP is the Android project source, not a compiled APK. This environment does not have the Android SDK/Gradle build tools installed, so I cannot truthfully provide a ready-to-install APK from here.

HOW TO BUILD AN APK
1. Install Android Studio on a computer.
2. Extract this ZIP.
3. In Android Studio, choose Open and select the MyDailyTracker folder.
4. Let Gradle sync and install the requested Android SDK platform if prompted.
5. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When the build finishes, choose Locate. Android Studio will show app-debug.apk.
7. Transfer app-debug.apk to your Android phone and open it to install. You may need to allow installs from that source.

DATA NOTE
The tracker saves locally inside the app on that phone. Export a backup regularly. Uninstalling the app or clearing its data may erase local records.

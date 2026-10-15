# Kimpex Flow Periodic Maintenance Report — Android project

This Android Studio project packages the supplied HTML maintenance report in a WebView and supports selecting signature images from the device.

## Build APK
1. Install Android Studio on a Windows/Mac/Linux computer.
2. Extract this project ZIP.
3. In Android Studio choose **Open** and select the `KimpexFlowAndroid` folder.
4. Allow Gradle sync and install any requested Android SDK platform (API 35).
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Android Studio will show the generated APK location, normally `app/build/outputs/apk/debug/app-debug.apk`.

## Notes
- The report HTML is bundled in `app/src/main/assets/index.html`.
- The report's PDF export library and company logo currently load from internet URLs, so those features require internet until the assets are bundled locally.
- This source project is not itself a compiled APK. A working Android SDK/Gradle build environment is needed to produce and sign the APK.

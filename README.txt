RailPrep Android project

This Android Studio project wraps the RailPrep web app in a local WebView. It includes 500 GK questions extracted from your uploaded PDF and 171 separate nursing practice questions. The app runs offline because the data is bundled in app/src/main/assets.

Build APK
1. Install Android Studio on a computer.
2. Open this RailPrep-Android folder as a project.
3. Let Android Studio install/download the required Android SDK and Gradle plugin.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Debug APK output: app/build/outputs/apk/debug/app-debug.apk

This workspace does not have Android SDK/Gradle installed, so a compiled APK could not be produced here. The complete ready-to-build Android Studio project is provided.

Optional cloud build without Android Studio on your own computer
1. Upload this project to a GitHub repository (the project root is RailPrep-Android).
2. Open the repository's Actions tab and run "Build RailPrep APK" (or push to main/master).
3. Download the RailPrep-debug-apk artifact from the completed workflow run.
This workflow compiles a debug APK; a release APK should be signed securely before public distribution.

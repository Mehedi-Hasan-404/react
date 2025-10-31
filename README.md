# React Native ExoPlayer App (Source)

This repo contains the React Native source files for a simple ExoPlayer-backed Android app.

IMPORTANT: This archive contains the JS source, package.json, and GitHub Actions workflow.
To create a complete Android project that can be built, run the following locally and then replace files:

1. Create a fresh React Native CLI project:
   ```
   npx react-native init reactNativeExoApp
   ```
2. Copy the files from this archive into the generated project, replacing existing files.
3. Install dependencies:
   ```
   cd reactNativeExoApp
   npm install
   ```
4. Run locally:
   ```
   npx react-native run-android
   ```

Alternatively, if you want me to generate the full android/ Gradle files in this repo, ask and I'll add them (they are large).

Files included:
- index.js
- App.js
- package.json
- .github/workflows/android-build.yml


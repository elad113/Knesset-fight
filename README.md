# Knesset Fight — Android APK

Android WebView wrapper for https://knesset.app/.

## Build APK

Every push to `main` builds a debug APK using GitHub Actions. Open **Actions → Build Android APK**, then download the `KnessetFight-debug-apk` artifact. Pushes to `main` also trigger the workflow.

## Project
- Java Android app with WebView
- Hebrew/RTL-friendly layout
- JavaScript and DOM storage enabled for the website
- Back button navigates web history before closing
- HTTPS links stay in the app; external schemes are handed to Android

This app displays the website; its online features still depend on the website and internet connection.
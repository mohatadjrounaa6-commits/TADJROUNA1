# TADJROUNA.1

Android WebView wrapper for the supplied Arabic prayer-clock HTML app. It supports Android phones and Android TV, keeps the display awake, enables JavaScript/local storage, and requests location permission only when the app asks for it.

## Build

Open this project with Android Studio, or push it to GitHub and run **Actions → Build TADJROUNA.1 APK**. The workflow creates a debug APK artifact. To publish a Downloader-compatible release link, create and push a tag such as `v1.0` after the workflow is configured. The APK will then be attached to the GitHub Release as `TADJROUNA.1.apk`.

The prayer clock's calculations and settings are local. Internet is still needed for online fonts and remote audio streams; offline playback of remote audio is not guaranteed.

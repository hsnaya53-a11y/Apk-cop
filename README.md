# PineMacro v1.2 — Android APK build

This repository contains the PineMacro v1.2 Android project and a GitHub Actions workflow that builds a debug APK.

## Build
1. Open the **Actions** tab.
2. Select **Build PineMacro APK**.
3. Press **Run workflow**.
4. Open the completed run and download the `PineMacro-v1.2-debug-apk` artifact.

The artifact is a ZIP containing `app-debug.apk`. Extract it on Android to install.

## Important
This is an unsigned-for-release debug build (debug-key signed by Gradle). It has not been tested on a physical device. Android may show an install warning for apps installed outside Play Store.

Review the source and requested Accessibility permissions before enabling the service. Use only in accordance with Roblox/Bee Swarm Simulator rules.

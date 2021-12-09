# Cordova Abdias Build plugin

## What is this plugin?

Due to the need to include In App Purchase from Google to upload to the Play Store, and make sure not to alter Apple's modifications, I created this plugin.

What it does:
  - adds the library in the `build.gradle` on the native app only on Android
  - adds the permission in `AndroidManifest.xml` ( not needed anymore, but just in case )
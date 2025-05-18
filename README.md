# Snake Game Android App

This is a mobile snake game that can be built as an Android APK using Apache Cordova.

## Prerequisites

1. Install Node.js from https://nodejs.org/
2. Install Android Studio from https://developer.android.com/studio
3. Install Java Development Kit (JDK)

## Setup Instructions

1. Install Cordova globally:
```bash
npm install -g cordova
```

2. Create a new Cordova project:
```bash
cordova create snake-game
cd snake-game
```

3. Add Android platform:
```bash
cordova platform add android
```

4. Copy the following files to the `www` folder:
   - index.html
   - game.js
   - config.xml

5. Build the Android app:
```bash
cordova build android
```

The APK file will be generated in the `platforms/android/app/build/outputs/apk/debug/` directory.

## Installing the APK

1. Enable "Install from Unknown Sources" in your Android device settings
2. Transfer the APK to your Android device
3. Open the APK file on your device to install it

## Development

To test the app on a connected Android device:
```bash
cordova run android
```

To test on an Android emulator:
1. Open Android Studio
2. Create and start an Android Virtual Device (AVD)
3. Run `cordova run android` 
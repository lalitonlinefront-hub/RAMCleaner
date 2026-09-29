# RAM Cleaner for Vivo Y56 5G

## How to Build the APK
1. Open Android Studio -> Open project -> `android/` folder
2. Run `./gradlew assembleDebug` in the terminal
3. Output APK: `app/build/outputs/apk/debug/app-debug.apk`

## How to Install on Vivo Y56 5G
1. Go to Settings > About phone > Software information > Tap "Build number" 7 times
2. Go to Settings > System > Developer options > Enable "USB debugging" AND "Install via USB"
3. Connect phone to PC and run:
   adb install -r app/build/outputs/apk/debug/app-debug.apk

## How to Add the 2x1 Widget
1. Pinch or long-press on Vivo Home Screen
2. Select Widgets -> RAM Cleaner -> Drag "RAM Monitor (2x1)" to home screen
3. Done!
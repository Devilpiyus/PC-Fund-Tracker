# PC Fund Tracker (Android)

A native Android savings tracker with a dark gaming-inspired interface.

## Included
- Fixed computer savings target: ₹80,000
- Live total, remaining amount, and progress percentage
- Add contributions with optional notes
- Dated savings history
- Delete an entry if it was added by mistake
- Data saved locally on the device using SharedPreferences

## Build the APK
1. Install Android Studio (current stable version).
2. Extract this ZIP.
3. In Android Studio choose **Open** and select the `PC_Fund_Tracker` folder.
4. Allow Gradle sync to finish. Android Studio may download the Android Gradle plugin and dependencies.
5. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Select **locate** in the build notification. The APK will be under `app/build/outputs/apk/debug/`.
7. Transfer the APK to your Android phone and install it. You may need to allow installation from that source.

## Notes
- The app does not connect to a bank or move money. It only records amounts you manually enter.
- Savings data stays on this device. Clearing app data or uninstalling the app can erase it, so keep your own backup if needed.
- The target is currently set to ₹80,000 in `MainActivity.kt` (`TARGET`).

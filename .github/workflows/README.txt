DUMPTRUCK ROUND TRIP MONITOR — ANDROID PROJECT

This project wraps your supplied offline HTML tracker in an Android WebView app.

Included:
- Truck fleet tap logging, date/shift/station fields
- Offline local device storage (WebView DOM storage)
- Undo, edit fleet, add truck(s), missed pass entry
- Trip counts, hourly chart, search and log deletion
- Word (.docx) and CSV export saved into the Android Downloads folder

BUILD AN APK:
1. Install Android Studio on a computer.
2. Extract this ZIP.
3. In Android Studio choose File > Open and select the DumptruckMonitor folder.
4. Allow Gradle sync and install Android SDK Platform 35 if prompted.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. The APK is created under app/build/outputs/apk/debug/app-debug.apk.
7. Copy that APK to your Android phone and install it. You may need to allow
   installation from your file manager/browser.

Package/application ID: com.curam.truckmonitor
Minimum Android: 6.0 (API 23)

NOTE:
- This ZIP is the Android Studio source project, not a precompiled APK.
- Your records are stored locally on the device. Clearing app data or uninstalling
  the app may erase locally stored records; export backups regularly.

Status Saver Pro - Android Studio project (Java) - FULL

What's included:
- Dynamic BottomNavigation (shows WhatsApp / WhatsApp Business only if installed)
- Statuses fragment lists files from WhatsApp .Statuses folder (images & videos)
- Save button copies file to /StatusSaver on external storage and adds to gallery
- Share button uses Android share chooser
- Saved tab lists saved files
- Settings: Open WhatsApp Web + Direct Chat (enter number, opens wa.me link)
- Runtime permission handling for READ_EXTERNAL_STORAGE (simple approach)

How to use:
1. Download ZIP and extract.
2. Open Android Studio -> Open 'StatusSaverPro' (root with settings.gradle).
3. Let Gradle sync. If Android Studio prompts to update Gradle plugin, accept or ask me for a matching ZIP.
4. Connect a real Android device (recommended) and Run the app. Grant storage permission when asked.
5. To test: put some files in /WhatsApp/Media/.Statuses on device storage (or WhatsApp Business path).
   Or use emulator with external storage containing those folders.

Notes:
- This project uses simple external storage reads (Environment.getExternalStorageDirectory()) for compatibility and clarity.
  For Play Store and Android 11+ robust behavior, consider adding MediaStore or SAF support; I can add that if you want.
- AdMob, analytics, advanced features not included by default; can be added later.

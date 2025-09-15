# Book Notifier Android (Project skeleton)

This is a lightweight Android Studio project skeleton for a Book Notifier app that:
- Checks Google Books API periodically (WorkManager, 15-minute minimum).
- Sends local notifications when new books are detected.
- Logs findings to a CSV in app storage.

## How to build
1. Open this folder in **Android Studio** (File → Open).
2. Let Gradle sync and download dependencies.
3. Build the APK: Build → Build Bundle(s) / APK(s) → Build APK(s).
4. Install the resulting APK on your device.

## Notes
- Minimum WorkManager periodic interval is 15 minutes.
- For dynamic query editing, you'll need to add UI and persistence (currently uses a hardcoded list).
- If you want a prebuilt APK and cannot build locally, I can guide you through using a CI service or provide build commands.

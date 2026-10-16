# Walker Desktop — installable Android source project

This is a native Android launcher source project. It is not an APK; the APK must be built using Android Studio or a compatible Android build environment.

## Build a debug APK
1. Install Android Studio and Android SDK Platform 35.
2. Open this folder in Android Studio.
3. Wait for Gradle sync to finish.
4. Choose Build → Build Bundle(s) / APK(s) → Build APK(s).
5. The APK is normally produced at `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer the APK to the Android phone, open it, and allow installation from that source if Android asks.

## Features in this source
- Desktop-inspired home screen and taskbar
- Start panel and web search
- Installed app list and launching
- Browser using Android WebView
- Android document picker
- Android settings and calculator shortcuts
- HOME intent filter so the app can be selected as the default launcher

## Important limits
- Android is still the operating system. This launcher does not install Windows or natively run Windows `.exe` applications.
- The document picker opens real files selected by the user; it is not a full desktop file manager.
- Floating desktop windows for arbitrary Android apps, external monitor UI, remote Windows PC access, and full office suite are not included.
- External display output depends on the specific phone's hardware and software. USB-C alone does not guarantee video output.
- This project has not been compiled or tested in this environment. Build and test on the target device before relying on it.

# PocketPlay — Android Media Player (VLC-Style)

PocketPlay is a lightweight, modern Android media player app built with **Kotlin**, **Jetpack Compose**, and **AndroidX Media3 (ExoPlayer)**.

## Features
- **Local Video Library**: Automatically finds videos stored on your smartphone.
- **Local Audio Library**: Lists MP3, AAC, FLAC, and other audio files on your device.
- **Network Stream**: Paste any video/audio stream URL (HTTP, HTTPS, HLS `.m3u8`, DASH `.mpd`, RTSP) and play it immediately.
- **VLC-Style Player Controls**:
  - Play / Pause, 10-second Rewind / Fast-Forward, and Seek bar
  - Playback Speed selector (`0.5x`, `1.0x`, `1.25x`, `1.5x`, `2.0x`)
  - Aspect Ratio / Resize toggle (Fit, Fill, Zoom)
  - Screen Lock button (prevents accidental taps while watching)
  - Fullscreen immersive mode

## How to Build & Install on Your Smartphone
1. **Install Android Studio** on your computer (Windows, Mac, or Linux) from [developer.android.com/studio](https://developer.android.com/studio).
2. **Unzip** this `PocketPlay-Android-App.zip` file.
3. Open **Android Studio** -> click **Open** -> select the unzipped `PocketPlayAndroid` folder.
4. Wait a few minutes for Android Studio to download dependencies (Gradle Sync).
5. **Connect your Android phone** via USB cable (enable *USB Debugging* in your phone's Developer Options), or use **Build -> Build Bundle(s) / APK(s) -> Build APK(s)** to create an `.apk` file you can copy and install on your phone.
6. Press the green **Run (▶)** button in Android Studio to install and launch PocketPlay on your phone.

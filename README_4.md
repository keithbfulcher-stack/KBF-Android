# KBF App - Android

Official Keith B. Fulcher music player for Android.

## Features
- Plays all tracks from SoundCloud (Keith B. Fulcher)
- Native Android player with background playback, lock screen controls
- Album art, bio, links
- Built with Kotlin + Jetpack Compose + Media3 ExoPlayer

## Setup
1. Open in Android Studio
2. Add your SoundCloud Client ID in local.properties: `SOUNDCLOUD_CLIENT_ID=xxx`
   - Or use public embed without API: app falls back to SoundCloud oEmbed / public stream URLs
3. Update SOUNDCLOUD_PROFILE_URL in MainViewModel.kt if needed: https://on.soundcloud.com/8kOP330AyXnEai460b
4. Build & Run

## Structure
- app/src/main/java/com/kbf/music/
  - MainActivity.kt
  - player/PlayerService.kt (foreground service for background audio)
  - ui/KBFApp.kt (Compose UI)
  - data/SoundCloudRepository.kt
- Works without private API - uses SoundCloud public API via widget API resolve.

To publish to Play Store: Generate signed APK/AAB in Android Studio > Build > Generate Signed Bundle.
Package name: com.kbf.music
App name: KBF

You own all code.

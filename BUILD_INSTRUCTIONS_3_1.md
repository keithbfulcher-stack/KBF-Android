
# KBF Android - Build APK for Play Store

1. Open KBF-Android folder in Android Studio Hedgehog or newer
2. File > Sync Gradle
3. To generate APK: Build > Build Bundle(s) / APK(s) > Build APK(s)
   APK will be at app/build/outputs/apk/debug/app-debug.apk
4. To generate AAB for Play Store: Build > Generate Signed Bundle / APK > Android App Bundle
   - Create new keystore if you don't have one (save it!)
   - Package: com.kbf.music
   - Upload AAB to play.google.com/console

Testing: Install APK directly on your phone, enable Live Auto-Sync will pull ALL tracks from soundcloud.com/keith-fulcher-549796740

Play Store listing:
- Name: KBF - Keith B. Fulcher
- Short desc: Official music app streaming all tracks from SoundCloud - auto-syncs new releases
- Full desc: Stream Broken, Asi Me Ve Dios, Can't Nobody, Be the Example and all future releases by Keith B. Fulcher. Live auto-sync with SoundCloud.
- Category: Music & Audio
- Content rating: Everyone

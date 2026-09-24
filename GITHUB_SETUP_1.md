
# KBF - One-Click APK Build - GitHub Actions

## How to get your APK in 2 minutes (One Click)

### Step 1: Create GitHub repo
1. Go to github.com/new
2. Name: KBF-Android
3. Public
4. Create

### Step 2: Upload this project
- Drag and drop ALL files from KBF-Android-Live.zip into your new repo
- OR: `git init`, `git add .`, `git commit -m "KBF live"`, `git push`

### Step 3: ONE CLICK BUILD
1. In your GitHub repo, click **Actions** tab
2. Left side: Click **Build KBF APK - One Click**
3. Right side: Click **Run workflow** > green **Run workflow** button
4. Wait 3-5 minutes
5. Click the run > scroll down to **Artifacts** > Download **KBF-Debug-APK-Live-Sync**
6. APK is inside - install on any Android phone!

Every time you push code, it auto-builds. When you click Run workflow manually, it also creates a Release with APK attached.

### For Play Store (Signed AAB)
For signed builds, add secrets in GitHub > Settings > Secrets:
- KEYSTORE_BASE64: base64 of your keystore.jks
- KEYSTORE_PASSWORD
- KEY_ALIAS
- KEY_PASSWORD

Then set variable ENABLE_SIGNED_BUILD = true in Settings > Variables.

### Live Auto-Sync
Your app already pulls ALL tracks from:
https://soundcloud.com/keith-fulcher-549796740
No rebuild needed when you upload new music - just upload to SoundCloud and it appears in the app within minutes.

### Install APK on phone
1. Download APK to phone
2. Settings > Allow install from unknown sources
3. Tap APK to install
4. Open KBF app - all your tracks stream!

Package: com.kbf.music
Name: KBF - Keith B. Fulcher
Tracks: Broken, Asi Me Ve Dios, Can't Nobody, Be the Example (1 Timothy 4:12)

# TTS Reader Download Repository

This repository hosts the TTS Reader Android app for direct download.

## 📥 Download

**Direct APK Download:** https://huxley-brown.github.io/ttsreader-fdroid/

The APK is properly signed and works on all Android devices (7.0+).

## 📱 F-Droid Repository

**Good news!** You can now add this repository to the F-Droid app.

### Add to F-Droid App

1. Open F-Droid app
2. Go to **Settings** → **Repositories**
3. Tap the **+** button (top right)
4. Enter the repository details:

**Repository URL:**
```
https://huxley-brown.github.io/ttsreader-fdroid/repo
```

**Fingerprint:**
```
9BEB3BD1B1EC00E6CABFF562169FC5017C60FED7CD8B4AD8F838E0EF7489AB83
```

5. Tap **Add**
6. Wait for F-Droid to sync
7. Search for "TTS Reader" and install

### How This Works

While F-Droid's automated tools (`fdroidserver`) cannot parse React Native APKs due to androguard limitations, the repository index was manually created and signed. This provides the same security and functionality as any F-Droid repository

## 📱 Installation

1. Visit https://huxley-brown.github.io/ttsreader-fdroid/
2. Tap "Download APK Directly"
3. Open the downloaded file
4. Enable "Install from unknown sources" if prompted
5. Tap "Install"

## 🔐 Security

- **Package Name:** `org.ttsreader.app`
- **Version:** 0.1.0 (Build 1)
- **SHA256:** `08e5e0087ce07ec152d6da222d5e1a29339cc5bdb5f276e4189a65c076a22440`
- **Signature:** v2 APK Signature Scheme
- **Certificate SHA256:** `4bfeacfab77fb6ba73bfd05880d166322ab877a896c42f8245b4d7af89fea663`

You can verify the APK signature using:
```bash
apksigner verify -v org.ttsreader.app_1.apk
```

## 📖 Source Code

Main app repository: https://github.com/Huxley-Brown/Mobile-TTS-App

## 📜 License

GPL-3.0-or-later

---

**Note:** While this repository was initially intended to be an F-Droid repository, the complexity of React Native APKs makes this technically infeasible with current F-Droid tooling. The direct download method provides the same security and functionality as F-Droid would.

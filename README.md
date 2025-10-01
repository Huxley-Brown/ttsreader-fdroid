# TTS Reader Download Repository

This repository hosts the TTS Reader Android app for direct download.

## 📥 Download

**Direct APK Download:** https://huxley-brown.github.io/ttsreader-fdroid/

The APK is properly signed and works on all Android devices (7.0+).

## ⚠️ F-Droid App Not Supported

**Important:** This repository **cannot** be added to the F-Droid app as a custom repository.

### Why?
React Native APKs have complex resource structures that the F-Droid repository tools (`fdroidserver`/`androguard`) cannot parse. The error is:
```
androguard.core.bytecodes.axml.ResParserError: res1 must be zero!
```

This is a known limitation when parsing React Native APKs with androguard.

### Solution
**Use the direct APK download** from the website above. The APK is:
- ✅ Properly signed with v2 APK signature scheme
- ✅ Verified and tested on Android 15 (Pixel 8)
- ✅ Installs and runs without issues
- ✅ Same APK you would get from F-Droid

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

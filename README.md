# Revanced-Morphe-Magisk

My personal Magisk module and APK builder using patches from [Morphe](https://github.com/MorpheApp), [crimera/piko](https://github.com/crimera/piko) and [RookieEnough/De-Vanced](https://github.com/RookieEnough/De-Vanced).

> Fork of [j-hc/revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module) — customized for personal use.

[![CI](https://github.com/LuxiestLux/Revanced-Morphe-Magisk/actions/workflows/build.yml/badge.svg)](https://github.com/LuxiestLux/Revanced-Morphe-Magisk/actions/workflows/build.yml)

---

## 📦 Download

Latest modules and APKs are available in the [Releases](https://github.com/LuxiestLux/Revanced-Morphe-Magisk/releases) tab.

---

## 📱 What's included

| App | Patch source | Output |
|-----|-------------|--------|
| YouTube (Morphe) | [MorpheApp/morphe-patches](https://github.com/MorpheApp) | Module + APK |
| YouTube Music (Morphe) | [MorpheApp/morphe-patches](https://github.com/MorpheApp) | Module + APK |
| X / Twitter (Piko) | [crimera/piko](https://github.com/crimera/piko) | Module + APK |
| Google Photos | [RookieEnough/De-Vanced](https://github.com/RookieEnough/De-Vanced) | Module + APK |

All modules are built for **arm64-v8a** architecture.

---

## ⚙️ Installation

### Root (Magisk / KernelSU)
1. Download the `.zip` file from [Releases](https://github.com/LuxiestLux/Revanced-Morphe-Magisk/releases)
2. Flash it via Magisk or KernelSU
3. Reboot your device
4. Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from the Play Store — this prevents them from being overwritten by an update

### Non-root (APK)
1. Download the `.apk` file from [Releases](https://github.com/LuxiestLux/Revanced-Morphe-Magisk/releases)
2. Install [Morphe MicroG-RE](https://github.com/MorpheApp) (required for YouTube and YT Music to work)
3. Install the downloaded APK

---

## 🔄 Updates

Modules notify you about new versions directly inside the Magisk / KernelSU app.

Builds run automatically every day via GitHub Actions whenever new patches are released.

---

## ⚠️ Known issues

If you see a **"Reflash needed"** error after reboot or a **"Suspicious mount detected"** warning from root detector apps, try using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount).

---

## 🙏 Credits

- [j-hc](https://github.com/j-hc) — for the original builder, zygisk-detach and rvmm-zygisk-mount
- [MorpheApp](https://github.com/MorpheApp) — for the Morphe patches and CLI
- [crimera](https://github.com/crimera) — for the piko patches for X / Twitter
- [RookieEnough](https://github.com/RookieEnough) — for the De-Vanced patches for Google Photos

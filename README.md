<div align="center">

<img src="logo.png" alt="CyberBenji" width="96" height="96">

# CyberBenji

**A free, on-device security toolkit for Android.**

Scan links, files and messages · block malicious domains · monitor threats · check your digital footprint — no account, no cost.

### [⬇️ Download the app](https://namarabenjaminkamugisha-arch.github.io/cyberbenji-app/)

[![Download APK](https://img.shields.io/badge/Download-APK-58A6FF?style=for-the-badge&logo=android&logoColor=white)](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji.apk)
[![Latest release](https://img.shields.io/github/v/release/namarabenjaminkamugisha-arch/cyberbenji-app?style=for-the-badge&color=2EA043)](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest)

</div>

---

## What it does

| Feature | Description |
|---|---|
| 🔗 **Scan links, files & messages** | Check a URL, QR code, downloaded file or suspicious message against threat intelligence before you trust it. |
| 🛡️ **Live threat monitor** | Watches incoming notifications for phishing and scam patterns and warns you in real time. |
| 🌐 **DNS Guard** | Blocks ads, trackers, malware and adult domains device-wide using a local, private DNS filter. |
| 📡 **Network & exposure** | See the devices on your Wi-Fi and check what the public internet can see about your connection. |
| 🔎 **Digital footprint (OSINT)** | Find where your username or email appears online and whether it's in a known data breach. |
| 🧰 **Privacy tools** | Inspect file metadata and other on-device utilities to understand what you share. |

## Install

1. **[Download the APK](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji.apk)** on your phone (~25 MB, Android 8.0+). Older or 32-bit phones can use the [universal build](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji-universal.apk) (~70 MB) instead.
2. When prompted, allow your browser or Files app to **install unknown apps** (required for any app installed outside the Play Store).
3. Tap the downloaded file to install, then open it. No account, no payment.

> Each release lists the APK's **SHA-256** so you can verify the file you downloaded is the official one.

### Download stops at 100% / won't finish?

Some browsers (especially Chrome) block `.apk` downloads. Two free fixes:

- **Download the [ZIP version](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji-apk.zip)** (~16 MB), then open it in your Files app, extract it, and tap the `.apk` inside. Browsers don't block ZIP files.
- **Or use Firefox / Samsung Internet** instead of Chrome — they let `.apk` files download normally.

After downloading, if Android warns the app is "unknown", tap **More details → Install anyway** (normal for any app outside the Play Store).

### Want automatic updates? (optional)

[**Obtainium**](https://obtainium.imranr.dev) is a free, open-source app that installs CyberBenji straight from GitHub and notifies you when a new version ships — like a Play Store, with no account or cost:

1. Install Obtainium (from [obtainium.imranr.dev](https://obtainium.imranr.dev) or its [GitHub releases](https://github.com/ImranR98/Obtainium/releases/latest)).
2. Open it → **Add App** → paste `https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app` → **Add**.
3. If asked which file, pick `cyberbenji.apk`, then **Install**. Obtainium handles all future updates automatically.

## Privacy & security

- Scans run **on-device**. There are no user accounts and no analytics tracking you.
- When a feature needs external threat intelligence (e.g. to check a link), only the item being checked is sent to the relevant lookup service — never your personal data.
- **Android only** for now. Several features rely on Android system services that don't exist on other platforms.
- CyberBenji is a real toolkit, not magic — it raises the bar against common threats but can't guarantee protection from every attack.

## About this repository

This public repo contains **only** the landing page and hosts the signed APK as a release asset. The application source code is maintained privately.

Built independently. Not affiliated with any security vendor or platform.

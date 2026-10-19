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

The main download is a **ZIP** (~16 MB) so it finishes in any browser — Chrome blocks raw `.apk` files, but not ZIPs.

1. **[Download CyberBenji](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji-apk.zip)** on your phone, then open the saved file in your Files app and **extract** it. If your Files app can't unzip, install **ZArchiver** (free) and extract with that.
2. Tap the extracted `cyberbenji.apk`. Allow **install unknown apps** if asked (required outside the Play Store).
3. If Android warns the app is "unknown", tap **More details → Install anyway**, then open it. No account, no payment.

> Each release lists the file **SHA-256** so you can verify your download is the official one.

### Prefer not to unzip? Two free options

- **Firefox** (free from the Play Store): open this page in Firefox and tap the [direct APK link](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji.apk) (~28 MB). Firefox lets `.apk` files download normally — nothing to unzip.
- **Obtainium** (auto-updates): [**Obtainium**](https://obtainium.imranr.dev) installs CyberBenji from GitHub and keeps it updated. Install it, tap **Add App**, paste `https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app`, then pick `cyberbenji.apk`.

> Older or 32-bit phones: use the [universal APK](https://github.com/namarabenjaminkamugisha-arch/cyberbenji-app/releases/latest/download/cyberbenji-universal.apk) (~70 MB), opened in Firefox.

## Privacy & security

- Scans run **on-device**. There are no user accounts and no analytics tracking you.
- When a feature needs external threat intelligence (e.g. to check a link), only the item being checked is sent to the relevant lookup service — never your personal data.
- **Android only** for now. Several features rely on Android system services that don't exist on other platforms.
- CyberBenji is a real toolkit, not magic — it raises the bar against common threats but can't guarantee protection from every attack.

## About this repository

This public repo contains **only** the landing page and hosts the signed APK as a release asset. The application source code is maintained privately.

Built independently. Not affiliated with any security vendor or platform.

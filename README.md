# Kontime Kiosk for Android — releases

Signed Android builds of **Kontime Kiosk**, the tablet time clock of Kontime by Komma SoftHouse.

## Install

1. Open the [latest release](https://github.com/komma-softhouse/kontime-kiosk-android-releases/releases/latest) on your phone.
2. Download `Kontime-Kiosk-<version>.apk`.
3. Open it. The first time, Android asks you to allow installing apps from your browser; allow it once and tap **Install**.

## Update

The kiosk checks this repository itself: **⚙ → Updates → Check for updates**, then **Download and install**. Every build is signed with the same key, so updates install over the current version and keep your data.

## Verify a download

Each release ships a `.sha256` file next to the APK:

```bash
shasum -a 256 -c Kontime-Kiosk-<version>.apk.sha256
```

## Pairing

In Kontime → Devices, tap **Tablet** on the device this tablet will be and scan the QR with the app. The kiosk only talks to your own Kontime server.

## Support

support@kommasofthouse.com · https://kontime.kommasofthouse.com
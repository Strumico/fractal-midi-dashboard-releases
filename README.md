# Fractal MIDI Dashboard — Downloads

Public **APK downloads** for Fractal MIDI Dashboard.

The app source code lives in a **private** repository. This repo only hosts installable releases.

---

## Install the app (on the phone)

1. Open the latest release:  
   **https://github.com/Strumico/fractal-midi-dashboard-releases/releases/latest**
2. Download **`FractalMIDI-vX.Y.Z.apk`** only (ignore GitHub’s auto “Source code” zip/tar links).
3. If Android asks, allow **Install unknown apps** for Chrome or Files.
4. Tap the downloaded file → **Install**.
5. Open **Fractal MIDI Dashboard**.

Direct link (current):  
**https://github.com/Strumico/fractal-midi-dashboard-releases/releases/download/v1.12.0/FractalMIDI-v1.12.0.apk**

---

## Plug in the WIDI Jack

The WIDI Jack has **two** small MIDI sockets. Use **both** cables:

| WIDI Jack socket | Plug into the FM9 |
|---|---|
| ▲ (arrow up) | **MIDI OUT / THRU** |
| ▼ (arrow down) | **MIDI IN** |

- ▲ also powers the WIDI from the FM9 in most setups.
- If the WIDI does not power on, plug **USB-C 5V** into the WIDI as well.

---

## Set these 3 things on the FM9 (required)

On the FM9 go to **SETUP → MIDI/Remote**:

| # | Setting | Value |
|---|---|---|
| 1 | **MIDI Thru** | **OFF** |
| 2 | **MIDI Channel** | **1** |
| 3 | **Send MIDI PC** | **Channel 1** |

---

## Connect the phone to the WIDI

1. Phone: **Settings → Bluetooth** → pair **WIDI Jack**.
2. Open the app → tap the connection badge → **Scan / Refresh** → tap **WIDI Jack**.
3. Set device type to **FM9**.

---

## Quick “is it working?” test

1. FM9: MIDI Thru **OFF**, Channel **1**, Send MIDI PC **Channel 1**
2. App connected to WIDI
3. Performance → **SYNC NAMES** → preset name appears
4. Change a scene from the phone → FM9 follows

---

## Support / source

Source code is private. For issues or access, contact the repo owner.

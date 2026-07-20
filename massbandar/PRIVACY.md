# Privacy Policy — Digitales Maßband (Tape Measure AR)

_Last updated: 2026-05-25_

Digitales Maßband ("we", "our", "us") is an AR tape-measure app that
respects your privacy. This Privacy Policy explains what data the app
handles, how it is used, and what choices you have.

**Summary in one sentence**: Digitales Maßband collects nothing, transmits
nothing, and stores measurements only on your device.

## 1. Data we collect

**None.** The app does not collect, transmit, sell, or share any personal
data with us, our partners, or third parties.

Specifically, the app does **not** access or collect:

- Your name, email, phone number, or account credentials
- Location data (GPS, IP-based, or otherwise)
- Microphone or contacts
- Advertising identifiers
- Health, fitness, motion, or sensor data beyond what ARKit uses on-device
- Usage analytics or crash reports

## 2. Camera and AR data

The app **requires camera access** to perform Augmented Reality
measurement. Camera frames are processed **entirely on your device** by
Apple's ARKit framework. They are never stored, copied to disk, or
transmitted off the device.

Likewise, the ARKit world-tracking state (anchors, mesh, plane geometry)
exists only in memory during a session and is discarded when the app closes.

## 3. Data stored on your device

| Item | Why it exists |
|---|---|
| Measurement history (last 50 segments + timestamps) | So you can review past measurements |
| Unit preference (m / cm / in / ft) | So your last choice persists across launches |

All stored locally in iOS's UserDefaults. No background services touch it.

## 4. Optional photo saving

If you tap the camera button to save a screenshot, the app asks for
permission to **add photos** to your Photos library (and only add — it
cannot read your existing photos). The saved image is a standard PNG you
can delete or share like any other photo.

## 5. Permissions

| Permission | Used? | Notes |
|---|---|---|
| Camera | ✅ Required | AR measurement; processed on-device only |
| Photos (add only) | ⚠ On request | Only when you tap the screenshot button |
| Microphone | ❌ Never requested | |
| Notifications | ❌ Never requested | |
| Location | ❌ Never requested | |
| Contacts | ❌ Never requested | |
| Health / Motion | ❌ Never requested | |

## 6. Network activity

Digitales Maßband makes **no network requests of any kind**. The app:

- Does not contact our servers (there are no servers)
- Does not load any web content
- Does not include any third-party analytics SDKs
- Does not include any advertising SDKs

You can verify this by enabling iOS's network privacy report and looking
under Digitales Maßband — the list will be empty.

## 7. Data sharing

We do **not** sell, rent, share, or transfer any data to any third party.
There is nothing to share, because nothing is collected.

## 8. Your rights and choices

- **Clear measurement history**: tap the trash icon in-app, or delete the
  app to remove all local data (iOS will remove the app sandbox completely).
- **Revoke camera or photo permission**: iOS Settings → Digitales Maßband.

## 9. Children

Digitales Maßband is rated 4+ and does not collect any data, so it is safe
for users of any age.

## 10. Changes to this policy

If we ever add functionality that requires collecting data, this policy will
be updated and the in-app "What's New" notes will explain the change before
it takes effect. As of this version: nothing changes the no-collection
guarantee above.

## 11. Contact

Questions or concerns about privacy? Open an issue at
[github.com/fengyiqicoder/open/issues](https://github.com/fengyiqicoder/open/issues)
or email annaaiannaaiannaai@gmail.com.

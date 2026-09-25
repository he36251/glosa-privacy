# Privacy Policy for Glosa

**Last updated: 13 August 2026**

Glosa is an offline translation app. It translates text, speech, and images using a language model that runs entirely on your device.

**Glosa does not collect, transmit, or store any of the text, speech, or images you translate.** Translation happens on your phone. You can verify this by enabling airplane mode after the initial setup — the app continues to work normally.

---

## What stays on your device

All of the following is processed locally and never leaves your phone:

- **Text you type or paste** for translation.
- **Speech you dictate.** Audio is transcribed by your device's own speech recognition and is never uploaded by Glosa.
- **Photos and camera frames.** Text recognition (OCR) runs on-device via Google ML Kit. Images are not uploaded.
- **Your translation history and sessions**, stored in your device's app storage.
- **Your settings** — chosen languages, tone, interface language, and selected model.

This data is stored only on your device. Uninstalling Glosa deletes all of it. Glosa has no user accounts, no login, no sync, and no server that receives your content.

## What leaves your device

Glosa makes network requests of three kinds, none of which carries your translations, speech, or photos.

**1. The one-time model download.** On first launch you choose a language model, which Glosa downloads from a public repository on Hugging Face (`huggingface.co`). Like any web request, Hugging Face's servers can see your IP address and the file requested. No account or token is needed and Glosa sends them nothing that identifies you. Hugging Face's privacy policy: https://huggingface.co/privacy

**2. Ads.** Glosa is free and supported by advertising served by Google AdMob.
Ad requests are always **non-personalized**: Glosa does not build or use a
profile of you to target them. Serving an ad involves Google receiving your IP
address, a device advertising identifier, and coarse device and network
information, which Google uses to deliver the ad and to detect fraud. Glosa
never sends your translations, your speech, your photos, or your history to
any advertiser — none of that data leaves your device at all. Google's
advertising privacy information: https://policies.google.com/technologies/ads

**3. Crash reports.** Glosa uses Google Firebase Crashlytics to find and fix crashes. When the app crashes, Crashlytics collects:

- a technical stack trace of the crash,
- device model, operating system version, and app version,
- a randomly generated Firebase installation identifier.

Crash reports never contain your translations, dictated speech, photos, or history. The installation identifier is not linked to your name, email, or any account, and is not used for advertising or tracking. Firebase's privacy information: https://firebase.google.com/support/privacy

## What Glosa does not do

- No **personalized** advertising — ad requests are non-personalized, and Glosa never builds a profile of you to target them (see item 2 above).
- No analytics of how you use the app.
- No tracking across apps or websites, and no data sold or shared with data brokers.
- No user accounts, and no email or phone number collected.
- No location access.

## Permissions and why they are requested

| Permission | Why |
| --- | --- |
| Microphone | To dictate text for translation. Audio is processed on-device. |
| Camera | To recognize text in the live camera view. Frames are processed on-device. |
| Photos / storage | To translate text in a picture you choose. Images are processed on-device. |
| Internet, network state | To download the language model, to load ads, and to send crash reports. Never to send anything you translate. |
| Foreground service, notifications, wake lock | To keep the large model download running when your screen turns off, and to show its progress. |

Every permission is requested only when you first use the feature that needs it, and the app remains usable without granting them.

## Children's privacy

Glosa is not directed at children and does not knowingly collect personal information from anyone, including children under 13.

## Your choices

- **Delete your data:** clear the app's storage in your device settings, or uninstall Glosa. Both remove all history, sessions, settings, and the downloaded model.
- **Opt out of crash reporting:** uninstall the app, or contact us at the address below to request deletion of crash data associated with your installation.

## Changes to this policy

If this policy changes materially, the updated version will be published here with a new date.

## Contact

Questions about this policy or about your data: **gawo.he@gmail.com**

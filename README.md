# Privacy Policy — Tonely

**Effective date:** 3 August 2026
**Last updated:** 3 August 2026

Tonely ("the app") is a photo and video editor for iOS published by KTN Apps. This policy explains what the app does with your data. The short version: everything stays on your device. We operate no servers, collect no analytics, and have no way to see your photos, videos, or edits.

## 1. Data we collect

**None.** Tonely does not collect, transmit, sell, or share any personal data. The app contains no analytics SDKs, no advertising SDKs, no crash-reporting services, and no tracking of any kind. It makes no network requests other than opening links you tap (this policy page and the support email address), which are handled by Safari and Mail.

No account is required. There are no subscriptions or in-app purchases.

## 2. Data the app stores on your device

All of the following is stored locally in the app's sandboxed container and is removed when you delete the app.

| Data | Where | Why |
| --- | --- | --- |
| Imported photos and videos | App Documents directory | So projects can be reopened and re-edited |
| Edit parameters (curves, HSL, presets, crop) | Local JSON alongside each project | Non-destructive editing — originals are never overwritten |
| Saved recipes and presets | Local store | Reuse your looks across projects |
| App settings and onboarding state | `UserDefaults` | Remember your preferences |
| Diagnostic breadcrumbs | Local device log (Apple `OSLog`) | Troubleshooting on your own device; never transmitted |

Diagnostic breadcrumbs record event names such as `app_launch` or `error: export_failed`. File paths and error details are marked private so they are redacted in device logs. Nothing from these logs leaves your device unless you choose to send Apple a sysdiagnose.

## 3. Permissions we request

- **Photo Library (read)** — to let you pick photos and videos to edit. Tonely reads only the items you select.
- **Photo Library (add)** — to save your exports, collages, and edited videos back to Photos. Tonely writes only the files you explicitly export.
- **Camera** — used only while the in-app camera screen is open, to capture photos directly into the editor. Captures stay on your device.

You can revoke any of these at any time in iOS Settings → Privacy & Security. The app remains usable with reduced functionality.

## 4. Processing

All image and video processing — colour science, tone curves, per-channel HSL, presets, collage composition, video grading and trimming — runs locally using Apple's Core Image and AVFoundation frameworks on your device's CPU and GPU. No media is uploaded anywhere.

## 5. Third parties

Tonely uses no third-party SDKs or services. The only Apple services involved are the standard on-device frameworks (Photos, AVFoundation, Core Image) and, if you download the app from the App Store, Apple's own reporting to us — which is aggregate and anonymous, governed by [Apple's privacy policy](https://www.apple.com/legal/privacy/).

## 6. Children

Tonely is not directed at children under 13 and collects no data from anyone, including children.

## 7. Your rights

Because we hold no data about you, there is nothing for us to export, correct, or delete on request. To remove everything Tonely has stored, delete the app; iOS removes its container, including all projects, recipes, and settings. Photos you exported to your Photos library remain there and are managed by you.

Under GDPR and CCPA terms: we are not a data controller or processor of your personal data, since none is transmitted to us. We do not sell or share personal information.

## 8. Security

Data stays inside the app's iOS sandbox, protected by your device passcode and iOS file-level encryption. If you use iCloud Backup, your device backup may include the app's stored projects; that backup is governed by Apple's terms and encryption.

## 9. Changes

If this policy changes, the updated version will be posted at https://tonely.app/privacy with a new "Last updated" date. Material changes will also be noted in the App Store release notes.

## 10. Contact

Questions about this policy: **ktnapps@gmail.com**

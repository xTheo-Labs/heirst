<p align="center">
  <img src="https://heirst-web.vercel.app/og/og-default-en.png" alt="Heirst — Take control of your digital life" width="100%">
</p>

# Heirst

Privacy-first Android tools that keep a phone clean and secure without servers, accounts, or root access.

| | |
|---|---|
| **Status** | Public beta |
| **Platform** | Android |
| **Website** | <https://heirst-web.vercel.app> (English and Indonesian) |
| **Download** | Signed APKs on the website |

## Products

### Heirst Clean

A storage cleaner that shows you everything before anything is removed.

- Finds duplicate and similar photos, large files, folders left behind by uninstalled apps, and outdated APK files.
- Every file is reviewed by the user before deletion; nothing is removed automatically.
- No `INTERNET` permission: the app cannot send data anywhere.

### Heirst Secure

A security check-up for the phone.

- Audits dangerous combinations of app permissions.
- Inspects APK files before they are installed.
- Produces a device posture report and checks newly installed apps.
- Findings are presented as clues with an explanation, not as verdicts.

## Principles

- **No servers and no accounts.** All analysis runs on the device.
- **No root required.**
- **Transparent by default.** The user sees and confirms every action.

## Quality

- Heirst Clean: 547 automated tests. Heirst Secure: 188 automated tests.
- Unit tests and Android lint run in CI on every change.

## Known limitations

- Some newer features are still being verified on a range of physical devices.
- Not yet published on Google Play.

## Source code

The source code is private. For licensing, partnerships, or a private demo, contact **mail.harastaputra@gmail.com**.

---

Heirst is a product of [xTheo Labs](https://xtheo-labs.vercel.app) by [Harasta Rahman Tri Putra](https://github.com/xtheoputra). © 2026. All rights reserved.

# VirusTotal Mobile — Privacy Notice

*Last updated: 1 November 2026 · [Español](es)*

This Privacy Notice describes how the Android app **VirusTotal Mobile** (package `com.funnycat.virustotal`, "the app"), developed by Funnycat, collects and processes information. The app lets you check installed apps, files and URLs for malware using the VirusTotal service. It has no user accounts, no advertising, no analytics or tracking libraries, and we operate no server that stores your data. This notice does not cover the VirusTotal service itself, which is governed by its own notice (<https://docs.virustotal.com/docs/privacy-policy>).

## Information the app collects and processes

- **Installed-app information.** To check your apps, the app reads the list of installed apps (name, package name, version, requested permissions) and computes the SHA-256 hash of each APK. Hashes are sent to VirusTotal to look up the app's reputation.
- **Files you submit.** The APK of an installed app VirusTotal does not know yet is uploaded **only if Auto-upload is enabled** in Settings (it can be switched off at any time; it runs only on unmetered networks with non-low battery). Files and URLs you choose to scan are uploaded only when you start the scan.
- **Your VirusTotal API key.** If you enter a personal API key, it is stored encrypted on your device and sent to VirusTotal only with the file and URL requests you make.
- **Scan history and settings.** Results, hashes, names and preferences are stored in a local database on your device.
- **Technical details for notifications.** The app uses Firebase Cloud Messaging; Google assigns the device a registration token to deliver notifications (<https://firebase.google.com/support/privacy>).

We do **not** collect your name, email, location, contacts or advertising ID.

## Why we process it

- To provide the checks you request: app, file and URL analysis.
- To run scans and show results and notifications in the background if you enable it.
- To keep your scan history and settings on your device.

## Sharing

We do not sell your information, and we do not receive it: data goes from your device directly to VirusTotal (operated by Google) and, for notifications, to Firebase Cloud Messaging (Google). **Files and URLs submitted to VirusTotal can be shared with the security community**, so do not scan files containing private information.

## Retention

Data held on your device stays until you delete your history, clear the app's storage, or uninstall the app. Retention of data submitted to VirusTotal is governed by VirusTotal's own notice.

## Security

The API key is encrypted on the device. All communication with VirusTotal uses HTTPS.

## Your choices and rights

You can disable background scanning and Auto-upload, remove your API key, delete your history, or uninstall the app at any time. Because we hold no personal data about you on our own servers, requests about data submitted to VirusTotal must be made to VirusTotal.

## Permissions

Internet and network state (contact VirusTotal); query all packages (list installed apps to check them, the app's core purpose); notifications; foreground service for data sync, wake lock and boot completed (background scans).

## Children

The app is not directed at children under 13 and does not knowingly collect their information.

## Changes

If this notice changes, the new version is published at this address with an updated date.

## Contact

Open an issue at <https://github.com/danielgf3/VirusTotal-Mobile-Privacy/issues>.

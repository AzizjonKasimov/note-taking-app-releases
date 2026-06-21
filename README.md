# Notes — Releases

Public download host for the **Notes** Android app. The app's source code lives in a
separate private repository; this repo holds only the built APKs and a small version
manifest the in-app updater reads.

- **`version.json`** — metadata for the latest version (version code/name, APK URL, release notes). The app fetches this on launch to decide whether to offer an update.
- **APK downloads** — see the [Releases](../../releases) page.

To install manually, download the latest `Notes-x.y.apk` from Releases and open it on your phone
(allow installs from this source). Once installed, the app updates itself.

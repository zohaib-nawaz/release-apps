# Release apps

Downloadable Android builds of Zohaib Nawaz's apps. Each app has one release with a fixed tag, and its APK is replaced in place on every new version, so the download link never changes.

| App | What it does | Version | Download | Release notes |
| --- | --- | --- | --- | --- |
| Zohaib Portfolio | Zohaib Nawaz's portfolio as an app | 1.0.0 | [zohaib-portfolio.apk](https://github.com/zohaib-nawaz/release-apps/releases/download/zohaib-portfolio/zohaib-portfolio.apk) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/zohaib-portfolio) |
| ZN GIFC | Sticker, GIF, video, image and PDF converter | 1.1.0 | [zn-gifc.apk](https://github.com/zohaib-nawaz/release-apps/releases/download/zn-gifc/zn-gifc.apk) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/zn-gifc) |
| ZN Speed | Internet speed test with signal map | 1.4 | [zn-speed.apk](https://github.com/zohaib-nawaz/release-apps/releases/download/zn-speed/zn-speed.apk) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/zn-speed) |

## Install on Android

1. Download the APK on your phone.
2. Open it. If Android asks, allow "Install unknown apps" for your browser or file manager.
3. Tap Install.

Updates install over the old version because every build of an app is signed with the same key.

## Desktop apps

| App | What it does | Version | Download | Release notes |
| --- | --- | --- | --- | --- |
| Digital Eye Strain Reminder | Tray app for the 20-20-20 eye break rule | 1.0.0 | [Mac (Apple Silicon)](https://github.com/zohaib-nawaz/release-apps/releases/download/digital-eye-strain/digital-eye-strain-mac-arm64.dmg) · [Windows](https://github.com/zohaib-nawaz/release-apps/releases/download/digital-eye-strain/digital-eye-strain-win-x64.zip) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/digital-eye-strain) |
| Zunaira | Voice AI companion with Gemini Live and PC control (bring your own Gemini key) | 1.0.0 | [Windows installer](https://github.com/zohaib-nawaz/release-apps/releases/download/zunaira/zunaira-setup-win-x64.exe) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/zunaira) |

Desktop builds are not signed by Apple or Microsoft yet. On Mac, right-click the app and choose **Open** the first time. On Windows, click **More info** then **Run anyway** if SmartScreen appears.

## Games

| Game | What it is | Version | Download | Release notes |
| --- | --- | --- | --- | --- |
| Orbit Keeper | One-thumb arcade game built for YouTube Playables | 1.0.0 | [orbit-keeper-web.zip](https://github.com/zohaib-nawaz/release-apps/releases/download/orbit-keeper/orbit-keeper-web.zip) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/orbit-keeper) |

The web build has to be served, not opened as a file: upload the unzipped folder to any static host, or run `npx serve` inside it.

## Browser extensions

| Extension | What it does | Version | Download | Release notes |
| --- | --- | --- | --- | --- |
| ZCatcher | Catch every image on a page and download them as a ZIP | 1.0 | [zcatcher.zip](https://github.com/zohaib-nawaz/release-apps/releases/download/zcatcher/zcatcher.zip) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/zcatcher) |
| Universal Cloud Saver | Save images, videos, PDFs and files straight to Google Drive | 1.0.0 | [universal-cloud-saver.zip](https://github.com/zohaib-nawaz/release-apps/releases/download/universal-cloud-saver/universal-cloud-saver.zip) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/universal-cloud-saver) |
| NETVRON | Video and stream downloader; blocked-site badges coming soon | 1.0.0 | [netvron-chrome.zip](https://github.com/zohaib-nawaz/release-apps/releases/download/netvron/netvron-chrome.zip) | [Release](https://github.com/zohaib-nawaz/release-apps/releases/tag/netvron) |

## Install a browser extension

Works in Chrome, Edge, Brave and other Chromium browsers.

1. Download the ZIP and unzip it into a folder you will keep (the browser loads it from there).
2. Open `chrome://extensions` and turn on **Developer mode** (top right).
3. Click **Load unpacked** and choose the unzipped folder.
4. Pin the extension from the puzzle icon in the toolbar.

To update, download the new ZIP, replace the folder contents, and press the reload icon on the extension card.

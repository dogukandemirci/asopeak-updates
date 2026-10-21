# AsoPeak Updates

Public release channel for **[AsoPeak](https://asopeak.app)**, the App Store keyword and ratings tracker for macOS.

This repository does not contain the app's source code. It hosts what the app and the website need to deliver new
versions:

| What | Where |
|---|---|
| Latest download | [AsoPeak.dmg](https://github.com/dogukandemirci/asopeak-updates/releases/latest/download/AsoPeak.dmg) |
| All releases | [Releases](https://github.com/dogukandemirci/asopeak-updates/releases) |
| In-app update feed (Sparkle) | [`appcast.xml`](https://dogukandemirci.github.io/asopeak-updates/appcast.xml) on the `gh-pages` branch |
| Release notes | [asopeak.app/changelog](https://asopeak.app/changelog) · [`changelog.js`](changelog.js) |

## Updating AsoPeak

AsoPeak checks for updates by itself once a day. To check now, choose **AsoPeak › Check for Updates…** in the
menu bar, or open **Settings › Support › Check for Updates**.

## Security

Every release is signed with an Apple Developer ID certificate and notarized by Apple. Each update in the feed also
carries an EdDSA signature that the app verifies before installing, so an update that was not signed by AsoPeak is
rejected.

## Requirements

macOS 15 Sequoia or later, on Apple silicon or Intel.

## Support

Questions or problems: [hello@asopeak.app](mailto:hello@asopeak.app).

---

This repository is updated automatically by AsoPeak's release process. Please do not open pull requests here.

# WatchIPTV — releases

Public APK downloads of **WatchIPTV**: IPTV channels and RTSP camera streams on your phone, Android TV and Wear OS watch. Nothing is built in: you add your own playlists and streams, and they are stored encrypted on your device.

Latest version:

- **[phone](https://github.com/il90il90/WatchIPTV-releases/releases/latest/download/WatchIPTV-phone.apk)**
- **[Android TV](https://github.com/il90il90/WatchIPTV-releases/releases/latest/download/WatchIPTV-tv.apk)**
- **[Wear OS watch](https://github.com/il90il90/WatchIPTV-releases/releases/latest/download/WatchIPTV-watch.apk)**

[All versions](https://github.com/il90il90/WatchIPTV-releases/releases)

The easiest way to install it and keep it up to date is [Israel App Manager](https://github.com/il90il90/israel-app-manager), which lists all of my apps.

## How a release gets here

The source code lives in a private repository. A signed APK is pushed to the `release-inbox` branch together with a `release.json`; the *Publish release* workflow checks that it is signed with the key whose fingerprint is in [`signing-cert.sha256`](signing-cert.sha256) and turns it into a tagged release. The links above always point at the newest one.

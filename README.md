# Fusilli Space Program — desktop app

A rocket game with a hand-written orbital-mechanics sim. Play it in the browser at **[fusillispaceprogram.com](https://fusillispaceprogram.com)**, or download the desktop app from the **[latest release](https://github.com/evertdespiegeleer/fusilli-space-program-public/releases/latest)**:

- **macOS:** the `.dmg` (one build for Apple silicon and Intel)
- **Windows:** the `-setup.exe`
- **Linux:** the `.AppImage`, or the `.deb`

The app is the live game in a window of its own, with your save kept in a file on your computer instead of in a browser that is free to throw it away. Once installed it offers each new version on its main menu.

The builds are not signed with an Apple or Microsoft certificate yet. On macOS, the first time, right-click the app and choose **Open**; if it says the app is damaged, run `xattr -dr com.apple.quarantine "/Applications/Fusilli Space Program.app"`. On Windows, choose **More info → Run anyway**.

This repository holds only the releases and the workflow that builds them; the source is private.

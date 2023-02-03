# Desktop app for Google Chat

[![release-linux](https://github.com/meysq/google-chat/actions/workflows/release-linux.yml/badge.svg)](https://github.com/meysq/google-chat/actions/workflows/release-linux.yml)
[![release-mac](https://github.com/meysq/google-chat/actions/workflows/release-mac.yml/badge.svg)](https://github.com/meysq/google-chat/actions/workflows/release-mac.yml)
[![release-windows](https://github.com/meysq/google-chat/actions/workflows/release-windows.yml/badge.svg)](https://github.com/meysq/google-chat/actions/workflows/release-windows.yml)

An unofficial desktop app for [Google Chat](http://chat.google.com) built with [Electron](https://www.electronjs.org).
Based on work by ankurk91. (Currently just a direct fork, but will be working on upkeep shortly.)

### Supported Platforms

The app should work on all x64 and Apple arm64 platforms, but due to lack of time; we test on most popular only.

| OS/Platform         |    Version    |
|:--------------------|:-------------:|
| Ubuntu GNOME        |    20, 22     |
| Linux Mint Cinnamon |      21       |
| MacOS               | 10.15, 11, 12 |
| Windows             |   7, 10, 11   |

### Major features

* System tray
    - Unread message indicator
    - Offline indicator (no internet or not logged-in)
    - Close the app to tray when you close the app window
* Desktop notifications
    - Clicking on notification bring the app to focus and open the specific person chat/room
* Unread message counter in dock
* Auto start the app when you log in to your machine (configurable)
* Auto check for updates on startup and notify user if any (configurable)
* Auto check for internet on startup and keep retrying to connect every 60 seconds if offline
* Open external links in your OS default web browser
* Preserve window position and size
* Prevent multiple chat app instances from running
* CTRL+F shortcut to search

### Acknowledgements

* [@robyf](https://github.com/robyf/google-chat-linux) for the initial work
* [@squalou](https://github.com/squalou/google-chat-linux) for enhancements
* All past [contributors](https://github.com/ankurk91/google-chat-electron/graphs/contributors)

## Disclaimer

This desktop app is just a wrapper which starts a chromium instance locally and runs the actual web-app in it. All
rights to the [Google Chat](https://chat.google.com/) product is reserved by
[Google Inc.](https://en.wikipedia.org/wiki/Google)
This desktop client has no way to access your data.

## License

[GNU GPLv3](LICENSE.txt) License

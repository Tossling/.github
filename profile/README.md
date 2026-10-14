<p align="center">
  <img src="https://raw.githubusercontent.com/Tossling/tossling-desktop/main/docs/images/icon.png" width="112" alt="Tossling">
</p>

<p align="center">
  One end-to-end encrypted clipboard for your computers and phones, through your own server.<br>
  Copy on one device and paste on another a second later. Text, images and files up to 500 MB go the same way.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Tossling/tossling-desktop/main/docs/images/mac-menu.png" width="360" alt="The Tossling menu on a Mac">
  &nbsp;
  <img src="https://raw.githubusercontent.com/Tossling/tossling-mobile/main/docs/images/android-home.png" width="190" alt="Tossling on Android">
</p>

| Repository | What is there |
|---|---|
| [**tossling-desktop**](https://github.com/Tossling/tossling-desktop) | Apps for macOS, Windows and Linux: menu bar or tray, hotkey, file manager menus and the `tossling` command. |
| [**tossling-mobile**](https://github.com/Tossling/tossling-mobile) | The Android and iOS apps with the room, history and notifications from your projects. Android builds are on GitHub Releases, iOS is coming to the App Store. |
| [**tossling-server**](https://github.com/Tossling/tossling-server) | The server in one Docker container (`ghcr.io/tossling/tossling-server`), with a setup page and a web panel. |

On a Mac install it with `brew install --cask tossling/tap/tossling`. Downloads for every platform are on
[monoroh.com/tossling](https://monoroh.com/tossling). Everything is encrypted on the devices (AES-256-GCM, a separate
X25519 key per device), and the server only relays ciphertext. Open source under GPL-3.0.

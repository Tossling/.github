<p align="center">
  <img src="https://raw.githubusercontent.com/Tossling/tossling-desktop/main/docs/images/icon.png" width="112" alt="Tossling">
</p>

<p align="center">
  One end-to-end encrypted clipboard for your Macs and Android phone, through your own server.<br>
  Copy on one device, paste on another a second later: text, images and files up to 500 MB.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Tossling/tossling-desktop/main/docs/images/mac-menu.png" width="360" alt="The Tossling menu on a Mac">
  &nbsp;
  <img src="https://raw.githubusercontent.com/Tossling/tossling-mobile/main/docs/images/android-home.png" width="190" alt="Tossling on Android">
</p>

| | |
|---|---|
| [**tossling-desktop**](https://github.com/Tossling/tossling-desktop) | The Mac app: menu bar, hotkey, Finder extension and the `tossling` command. Windows and Linux in progress. |
| [**tossling-mobile**](https://github.com/Tossling/tossling-mobile) | The Android app: the room, history, a widget and notifications from your projects. |
| [**tossling-server**](https://github.com/Tossling/tossling-server) | The server in one Docker container (`ghcr.io/tossling/tossling-server`), with a setup page and a web panel. |

Get it: `brew install --cask tossling/tap/tossling`, or the downloads on [monoroh.com/tossling](https://monoroh.com/tossling).
Everything is encrypted on the devices (AES-256-GCM, a separate X25519 key per device); the server only relays ciphertext. Open source under GPL-3.0.

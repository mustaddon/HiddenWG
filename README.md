# HiddenWG

**HiddenWG** is a fork of [WireGuard](https://www.wireguard.com/) enhanced with **built-in protocol obfuscation**. 

It retains the speed, simplicity, and state-of-the-art cryptography of the original WireGuard protocol while masking VPN traffic to bypass Deep Packet Inspection (DPI) and network restrictions.

> [!IMPORTANT]
> HiddenWG modifies the underlying wire protocol for obfuscation purposes. As a result, **it is not compatible with standard WireGuard clients or servers**—both ends of the tunnel must run HiddenWG.

---

## ✨ Key Features

- **Protocol Obfuscation:** Masks WireGuard packet headers and handshakes to prevent automated traffic detection and blocking.
- **Native Performance:** Built directly on top of the official WireGuard kernel modules and clients.
- **Drop-in Configuration:** Uses the exact same configuration format, keys, and routing concepts (`Cryptokey Routing`) as standard WireGuard.
- **Cross-Platform:** Available for Linux servers/clients, Windows, and Android.

---

## 🚀 Installation

### Linux (Client & Server)
Use the automated scripts from the [hiddenwg-linux-compat](https://github.com/mustaddon/hiddenwg-linux-compat/#driver-installation-script) repository.

### Windows
Download the latest installer from the [Windows Releases](https://github.com/mustaddon/hiddenwg-windows/releases/latest/) page.

### Android
Download and install the latest `.apk` directly from the [Android Releases](https://github.com/mustaddon/hiddenwg-android/releases/latest/) page.

---

## 📄 Credits & License
Based on [WireGuard](https://www.wireguard.com/) by Jason A. Donenfeld. Released under the respective open-source licenses of the upstream WireGuard repositories (GPLv2 / MIT / Apache 2.0).

<p align="center">
  <img src="./assets/logo.svg" alt="OpenSelfHosting" width="112" height="112" />
</p>

<h1 align="center">OpenSelfHosting</h1>

<p align="center">
  <strong>Your tools. Your server. Your data.</strong><br />
  <em dir="rtl">أدواتك. خادمك. بياناتك.</em>
</p>

<p align="center">
  We build open-source, privacy-first software you host yourself —<br />
  end-to-end encryption, no middlemen, and <strong>you hold the keys</strong>.
</p>

<p align="center">
  <img src="./assets/hero-stack.svg" alt="Self-hosted vault, chat, and media stack" width="420" />
</p>

<p align="center">
  <a href="https://openselfhosting.com"><img src="https://img.shields.io/badge/Website-openselfhosting.com-0F5C4C?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://openkey.openselfhosting.com"><img src="https://img.shields.io/badge/Try-OpenKey-1A7A64?style=for-the-badge&logo=keycdn&logoColor=white" alt="OpenKey" /></a>
  <a href="https://github.com/OpenSelfHosting"><img src="https://img.shields.io/badge/License-MIT-2F2A26?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="MIT" /></a>
</p>

---

## Why we exist

<p align="center">
  <img src="./assets/cover-welcome.svg" alt="Welcome to OpenSelfHosting" width="560" />
</p>

Cloud convenience often means surrendering control. **OpenSelfHosting** builds tools where cryptography happens on your devices first, servers store opaque ciphertext, and deployment stays under your roof — home lab, VPS, or LAN.

Self-hosting is not a hobbyist luxury. It is control.

## Principles

<p align="center">
  <img src="./assets/icon-shield.svg" alt="" width="56" height="56" />
  &nbsp;&nbsp;
  <img src="./assets/icon-server.svg" alt="" width="56" height="56" />
  &nbsp;&nbsp;
  <img src="./assets/icon-code.svg" alt="" width="56" height="56" />
</p>

| | Principle | Meaning |
|---|---|---|
| <img src="./assets/icon-shield.svg" width="36" height="36" alt="Keys" /> | **You hold the keys** | Encryption on-device first. The server sees ciphertext only — we cannot read your data even if we wanted to. |
| <img src="./assets/icon-server.svg" width="36" height="36" alt="Server" /> | **Run it where you want** | Docker at home, on a VPS, or on a LAN. No vendor lock-in. No mandatory subscription to reach your own data. |
| <img src="./assets/icon-code.svg" width="36" height="36" alt="Code" /> | **Open source** | Code you can audit. Review, fork, and contribute — transparency instead of blind trust. |

## Products

<p align="center">
  <img src="./assets/cover-openkey.svg" alt="OpenKey zero-knowledge sync" width="560" />
</p>

| | Product | Status | What it is |
|---|---|---|---|
| <img src="./assets/icon-key.svg" width="40" height="40" alt="OpenKey" /> | **[OpenKey](https://openkey.openselfhosting.com)** | Live | Zero-knowledge password manager. Master password never leaves the device; the server stores ciphertext only. |
| <img src="./assets/icon-chat.svg" width="40" height="40" alt="OpenChat" /> | **OpenChat** | In progress | Self-hosted chat with E2EE message bodies. Your server, your keys, your conversations. |
| <img src="./assets/icon-clipboard.svg" width="40" height="40" alt="OpenClipBoard" /> | **OpenClipBoard** | Soon | Clipboard sync across your devices through a server you own. |
| <img src="./assets/icon-gallery.svg" width="40" height="40" alt="OpenGalary" /> | **OpenGalary** | Soon | Private photo gallery on your own stack — memories stay with you. |

### OpenKey stack

<p align="center">
  <img src="./assets/cover-selfhost.svg" alt="Self-hosting architecture" width="560" />
</p>

| Package | Role |
|---|---|
| Flutter app | Android, iOS, desktop clients |
| FastAPI server | Zero-knowledge sync API + PostgreSQL |
| Browser extension | Chrome / Firefox (MV3) |
| CLI | Secrets, password generation, sync |
| Docs | Product site & guides (multi-locale) |

## Quick links

<p align="center">
  <a href="https://openselfhosting.com">
    <img src="./assets/about.svg" alt="About OpenSelfHosting" width="360" />
  </a>
</p>

- Website: [openselfhosting.com](https://openselfhosting.com)
- OpenKey: [openkey.openselfhosting.com](https://openkey.openselfhosting.com)
- Organization: [github.com/OpenSelfHosting](https://github.com/OpenSelfHosting)

## Contributing

Contributions are welcome — code, docs, translations, and security reviews.

1. Open an issue to discuss larger changes.
2. Fork the relevant repository and open a pull request.
3. Prefer clear commits and a short description of *why* the change exists.

For vulnerability reports, use each product’s `SECURITY.md` when available. Do not open public issues for sensitive security findings.

## License

Unless otherwise noted, projects under this organization are released under the **MIT License**.

---

<p align="center">
  <img src="./assets/logo.svg" alt="" width="48" height="48" />
</p>

<p align="center">
  Built for people who want privacy without giving up usability.<br />
  <a href="https://openselfhosting.com">openselfhosting.com</a>
</p>

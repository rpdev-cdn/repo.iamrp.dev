---
title: "Firefox Privacy Add-on Portal"
description: "Self-hosted Mozilla Firefox WebExtension portal distributing DNS Forge with automated update manifests and SHA-256 integrity verification."
---

# Firefox Privacy Add-on Portal (`firefox.repo.iamrp.dev`)

The **RPDev Firefox Add-on Portal** serves signed WebExtension packages directly to Firefox desktop and mobile browsers, independent of third-party store approvals.

- **Portal URL**: **[`https://firefox.repo.iamrp.dev/`](https://firefox.repo.iamrp.dev/)**
- **Update Manifest**: [`https://firefox.repo.iamrp.dev/updates.json`](https://firefox.repo.iamrp.dev/updates.json)
- **Target Platform**: Mozilla Firefox (Gecko Runtime, Manifest V3)

---

## 📥 Direct Installation

1. Visit **[`https://firefox.repo.iamrp.dev/`](https://firefox.repo.iamrp.dev/)** in Firefox.
2. Click the install button or download [`nextdns-firefox-addon-1.0.0.xpi`](https://firefox.repo.iamrp.dev/addons/nextdns-firefox-addon-1.0.0.xpi).
3. Confirm the browser permission prompt to activate DNS Forge.

---

## 🔒 Cryptographic Verification

| Attribute | Specification |
| :--- | :--- |
| **Extension ID** | `dns-forge@rpdevs.org` |
| **Version** | `1.0.0` |
| **Package File** | `nextdns-firefox-addon-1.0.0.xpi` |
| **SHA-256 Checksum** | `461cf346e7032af83599b311d6e9b60a43b8bdb116b32e068b9408b7010f0ee4` |
| **Update Endpoint** | `https://firefox.repo.iamrp.dev/updates.json` |

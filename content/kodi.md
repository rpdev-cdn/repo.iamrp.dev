---
title: "Kodi Add-on Repository"
description: "Sovereign Kodi add-on distribution repository hosting streaming resolvers, metadata scrapers, and service add-ons for Kodi Omega and Piers."
---

# Kodi Add-on Repository (`kodi.repo.iamrp.dev`)

The **RPDev Kodi Add-on Repository** provides a sovereign distribution point compatible with the native Kodi File Manager, Add-on Manager, and remote dependency resolver.

- **Primary Repository URL**: **[`https://kodi.repo.iamrp.dev/`](https://kodi.repo.iamrp.dev/)**
- **Repository Zip**: [`repository.rpdevs-1.0.0.zip`](https://kodi.repo.iamrp.dev/repository.rpdevs-1.0.0.zip)
- **Repository Manifest**: [`addons.xml`](https://kodi.repo.iamrp.dev/addons.xml)
- **Manifest MD5 Checksum**: [`addons.xml.md5`](https://kodi.repo.iamrp.dev/addons.xml.md5)

---

## 🛠️ Installation Instructions

### Step 1: Add File Manager Source
1. Open Kodi and navigate to **Settings (Gear Icon)** → **File manager**.
2. Click **Add source**.
3. In the `<None>` text field, enter exactly:
   ```
   https://kodi.repo.iamrp.dev/
   ```
4. Enter the media source name: `RPDev Repo` and click **OK**.

### Step 2: Install Repository from Zip
1. Return to the Kodi Home Screen and select **Add-ons**.
2. Click the open box icon (**Add-on browser**) in the upper-left corner.
3. Select **Install from zip file**.
4. If prompted to allow unknown sources, enable the toggle in Settings.
5. Select `RPDev Repo` → choose `repository.rpdevs-1.0.0.zip`.
6. Wait for the *RPDev Repository Add-on installed* notification.

---

## 📦 Hosted First-Party Add-ons

| Add-on ID | Name | Version | Description |
| :--- | :--- | :---: | :--- |
| `script.service.megacloud` | MegaCloud Debrid Service | `1.0.0` | High-throughput multi-provider debrid orchestration daemon |
| `script.service.flaresolverr` | FlareSolverr Helper | `1.0.0` | Cloudflare clearance solver bridge for scraper engines |
| `metadata.anime.otaku.python` | Otaku Metadata Engine | `1.0.0` | Python 3 metadata and art scraper engine for anime media |

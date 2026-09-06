---
title: "OpenWrt Package Feed"
description: "Dual-target OpenWrt package repository supporting legacy OPKG (Packages.gz) and modern Alpine APK v3 (APKINDEX.tar.gz) feeds."
---

# OpenWrt Custom Package Feed (`openwrt.repo.iamrp.dev`)

The **RPDev OpenWrt Package Feed** distributes kernel modules, LuCI management apps, and networking daemons built for high-performance edge routers.

- **Primary Repository URL**: **[`https://openwrt.repo.iamrp.dev/`](https://openwrt.repo.iamrp.dev/)**
- **Architecture**: `packages/all/` (Architecture-independent LuCI apps & scripts)
- **Target OS Support**: OpenWrt 21.02, 22.03, 23.05 (OPKG), and 24.10+ / 26+ (APK v3)

---

## 🚀 Feed Configuration

### OPKG (OpenWrt 23.05 and earlier)
Add the feed URL to `/etc/opkg/customfeeds.conf`:
```bash
echo "src/gz rpdev_all https://openwrt.repo.iamrp.dev/packages/all" >> /etc/opkg/customfeeds.conf
opkg update
```

Install available packages:
```bash
opkg install luci-app-nfs
```

### Alpine APK v3 (OpenWrt 24.10+ / Master)
Add the repository to `/etc/apk/repositories.d/rpdev.list`:
```bash
echo "https://openwrt.repo.iamrp.dev/packages/all" >> /etc/apk/repositories.d/rpdev.list
apk update
```

Install available packages:
```bash
apk add luci-app-nfs
```

---

## 📦 Hosted Packages

| Package Name | Format | Version | Architecture | Description |
| :--- | :---: | :---: | :---: | :--- |
| **`luci-app-nfs`** | `.ipk` / `.apk` | `1.2.3-1` | `all` | OpenWrt LuCI Web UI and UCI configuration bridge for Linux kernel `nfsd` |

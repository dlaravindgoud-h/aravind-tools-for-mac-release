# Aravind Tools for Mac — Evaluation Release

Native encrypted vault application for macOS built with SwiftUI and SwiftData, utilizing hardware-accelerated AES-256-GCM symmetric encryption.

---

## ⬇️ Download

| Release | Version | Build | Architecture | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **Latest** | `1.7.0` | `8` | Apple Silicon (`arm64`) | [**Download Aravind-Tools-Mac-v1.7.0.zip**](https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip) |

> **Direct Download Link**:  
> 👉 [https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip](https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip)

---

## 🚀 Installation & First-Time Launch

Because this application is distributed directly for evaluation (outside the Mac App Store) and is ad-hoc signed, macOS Gatekeeper attaches a quarantine attribute upon downloading.

### 1. Install
- Download and unzip `Aravind-Tools-Mac-v1.7.0.zip`.
- Drag **Aravind Tools.app** into your **`/Applications`** folder.

### 2. First-Time Launch (Choose Option A or B)

#### Option A — Terminal (Recommended, 1-Second Fix)
Open the **Terminal** app and run:
```bash
xattr -cr /Applications/"Aravind Tools.app"
```
You can now open Aravind Tools normally from Spotlight, Launchpad, or Applications.

#### Option B — System Settings GUI
1. In Finder, navigate to `/Applications`.
2. **Right-click** (or Control-click) on **Aravind Tools.app** and select **Open**.
3. In the confirmation dialog, click **Open**.
4. *(If macOS blocks launch)*: Open **System Settings → Privacy & Security**, scroll down to the Security section, and click **"Open Anyway"**.

---

## 🔒 Security & Evaluation Notes

- **Zero-Knowledge Encryption**: Master passphrases are never transmitted over the internet or stored unencrypted. All cryptographic operations are processed strictly locally via Apple CryptoKit.
- **Master Passphrase Responsibility**: There is no remote account recovery or "forgot password" option. Please memorize or safely store your master passphrase.
- **Evaluation Period**: This evaluation build is active through **November 30, 2026**.
- **Backup & Restore**: Users maintain complete ownership of their data. Please use **Settings → Backup & Restore** to generate regular encrypted `.vaultbackup` archives.
- **Hardware Requirement**: macOS 14.0+ running on Apple Silicon (M1, M2, M3, M4 Macs).

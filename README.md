# Aravind Tools for Mac — Evaluation Releases

Native encrypted vault application for macOS built with SwiftUI and SwiftData, utilizing hardware-accelerated AES-256-GCM symmetric encryption.

---

## ⬇️ Download

| Release | Version | Build | Architecture | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **Latest** | `1.7.0` | `8` | Apple Silicon (`arm64`) | [**Download Aravind-Tools-Mac-v1.7.0.zip**](https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip) |

> **Direct Download Link**:  
> 👉 [https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip](https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip)

---

## 🚀 First-Time Installation & Launch

Because this application is distributed directly for personal evaluation (outside the Mac App Store) and is ad-hoc signed, macOS Gatekeeper attaches an automatic quarantine attribute upon downloading.

### 1. Install
- Download and unzip `Aravind-Tools-Mac-v1.7.0.zip`.
- Drag **Aravind Tools.app** into your **`/Applications`** folder.

### 2. First-Time Launch (Choose Option A or B)

#### Option A — Terminal (Recommended, 1-Second Fix)
Open the **Terminal** app and paste this command:
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

## 📋 Ready-to-Send Message Template

Copy and paste the template below when sharing this evaluation build with friends or relatives via WhatsApp, Telegram, Email, or Slack:

```text
Hey! Here is the evaluation build of Aravind Tools for Mac (v1.7.0).

⬇️ Download Link:
https://github.com/dlaravindgoud-h/aravind-tools-for-mac-release/raw/main/Aravind-Tools-Mac-v1.7.0.zip

📦 Quick Setup:
1. Download and unzip the file, then drag "Aravind Tools.app" into your Applications folder.
2. Since this is an ad-hoc evaluation build, macOS might show a warning that "the developer cannot be verified".
3. To open it the first time:
   • Open Terminal and run:
     xattr -cr /Applications/"Aravind Tools.app"
   (Or right-click the app in Applications, choose "Open", and click "Open Anyway" in System Settings > Privacy & Security).

🔐 Important Notes:
• All your records are encrypted locally on your Mac using hardware-accelerated AES-256-GCM.
• Remember your Master Passphrase! There is no "forgot password" reset because no data ever leaves your Mac.
• This build is valid for evaluation through November 30, 2026.
• You can export encrypted backups anytime under Settings > Backup & Restore.

Let me know your feedback!
```

---

## 🔒 Security & Evaluation Notes

- **Zero-Knowledge Architecture**: Master passphrases are never transmitted over the internet or stored unencrypted. All cryptographic operations are processed locally via Apple CryptoKit.
- **Evaluation Period**: This evaluation build is configured to operate through **November 30, 2026**.
- **Data Responsibility**: You maintain complete ownership and responsibility for your local data. Please use **Settings → Backup & Restore** to create regular encrypted `.vaultbackup` archives.
- **Hardware Requirement**: macOS 14.0+ running on Apple Silicon (M1, M2, M3, M4 Macs).

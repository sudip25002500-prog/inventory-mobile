# 📱 Inventory OS - Android APK Project

This folder contains the complete native Android project that wraps your Inventory Management System into a standalone Android APK.

---

## ⚡ How to Build the APK in 2 Minutes (Using Free GitHub Actions)

You do **not** need to install heavy Android SDKs or tools on your computer. GitHub will compile the APK in the cloud for you automatically:

### Step 1: Create a new repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Name the repository (for example: `inventory-mobile`).
3. Leave it Public or Private, and click **"Create repository"**.

### Step 2: Push this folder to your repository
Open PowerShell in this folder (`android_project`) and run:

```bash
git init
git add .
git commit -m "Initial Android APK commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/inventory-mobile.git
git push -u origin main
```

*(Replace `YOUR_USERNAME/inventory-mobile` with your actual GitHub repository URL).*

---

### Step 3: Download the APK
1. As soon as you push, open your repository on GitHub.
2. Click the **"Actions"** tab at the top.
3. You will see a workflow running named **"Build Android APK"**.
4. Once completed (~2 minutes), click on the workflow run.
5. Under **Artifacts** at the bottom of the page, click **`InventoryOS-Debug-APK`** to download your ready-to-install `.apk` file!
6. Transfer the `.apk` file to your Android phone (or download it directly from your phone's browser) and tap to install.

---

## 📲 App Features on Your Phone

- **100% Standalone Offline Storage:** Works anywhere, anytime, without needing your PC to be running.
- **Pre-loaded Catalog:** Pre-seeded with your spreadsheet data (Raj Sales, products, categories, stock counts).
- **Automated Stock Deduction:** Logging sales automatically decreases stock; logging purchases increases stock.
- **Server Sync:** Want to connect to your PC's SQLite database when on Wi-Fi? Tap the Wi-Fi icon in the top header and enter your PC's IP (`http://20.101.30.189:8000`).

## Windows Users: WSL 2 Setup

# Step 1: Check Windows Version

For **WSL 2**, you need:

- **Windows 10 (version 2004 or later)**, or  
- **Windows 11**

If you are using **Windows 11 → it will work directly** ✅

---

# 🧑‍💻 Step 2: Open PowerShell in Admin Mode

1. Open the **Start Menu**
2. Type **PowerShell**
3. Right-click on it → **Run as Administrator**

⚠️ This step is **very important**

---

# 🐧 Step 3: Install WSL 2

Paste the following command into **PowerShell**:

```bash
wsl --install
```
## This command will automatically:

Enable WSL

Install WSL 2

Install the default Linux distribution

⏳ This may take some time

## 🔁 Step 4: Restart Your System

After installation:
Step 5: Install Ubuntu 22.04 (Explicitly)

After restarting, open PowerShell (Admin) again and run:
```
wsl --install -d Ubuntu-22.04
```
This will specifically install Ubuntu 22.04

Step 6: Set WSL 2 as Default Version
```
wsl --set-default-version 2
```
Restart your PC (required)
Step 7: Ubuntu First-Time Setup

When Ubuntu opens for the first time:

It will ask for a username → enter anything (e.g. bisma)

Set a password (it will not be visible while typing)

✅ Done!

Step 8: Verify Installation

Run this command inside the Ubuntu terminal:
```
wsl --list --verbose
```
Expected output:
NAME            STATE           VERSION
Ubuntu-22.04    Running         2


🎉 If VERSION = 2, everything is set up correctly!

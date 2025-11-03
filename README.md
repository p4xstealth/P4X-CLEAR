# P4X CLEAR

<div align="center">

**A powerful cleaning utility for FiveM installations**

Keep your FiveM client optimized, free up disk space, and resolve common issues with ease.

[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=flat&logo=windows)](https://www.microsoft.com/windows)
[![.NET](https://img.shields.io/badge/.NET%20Framework-4.8-512BD4?style=flat&logo=dotnet)](https://dotnet.microsoft.com/download)

</div>

---

## 📥 Download

1. Go to [Releases](https://github.com/p4xstealth/P4X-CLEAR/releases)
2. Download `P4XClear.exe`
3. Run the executable

**That's it!** No installation required.

---

## ⚙️ Requirements

- Windows 10 or Windows 11
- [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48) (usually pre-installed on Windows)
- FiveM installed on your system

---

## 🚀 How to Use

### Step 1: Close FiveM
**Important:** Make sure FiveM is completely closed before running any cleaning operations.

### Step 2: Run P4X CLEAR
Double-click `P4XClear.exe` to start the application.

### Step 3: Choose an Option
You'll see a menu with the following options:

```
  [1] Clean Cache
  [2] Clean Logs and Crashes
  [3] Clean Digital Entitlements
  [4] Clear file keysBinds
  [5] Clean Temporary Files
  [6] Exit
```

Type the number of your choice and press `Enter`.

### Step 4: Wait for Completion
Watch the progress bars as the cleaning operation completes.

### Step 5: Return to Menu
Press any key to return to the menu or exit.

---

## 📋 What Each Option Does

### [1] Clean Cache
**What it does:** Removes cached game resources, textures, and models

**Use when:**
- Textures are not loading correctly
- Game files appear corrupted
- You want to free up disk space
- After installing new resources or mods

**Location:** `%LocalAppData%\FiveM\FiveM.app\data`

---

### [2] Clean Logs and Crashes
**What it does:** Deletes log files and crash dumps

**Use when:**
- You want to free up disk space
- You want to remove old crash reports
- Log folder is taking up too much space

**Locations:** 
- Logs: `%LocalAppData%\FiveM\FiveM.app\logs`
- Crashes: `%LocalAppData%\FiveM\FiveM.app\crashes`

---

### [3] Clean Digital Entitlements
**What it does:** Clears digital license data

**Use when:**
- FiveM shows license verification errors
- You're experiencing entitlement errors
- You need to reset your digital license
- After changing your FiveM account

**⚠️ Warning:** This will require you to re-authenticate on next launch.

**Location:** `%LocalAppData%\DigitalEntitlements`

---

### [4] Clear file keysBinds
**What it does:** Deletes the configuration file (`fivem.cfg`) to reset all settings

**Use when:**
- Key bindings are not working correctly
- You want to reset all settings to default
- You're experiencing configuration issues

**⚠️ Warning:** This will reset ALL your key bindings and settings to default!

**Location:** `%AppData%\CitizenFX\fivem.cfg`

---

### [5] Clean Temporary Files
**What it does:** Cleans temporary files from multiple system locations

**Cleans:**
- User temporary files (`%temp%`)
- Windows temporary files (`C:\Windows\Temp`)
- Prefetch cache files (`C:\Windows\Prefetch`)

**Use when:**
- You want to free up significant disk space
- Temporary folders are taking up too much space
- You want to improve system performance
- As part of regular system maintenance

**💡 Tip:** This is safe to run regularly and can free up a lot of space!

---

## 💡 Tips

- ⚠️ **Always close FiveM** before running any cleaning operations
- 🔄 Run option [5] periodically to maintain disk space
- 💾 Back up important configurations before using option [4]
- 📊 The tool shows how much space was freed after cleaning
- 🛡️ The tool automatically checks if FiveM is running
- ✅ Some files may fail to delete if they're in use (this is normal and safe)

---

## ❓ Frequently Asked Questions

### Do I need to close FiveM?
**Yes!** Always close FiveM completely before running any cleaning operations. The tool will warn you if FiveM is running.

### Is it safe to use?
Yes, P4X CLEAR is safe to use. It only removes files that are safe to delete. However, always ensure FiveM is closed before running.

### Will I lose my settings?
- **Option [4]** will reset all key bindings and settings to default
- Other options don't affect your settings

### How much space can I free up?
It depends on how long you've been using FiveM:
- Cache cleaning: Usually 100MB - 2GB
- Logs and crashes: Usually 50MB - 500MB
- Temporary files: Can free up several GBs

### Can I run multiple options at once?
No, run one option at a time for best results.

### What if some files fail to delete?
Some files may fail to delete if they're currently in use by other applications. This is normal and safe. The tool will report how many items failed.

---

## 🆘 Troubleshooting

### "FiveM is currently running"
**Solution:** Close FiveM completely and try again.

### "The default installation path does not exist"
**Solution:** The tool will ask you to enter your FiveM installation path manually.

### "Some files failed to delete"
**Solution:** This is normal. Some files may be in use by other programs. The tool will still clean what it can.

### Program won't start
**Solution:** Make sure you have .NET Framework 4.8 installed. Download it [here](https://dotnet.microsoft.com/download/dotnet-framework/net48).

---

## 📚 More Information

- **[FEATURES.md](FEATURES.md)** - Detailed documentation of all features
- **[ABOUT.md](ABOUT.md)** - More information about P4X CLEAR

---

## 🌐 Support

- **Discord**: [https://dsc.gg/p4xstealth](https://dsc.gg/p4xstealth)
- **GitHub**: [https://github.com/devns](https://github.com/devns)

---

## ⚠️ Disclaimer

This tool is provided as-is. Use at your own risk. Always ensure FiveM is closed before running cleaning operations. Some operations may require re-authentication or reset settings.

---

<div align="center">

**P4X CLEAR** - Keeping your FiveM installation clean, optimized, and trouble-free.

</div>

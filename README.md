# P4X CLEAR

<div align="center">

![P4X CLEAR](https://img.shields.io/badge/P4X-CLEAR-purple?style=for-the-badge)
![.NET](https://img.shields.io/badge/.NET%20Framework-4.8-512BD4?style=for-the-badge&logo=dotnet)
![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-P4X-purple?style=for-the-badge)

**A powerful and comprehensive cleaning utility for FiveM installations**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Documentation](#-documentation) • [Support](#-support)

</div>

---

## 📖 About

**P4X CLEAR** is a specialized Windows console application designed to help FiveM users maintain a clean and optimized installation. It removes unnecessary files, cached data, logs, and temporary files that can accumulate over time and cause performance issues.

### Why P4X CLEAR?

- 🚀 **Free Up Disk Space** - Remove gigabytes of unnecessary files
- ⚡ **Improve Performance** - Clean cache and temporary files
- 🔧 **Fix Issues** - Resolve cache corruption and authentication problems
- 🛡️ **Safe & Reliable** - Automatic process checking and error handling
- 📊 **Progress Tracking** - Real-time visual progress indicators

---

## ✨ Features

### 🧹 Cache Cleaning
Remove cached game resources, textures, and models to free up space and resolve cache-related issues.

### 📝 Logs & Crashes Cleanup
Eliminate old log files and crash dumps that can take up significant disk space.

### 🔒 Digital Entitlements Management
Clear digital entitlement data to resolve authentication and license verification issues.

### ⌨️ Key Bindings Reset
Remove the configuration file (`fivem.cfg`) to reset all settings and key bindings to default values.

### ⏳ Temporary Files Cleanup
Comprehensive cleaning of system temporary files:
- User temporary files (`%temp%`)
- Windows temporary files (`C:\Windows\Temp`)
- Prefetch cache files (`C:\Windows\Prefetch`)

---

## 🛠️ Requirements

- **Operating System**: Windows 10 or Windows 11
- **.NET Framework**: [.NET Framework 4.8 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net48)
- **FiveM**: Installed FiveM client (must be closed during cleaning operations)

---

## 📥 Installation

### Option 1: Download Pre-built Executable

1. Go to the [Releases](https://github.com/p4xstealth/P4X-CLEAR/releases) page
2. Download the latest `P4XClear.exe`
3. Extract to a folder of your choice
4. Run `P4XClear.exe`

### Option 2: Build from Source

```bash
# Clone the repository
git clone https://github.com/p4xstealth/P4X-CLEAR.git
cd P4X-CLEAR

# Build using the provided script
BUILD.bat

# Or build manually in Visual Studio
# Open ClearFiveM.sln and build
```

---

## 🚀 Usage

### Quick Start

1. **Close FiveM** - Ensure FiveM is completely closed
2. **Launch P4X CLEAR** - Run `P4XClear.exe`
3. **Select Option** - Choose the cleaning option you need
4. **Wait for Completion** - Watch the progress bars
5. **Return to Menu** - Press any key to return or exit

### Menu Options

```
  [1] Clean Cache
  [2] Clean Logs and Crashes
  [3] Clean Digital Entitlements
  [4] Clear file keysBinds
  [5] Clean Temporary Files
  [6] Exit
```

### Detailed Usage

#### Option 1: Clean Cache
- Removes cached game resources
- Location: `%LocalAppData%\FiveM\FiveM.app\data`
- Use when: Experiencing texture loading issues or cache corruption

#### Option 2: Clean Logs and Crashes
- Cleans log files and crash dumps
- Locations: `logs/` and `crashes/` folders
- Use when: Wanting to free up disk space or remove old crash reports

#### Option 3: Clean Digital Entitlements
- Clears digital license data
- Location: `%LocalAppData%\DigitalEntitlements`
- Use when: Experiencing license verification errors
- ⚠️ **Warning**: Requires re-authentication on next launch

#### Option 4: Clear file keysBinds
- Removes `fivem.cfg` configuration file
- Location: `%AppData%\CitizenFX\fivem.cfg`
- Use when: Key bindings not working or want to reset settings
- ⚠️ **Warning**: Resets all key bindings and settings to default

#### Option 5: Clean Temporary Files
- Comprehensive system temp file cleanup
- Locations: `%temp%`, `C:\Windows\Temp`, `C:\Windows\Prefetch`
- Use when: Wanting to free up significant disk space
- 💡 **Tip**: Safe to run regularly for maintenance

---

## 📚 Documentation

For detailed information, check out:

- **[FEATURES.md](FEATURES.md)** - Complete documentation of all cleaning modes
- **[ABOUT.md](ABOUT.md)** - More information about P4X CLEAR
- **[GIT_GUIDE.md](GIT_GUIDE.md)** - Git setup and deployment guide

---

## 💡 Tips & Best Practices

- ⚠️ **Always close FiveM** before running any cleaning operations
- 🔄 Run option [5] periodically to maintain disk space
- 💾 Back up important configurations before using option [4]
- 📊 Check disk space before and after using option [5]
- 🛡️ The tool automatically checks if FiveM is running
- 🔒 Some files may fail to delete if in use (normal and safe)

---

## 🛠️ Building from Source

### Prerequisites

- Visual Studio 2019 or later (with .NET Framework 4.8 SDK)
- Or Visual Studio Build Tools

### Build Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/p4xstealth/P4X-CLEAR.git
   cd P4X-CLEAR
   ```

2. **Open Solution**
   - Open `ClearFiveM.sln` in Visual Studio

3. **Build**
   - Press `Ctrl+Shift+B` or use `Build > Build Solution`
   - Or use the provided script:
     ```bash
     BUILD.bat
     ```

4. **Run**
   - The executable will be in `bin\Release\P4XClear.exe`

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Copyright (c) 2025 P4X

See the [LICENSE](LICENSE.txt) file for more details.

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

Made with ❤️ by P4X

[⬆ Back to Top](#p4x-clear)

</div>

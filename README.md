# ✉️ OOUPSSmail ✉️

![Platform](https://img.shields.io/badge/platform-Windows-blue?logo=windows)
![Python](https://img.shields.io/badge/python-3.11+-yellow?logo=python&logoColor=white)
![PyQt6](https://img.shields.io/badge/GUI-PyQt6-%233377AA?logo=qt&logoColor=white)
![License](https://img.shields.io/github/license/OOUPSS/OOUPSSmail)
![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan%20Passed-brightgreen?logo=virustotal&logoColor=white)
![Downloads](https://img.shields.io/github/downloads/OOUPSS/OOUPSSmail/total?color=brightgreen)
![Release](https://img.shields.io/github/v/release/OOUPSS/OOUPSSmail?color=purple)


**OOUPSSmail** is a sleek, neon-themed desktop app for generating thousands of Gmail aliases in one click.  
Perfect for signups, filtering incoming emails, A/B testing, and keeping your primary inbox clean.

![UI Screenshot](https://github.com/OOUPSS/OOUPSSmail/blob/main/screenshot.png?raw=true)

---

## 🚀 Features

- ⚡ Generate up to **50,000** unique Gmail aliases
- 🟣 Supports dot (`.`) and plus (`+`) alias formats
- 💾 Save results to `.txt`
- 📋 One-click copy to clipboard
- 🖤 Neon cyberpunk UI (PyQt6)
- 🔐 100% local — no internet connection required

---

## 📥 Download

**[⬇️ Download OOUPSSmail for Windows (EXE)](https://github.com/OOUPSS/OOUPSSmail/releases/download/v1.0.1/OOUPSSmail.exe)**

> ⚠️ Only Gmail addresses with `.com` domain are supported (e.g. `yourname@gmail.com`)

---

## 📹 Video Guide

<p align="center">
  <a href="https://youtu.be/t4nBpjHrVzs?si=rfVNEpDQ-PL9UnNT">
    <img src="https://github.com/OOUPSS/OOUPSSmail/blob/main/ytic.png?raw=true" alt="YouTube Preview" width="640" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/t4nBpjHrVzs?si=rfVNEpDQ-PL9UnNT">
    <img src="https://github.com/OOUPSS/OOUPSSmail/blob/main/youtube.png?raw=true" alt="Watch on YouTube Button" width="220" />
  </a>
</p>

---

## 👤 Author

**OOUPSS**

- Discord: `oouuppss`

---

## 🛡️ Virus Scan

This executable was scanned using [VirusTotal](https://www.virustotal.com/) and received **4/72 detections**.

![VirusTotal Scan](https://github.com/OOUPSS/OOUPSSmail/blob/main/VirTot101.png?raw=true)

**SHA256:** `9088274874f1ee332860302d747e0dda31f682f624307c2fde973e60d7e9adfc`  
🔗 [View full scan on VirusTotal](https://www.virustotal.com/gui/file/9088274874f1ee332860302d747e0dda31f682f624307c2fde973e60d7e9adfc/detection)

**Detected by:** 4 out of 72 antivirus engines  
**Label:** `Trojan` *(generic match, usually a false positive)*

> ⚠️ **Why this happens:**  
> This is a **false positive** commonly seen with PyInstaller-packed `.exe` files.  
> Some antivirus engines flag it because:
> - It uses **PyInstaller**, which bundles all code and dependencies into a single `.exe`
> - The file is **not digitally signed**
> - It contains an **embedded icon and resources**, which resemble malware behavior
> - It matches a **YARA rule for PyInstaller**, which only detects packaging — not malicious behavior

This tool is 100% open-source and safe to use. You can review the full code in this repository.

## ⭐ Support

If you like the project, give it a ⭐ and share it with others — it helps the project grow!

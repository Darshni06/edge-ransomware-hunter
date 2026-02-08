# 🛡️ Edge Ransomware Hunter

**Real-time behavioral ransomware detection for Windows & Android**

[![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)](https://github.com/yourusername/edge-ransomware-hunter/releases)
[![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)](https://github.com/yourusername/edge-ransomware-hunter/releases)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📥 Download Latest Release

### Windows
[![Download Windows](https://img.shields.io/badge/Download-Windows_Executable-blue)](https://github.com/yourusername/edge-ransomware-hunter/releases/download/v1.0.0/EdgeRansomwareHunter-Windows.zip)
**Size:** 24.5 MB | **Version:** 1.0.0

### Android (APK)
*Coming Soon - Currently in testing*

## 🚀 Quick Start (Windows)

1. **Download** the Windows zip file
2. **Extract** to any folder
3. **Run** `EdgeRansomwareHunter.exe`
4. **Allow** if Windows Defender shows warning (click "More info" → "Run anyway")

**That's it!** Real-time protection starts immediately.

## ✨ Features

### 🔍 Real-time Detection
- Monitors file system for ransomware patterns
- Behavioral analysis (no signature updates needed)
- Detects mass encryption, suspicious extensions, rapid renames

### 🛡️ Multi-Platform
- **Windows**: Native executable with system tray icon
- **Android**: Mobile protection (Kivy-based UI)
- **Cross-platform core**: Same detection engine

### 📊 Smart Alerts
- Console notifications with detailed threat analysis
- Windows popup alerts for critical threats
- JSON logging for forensic analysis

### ⚡ Lightweight & Efficient
- No internet required (works offline)
- Low CPU/RAM usage (< 50MB)
- Configurable monitoring paths

## 🖥️ Windows Agent

```bash
# Run from source
cd platform_wrappers/windows
python windows_agent.py

# Or use the built executable
./dist/EdgeRansomwareHunter.exe
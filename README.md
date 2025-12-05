# 🛡️ KernelHunt Framework

> **Advanced Windows Driver 0-Day Hunter**
> By Shravan Kumar Sheri (SSK)

Automated discovery of 0-day vulnerabilities in Windows kernel drivers through systematic analysis of attack surfaces, exploitation primitives, and dangerous operations.

[![Language](https://img.shields.io/badge/Language-C%2B%2B%20%7C%20Python-blue)]()
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)]()
[![License](https://img.shields.io/badge/License-Research-green)]()
[![Version](https://img.shields.io/badge/Version-2.0.0-brightgreen)]()

---

## 🚀 Quick Start

```cmd
# Run the main Windows executable
kernelHuntFramework.exe
```
https://youtu.be/kRfpD0X-E3U

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Professional Console** | Beautiful interactive interface with color-coded output |
| 🔬 **Auto Decompilation** | Ghidra headless batch processing |
| 🎯 **IOCTL Extraction** | Maps complete attack surface with proper categorization |
| ⚠️ **Dangerous Functions** | Detects 40+ exploitable functions across 4 severity levels |
| ⚡ **Exploitation Primitives** | Detects arbitrary read/write, code execution, privilege escalation |
| 📊 **Security Scoring** | Automated risk assessment (0-100 scale) |
| 🎨 **HTML Reports** | Beautiful visual dashboards with compartmentalized data |
| 🔄 **Batch Analysis** | Analyze multiple drivers sequentially or in parallel |
| 🚀 **Parallel Processing** | Multi-CPU batch analysis - 8-16x faster than sequential |
| 📈 **Master Dashboard** | Aggregate view of all analyzed drivers by severity |
| 🔍 **Patch Diff Analyzer** | Compare driver versions to find 0-days (85-95% success) |
| 🖥️ **System-Wide Scanning** | Enumerate ALL Windows drivers (Microsoft + Third-Party) |
| 🎯 **Live IOCTL Fuzzing** | Real-time driver testing with automated input generation |
| 🔌 **Driver Loader** | Bulk load/unload drivers for testing - supports file lists & directories |

---

---

## 🎯 Example Output

### Security Report
```
============================================================
REPORT SUMMARY
============================================================
Security Score:      100/100 (CRITICAL)
Total IOCTLs:        142
Total Functions:     166
Dangerous Functions: 92
  - Critical:        1
  - High:            13
  - Medium:          69
============================================================
```


---

## 💾 Installation

### **Prerequisites:**
- **Windows 10** (required for main executable)
- **Visual Studio 2019+** (to compile C++)
- **Python 3.8+** (for analysis helper scripts)
- **Ghidra 11.0+** (for decompilation engine)
- **Configure paths (in code):**
   ```cpp
   // Edit rundriverDecompiler.cpp line 123-126:
   string baseDir = "C:\\YourPath\\kernelHuntFramework";
   string ghidraPath = "C:\\ghidra_11.0_PUBLIC";
   ```




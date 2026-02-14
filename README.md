# 🇵🇰 PAK SIM INFO CLI

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-1.0-red.svg)

A **Python CLI tool** to fetch **Pakistani SIM and CNIC information** in a colorful, hacker-style terminal interface.  
Supports **phone number (11 digits)** and **CNIC (13 digits)** queries.  

> Displays **all results** in a readable, colorful format with **banner, progress bar, and arrows**.

---

## 📋 Table of Contents

- [Features](#-features)  
- [Requirements](#-requirements)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Example Session](#-example-session)  
- [Notes](#-notes)  
- [Author](#-author)  
- [Disclaimer](#-disclaimer)

---

## 🌟 Features

- ✅ Phone Number Info (11 digits)  
- ✅ CNIC Info (13 digits)  
- ✅ Displays **all results**  
- ✅ **Progress bar loader** while fetching data  

---

-

## 📦 Requirements

- Python 3.8+  
- Install required modules:

```bash
pip install requests beautifulsoup4
```
• Works on Linux, macOS, Windows

## ⚡ Installation

### 1. Clone the repository:
```bash
git clone https://github.com/anubhavanonymous/pak-sim-info-cli.git
cd pak-sim-info-cli
```
### 2. Make the script executable (Linux/ macOS)
```bash
chmod +x pak_sim_info.py
```
### 3. Run the tool
```bash
python pak_sim_info.py
```
Or on Linux/macOS:
```bash
./pak_sim_info.py
```
## 🖥️ Usage
1. On startup, you'll see the PAK flag banner with author info.
2. Menu with options:
```bash
1. Phone number info (11 digits)
2. CNIC info (13 digits)
3. Exit
```
3. Enter your choice (1, 2, or 3).
4. Enter the number/CNIC with the correct format:
```bash
Phone Number: 11 digits starting with 0 (e.g., 03340122573).
• Automatically converts to 92 country code format.
CNIC: 13 digits (e.g., 4230199577600).
```
5. Results display like this;
```bash
Result #1
Mobile  : 923323312487
Name    : YASMIN
CNIC    : 4230199577600
Address : HOUSE NUMBER C-1 PLOT 1519-152 - KARACHI
```
## 🖱️ Example Session
```bash
┌────────────────────────────────────────────────────────┐
│      [PAK SIM INFO]                                     │
└────────────────────────────────────────────────────────┘

Author: Anubhav Kashyap | GitHub/Telegram: @anubhavanonymous

1. Phone number info (11 digits)
2. CNIC info (13 digits)
3. Exit

=> Choose an option: 1

=> Enter 11-digit phone number: 03340122573

Fetching data: |██████████████████| 100%

=== Results for 923340122573 (mobile) ===

Result #1
Mobile  : 923340122573
Name    : ALI
CNIC    : 4230199571234
Address : HOUSE NUMBER 5 STREET 8 KARACHI

All Data Exposed ! Jay Hind ♥️
```
## 🔧 Notes
• Only valid 11-digit numbers or 13-digit CNICs are accepted.

• Phone numbers starting with 0 are converted to 92 automatically.

• Exits automatically after displaying all results.
## 👨🏻‍💻 Author

💠 Anubhav Kashyap

=> GitHub : https://github.com/anubhavanonymous

=> Telegram: https://t.me/anubhavanonymous

## ⚠️ Disclaimer
This tool is for **educational purposes only**. Accessing or misusing personal data without permission may be illegal. Use responsibly.

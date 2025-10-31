# Compiled Masscan For Windows v1.3.9

A Windows build of **masscan v1.3.9-integration** (original project: https://github.com/robertdavidgraham/masscan).

**Build info**
- Version: `1.3.9-integration`  
- Compiled on: **Oct 31 2025 21:07:53**  
- Compiler: **Visual Studio (post-2013)**  
- OS: **Windows**  
- CPU: **x86 (32-bit)**

---

## Overview

This repository contains a Windows executable build of Masscan (v1.3.9-integration). Masscan is a fast port scanner similar to `nmap`, capable of scanning large networks quickly.

---

## Download

Download the executable directly:

- `masscan.exe` —  
  https://github.com/Muhammad-Hasan-BD/MasscanForWindows1.3.9/blob/main/masscan.exe

> **Tip:** Right-click → *Save link as...* to download the binary.

---

## Requirements

- Windows (32-bit build)  
- A packet capture driver such as **WinPcap** or compatible (required for raw packet I/O).

WinPcap:
- https://www.winpcap.org/

> If WinPcap is unavailable on your system, consider using Npcap (WinPcap-compatible). Check compatibility before installing.

---

## Installation

1. Install WinPcap (or a compatible packet driver such as Npcap in WinPcap-compatible mode).  
2. Place `masscan.exe` in a folder included in your `PATH` or run it directly from the folder where it resides.

---

## Usage

Open a command prompt and run:

```bash
masscan --help

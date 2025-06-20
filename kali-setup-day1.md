# 🐉 Kali Linux Setup – Day 1 Hands-On Lab Report

**Date:** June 20, 2025  
**Author:** Jackton Nyaga  
**Focus:** Installing and configuring Kali Linux in a VirtualBox environment for ethical hacking labs.

---

## 🎯 Summary

Today, I successfully installed Kali Linux on a VirtualBox VM and configured essential tools and terminal settings. This is my first step toward mastering ethical hacking and cybersecurity fundamentals through hands-on labs.

---

## 🛠️ Tools Used

- **VirtualBox 7.1.10**
- **Kali Linux ISO**
- **7-Zip** (for extracting)
- **Tilix Terminal Emulator**
- **Host System:** Windows 10

---

## 🧪 Steps Performed

1. Downloaded Kali Linux ISO from the official site
2. Installed VirtualBox and configured the VM:
   - OS type: Linux > Debian (64-bit)
   - Memory: 4 GB
   - Disk: 30 GB dynamically allocated
3. Mounted the ISO and installed Kali
4. Set up Bridged Networking for internet access
5. Ran system update and upgrade:
   ```bash
   sudo apt update && sudo apt upgrade

# 🛡️ Cyber Sentinel (All-in-One Defensive Edition)

Cyber Sentinel is a **passive, defensive, and ethical cybersecurity tool** designed for **educational purposes only**.  
It helps users analyze URLs, links, and local device hygiene **without exploiting, attacking, or bypassing any system**.

This project is built to promote **cyber awareness, safe browsing, and responsible security learning**, especially for students.

---

## ✨ Key Features

- 🔍 **URL / Domain Analysis**
  - HTTPS & redirect checks
  - TLS certificate inspection
  - Security headers (OWASP-based)
  - robots.txt & basic subdomain presence

- 🔗 **Text & Link Analysis**
  - Extracts links from text
  - Expands shortened URLs
  - Detects suspicious keywords (heuristic-based)
  - Optional VirusTotal hash lookup (user-provided API key)

- 📱 **Local Device Hygiene (Termux / Android)**
  - Disk usage overview
  - Running processes snapshot
  - Installed user apps listing
  - Network connections overview
  - Optional ClamAV hook (non-destructive)

- 📄 **Reports**
  - Human-readable log file
  - JSON summary output
  - Optional Telegram notification support

---

## 🧠 Design Principles

- ✅ **Read-only & Passive**
- ✅ **No exploitation, no brute force**
- ✅ **User consent & authorization required**
- ✅ **Educational and ethical focus**

---

## ⚠️ Legal & Ethical Notice

This tool **MUST be used only on**:
- Systems you own, **or**
- Systems where you have **explicit written permission** to test.

❌ Do NOT use this tool for:
- Unauthorized scanning
- Hacking or exploitation
- Privacy invasion
- Any illegal activity

The author takes **no responsibility for misuse** of this software.

---

## 🛠️ Requirements

- Termux (Android)
- bash
- curl
- openssl (recommended)
- sha256sum  
(Optional: whois, dig, clamscan, proot-distro)

---

## 🚀 Usage

```bash
chmod +x cyber_sentinel_allinone.sh
./cyber_sentinel_allinone.sh

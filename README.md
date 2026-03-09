# 🌐 NetworkDebloat

> PowerShell script to **disable unwanted network bindings** — File Sharing, MS Client, QoS, LLTD, IPv6, etc. Runs at startup as SYSTEM.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚫 **Disabled** | ms_server, ms_msclient, ms_pacer, ms_lltdio, ms_rspndr, ms_tcpip6 |
| ⏰ **Startup** | Scheduled task `NetworkDebloatStartup` at logon |
| 📂 **Copy** | Installs to `C:\Windows\Setup\Scripts` |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\NetworkDebloat.ps1
```

---

<p align="center">
  <sub>🔧 Gorstak Network Utilities</sub>
</p>

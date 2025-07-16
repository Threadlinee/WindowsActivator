# 💻 Microsoft Activation Scripts (MAS AIO)

**MAS AIO** is an all-in-one, open-source script suite for activating Microsoft products such as **Windows** and **Office** using multiple secure methods. It automates the process of licensing your system legally through Microsoft's own activation technologies.

> 🔗 Official site: [massgrave.dev](https://massgrave.dev)  
> 🌐 Script mirror: [get.activated.win](https://get.activated.win)

---

## 📌 Features

- 🔑 **HWID Activation** – Permanent digital license for Windows 10/11
- 🔐 **Ohook Activation** – Office activation bypass (Office 2016–2021, 365)
- 🛠️ **TSforge** – Flexible ticket-based activation (Windows / Office / ESU)
- 📅 **KMS38** – Offline activation valid until the year 2038
- 🌐 **Online KMS** – 180-day renewable activation using remote KMS servers
- 🧰 Tools to check activation status, switch editions, and troubleshoot

---

## 🧩 Activation Methods

| Option | Method      | Supports                             | Notes                                                  |
|--------|-------------|--------------------------------------|--------------------------------------------------------|
| `[1]`  | **HWID**     | Windows 10 / 11                      | Permanent, tied to hardware                            |
| `[2]`  | **Ohook**    | Office 2016–2021 / 365               | Bypass method, advanced users only                     |
| `[3]`  | **TSforge**  | Windows / Office / ESU (Win 7, etc.) | Uses forged activation tickets                         |
| `[4]`  | **KMS38**    | Windows 10 / 11                      | Offline activation valid till 2038                     |
| `[5]`  | **Online KMS** | Windows / Office                  | 180-day license with auto-renew                        |

---

## 🔧 Utilities

- Check Activation Status
- Change Windows/Office Edition
- Troubleshooting Tools
- Optional Office Installer (OfficeRTool)
- Registry cleanup (AutoRun issues, licensing fixes)

---

## ⚙️ Requirements

- Windows 7 SP1 and above (including Windows 11)
- PowerShell (Full Language Mode)
- Internet connection (for Online KMS or Ohook install/update)
- Optional: Windows Administrator access

---

## 🚀 How to Use

1. **Download the script**:
   - Download this repo here and after installation go inside folder and look the .txt file what it says to run the script.

2. **Run PowerShell as Administrator**, then execute:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
.\MAS_AIO.ps1
Select your preferred activation method from the menu.

Follow on-screen instructions. That's it!

🛡️ Is This Safe?
MAS is open-source and fully transparent.
While some antivirus solutions may flag activation methods (like KMS) as "potentially unwanted," the tool itself is clean and community-trusted.

✅ No telemetry
✅ No network abuse
✅ No harmful modifications

📚 License & Credits
Created and maintained by the Massgrave Community

License: MIT

📞 Support
If you're having trouble, check the official docs:
👉 massgrave.dev/troubleshoot
If you find this tool useful, drop a ⭐ or fork it. Contributions and proxy improvements are welcome.
```
[![Buy Me a Coffee](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G2G114SBVV)

🙏 Disclaimer
This project is intended for educational purposes only.
Use it only on systems where you have legal permission to activate or test software.

# 🖥️ wino-RAT

<p align="center">
  <b>Python Remote System Control Tool</b>
</p>

<p align="center">
  A Python-based remote administration and system-control tool for authorized environments, cybersecurity research, and laboratory testing.
</p>

<p align="center">
  <img src="assets/demo.gif" width="850" alt="wino-RAT Demo">
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🖼️ **Remote Screenshot** | Capture screenshots from the remote system |
| 🔌 **Remote Shutdown** | Shut down the remote computer |
| 💻 **System Information** | Retrieve hardware and operating-system information |
| 🌐 **Open Ports** | Detect and display open ports |
| 🌍 **IP Information** | Retrieve IP and network information |
| 👥 **User Enumeration** | Retrieve users available on the system |
| ➕ **User Creation** | Create a new local user account |
| 📂 **File Operations** | Perform remote file-management operations |
| 💣 **File Bomb** | Generate large numbers of files for controlled stress testing |
| ⚠️ **System32 Deletion** | Destructive testing functionality for isolated laboratory environments |

---

## 🛠️ Technologies

- 🐍 Python 3
- 🌐 TCP/IP
- 🔌 Socket Programming
- 🪟 Windows APIs
- 💻 Network Programming
- 🖥️ Remote System Administration

---

## 🚀 Installation

### 1. Clone the repository

```bash
https://github.com/Tblak-9/wino-RAT.git
cd wino-RAT
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Start the server

```bash
python main.py
```


## 🔐 Security

For authorized administration and research environments, the project should use:

- 🔑 Authentication and authorization
- 🔒 Encrypted communication such as TLS
- 🛡️ Command validation
- 📋 Logging and auditing
- 👤 Least-privilege execution
- ⚠️ Confirmation before destructive operations

Never use this software to access or control systems without explicit authorization.

---

## ⚠️ Destructive Features

Some features can potentially damage or disrupt a system.

**File Bomb** and **System32 Deletion** are intended only for controlled testing inside an isolated virtual machine or dedicated laboratory environment.

Do not execute destructive functionality against systems or data without explicit authorization.

---

## 📌 Disclaimer

This project is intended for:

- 🎓 Educational purposes
- 🔬 Cybersecurity research
- 🖥️ Authorized system administration
- 🛡️ Authorized security testing
- 🧪 Isolated laboratory environments

The author is not responsible for damage, data loss, unauthorized access, or misuse resulting from this software.

**Use responsibly and only on systems you are authorized to control.**

---

<p align="center">
  Made with ❤️ and 🐍 Python
</p>

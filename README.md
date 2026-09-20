# wino-RAT
🖥️ Python Remote System Control
A Python-based Remote System Control tool designed for authorized system administration, security research, and controlled laboratory environments.
> ⚠️ **Disclaimer:** This project should only be used on systems that you own or have explicit authorization to administer.
<p align="center">
  <img src="https://YOUR-GIF-URL-1.gif" width="800">
</p>
<p align="center">
  <img src="https://YOUR-GIF-URL-2.gif" width="800">
</p>
---
✨ Features
🖼️ Remote Screenshot — Capture screenshots from the remote system.
🔌 Remote Shutdown — Shut down the remote computer.
💻 System Information — Retrieve hardware and operating-system information.
🌐 Open Ports — Detect and display open ports on the system.
🌍 IP Information — Retrieve IP and network information.
👥 User Enumeration — Retrieve users available on the remote system.
➕ User Creation — Create a new local user account.
📂 File Operations — Perform remote file-management operations.
💣 File Bomb — Generate large numbers of files for controlled stress testing.
⚠️ System32 Deletion — Destructive testing functionality intended for isolated laboratory environments.
---
🛠️ Technologies
Python 3
TCP/IP
Socket Programming
Windows APIs
Network Programming
Remote System Administration
---
🚀 Installation
Clone the repository:
```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
---
▶️ Usage
Start the server:
```bash
python server.py
```
Run the client on the authorized target machine:
```bash
python client.py
```
Make sure the client and server can communicate over the network.
---
⚠️ Destructive Features
Some features of this project can potentially damage or disrupt a system.
Features such as File Bomb and System32 Deletion should only be tested inside an isolated virtual machine or dedicated laboratory environment.
Never run destructive functionality against systems or data without explicit authorization.
---
📜 Disclaimer
The author is not responsible for damage, data loss, unauthorized access, or misuse resulting from this software.
This project is intended for:
🎓 Educational purposes
🔬 Cybersecurity research
🖥️ System administration
🛡️ Authorized security testing
🧪 Isolated laboratory environments
Use responsibly and only on systems you are authorized to control.
---
<p align="center">
  <b>Made with ❤️ and Python 🐍</b>
</p>

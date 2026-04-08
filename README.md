
<h1 align="center">🐧 Linux Learning Path 🚀</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=28&color=00FFAA&center=true&vCenter=true&width=600&lines=Master+Linux+Step+by+Step;Learn+Commands+Like+a+Pro;Open+Source+%7C+Cybersecurity+%7C+DevOps" />
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Linux-Learning%20Path-blue?logo=linux&logoColor=white" />
   <img src="https://img.shields.io/badge/Open%20Source-❤-brightgreen?logo=opensourceinitiative" />
   <img src="https://img.shields.io/badge/Contributions-Welcome-orange?logo=github" />
   <img src="https://img.shields.io/github/stars/K921-cyber/linux-learning-path?style=social" />
   <img src="https://komarev.com/ghpvc/?username=K921-cyber&label=Profile+Views&color=blueviolet" />
</p>

---

> 💡 *“The shell is mightier than the sword.”*  
> Whether you're a developer, cybersecurity learner, or DevOps engineer — **Linux is your superpower.**

---

## 🌟 Why This Repository?

- ✔ Beginner-friendly guides  
- ✔ Step-by-step learning roadmap  
- ✔ Practical command examples  
- ✔ Cybersecurity & DevOps context  
- ✔ Open for contributions  
- ✔ No fluff — only real, usable knowledge  

---

## 🐧 What is Linux?

Linux is an open-source **kernel** written by Linus Torvalds in 1991. Distros (Ubuntu, Kali, Fedora) are built around this kernel.

> 🔧 *Linux = Engine*  
> *Distributions = Cars built around the engine*

👉 Scroll down to explore common Linux distributions.

---

## 🚀 Why Learn Linux?

- 🆓 **Free & Open Source**
- 🔒 **Secure by Design**
- ⚙️ **Perfect for Automation**
- ☁️ **Cloud-Native (AWS, Azure, GCP)**
- 🛡️ **Cybersecurity Industry Standard**
- 💻 **Developer Essential** (Git, Docker, Kubernetes, CI/CD)

---
# 🖥️ Install VirtualBox (Run Linux on Your System)

<p align="center">
  <img src="https://img.shields.io/badge/VirtualBox-Setup-blue?logo=virtualbox&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-Virtualization-green?logo=linux"/>
</p>

---

## 📦 What is VirtualBox?

**Oracle VM VirtualBox** is a free and open-source virtualization software that allows you to run multiple operating systems (like Linux) on your current system.

> 💡 Think of it as:  
> **Your PC → runs a virtual PC inside it**

---

## 🚀 Steps to Download & Install VirtualBox

### 🔽 Step 1: Download VirtualBox

👉 Visit the official website:  
https://www.virtualbox.org/wiki/Downloads  

- Click on **Windows Hosts** (for Windows users)  
- Select macOS/Linux accordingly  

---

### ⚙️ Step 2: Install VirtualBox

1. Open the downloaded `.exe` file  
2. Click **Next → Next → Install**  
3. Allow system permissions if prompted  
4. Wait for installation to complete  
5. Click **Finish**

---

### 🔌 Step 3: Install Extension Pack (Important)

- Download the **Extension Pack** from the same page  
- Open VirtualBox  
- Go to: **File → Preferences → Extensions**  
- Click ➕ and add the Extension Pack  

> ⚠️ Required for USB support, better performance, and advanced features

---

## 🐧 Run Linux on VirtualBox

### 📥 Step 4: Download Linux ISO

- Ubuntu → https://ubuntu.com/download  
- Kali Linux → https://www.kali.org/get-kali/  

---

### 🛠️ Step 5: Create Virtual Machine

1. Open VirtualBox  
2. Click **New**  
3. Enter Name: `Ubuntu` / `Kali`  
4. Type: `Linux`  
5. Version: Select appropriate distro  

---

### 💾 Step 6: Allocate Resources

- RAM: **2GB minimum (4GB recommended)**  
- Storage: **20GB+**

---

### ▶️ Step 7: Start & Install OS

1. Click **Start**  
2. Select downloaded ISO file  
3. Follow on-screen installation  

---

## 🎯 Cybersecurity Tip

If you're learning **Cybersecurity / VAPT / SOC**:

- Use **Kali Linux** inside VirtualBox  
- Practice tools like:
  - `nmap`
  - `burpsuite`
  - `wireshark`
- Build your own **safe home lab**

---

## ⭐ Pro Tip

- Take snapshots before testing tools 🧪  
- Allocate enough RAM for smooth performance ⚡  
- Use NAT or Bridged networking depending on use-case 🌐  

---

> 🐧 “Don’t just use Linux — virtualize it, break it, rebuild it, master it.”

---

## 🖥️ Common Linux Distributions

| Distribution | Logo | Best For | Download |
|--------------|------|----------|----------|
| **Ubuntu** | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/1200px-UbuntuCoF.svg.png" width="55"/> | Beginners, Developers | [Download](https://ubuntu.com/download) |
| **Kali Linux** | <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" width="55"/> | Pentesting, Security | [Download](https://www.kali.org/get-kali/) |
| **Debian** | <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png" width="55"/> | Servers, Stability | [Download](https://www.debian.org/) |
| **Arch Linux** | <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Arch_Linux_%22Crystal%22_icon.svg" width="55"/> | Advanced Users | [Download](https://archlinux.org/) |
| **Fedora** | <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Fedora_icon_%282021%29.svg" width="55"/> | Latest Tech, Workstations | [Download](https://fedoraproject.org/) |

> 🆕 **Beginners → Ubuntu**  
> 🔐 **Hackers → Kali Linux**

---

## 🎯 What Can You Do With Linux?

<div align="center">
  <img src="https://media1.giphy.com/media/dDwicM3uFUqfC/giphy.gif" width="480" />
</div>

- Host websites (Nginx/Apache)  
- Write scripts in Bash/Python  
- Run cybersecurity tools (nmap, Metasploit, Wireshark)  
- Automate tasks  
- Manage cloud servers  
- Build DevOps pipelines  

---

# 📚 Linux Command Cheat Sheets

### 📁 Navigation & File Management
| Command | Description | Example |
|--------|-------------|---------|
| `pwd` | Show working directory | `pwd` |
| `ls` | List files | `ls -la` |
| `cd` | Change directory | `cd /etc` |
| `mkdir` | Create folder | `mkdir project` |
| `touch` | Create file | `touch notes.txt` |
| `cp` | Copy file | `cp file /backup/` |
| `mv` | Move/rename | `mv test.txt old.txt` |
| `rm` | Delete file | `rm file.txt` |

---

### 🔍 Search & Text Utilities
| Command | Description | Example |
|--------|-------------|---------|
| `cat` | Show file contents | `cat data.txt` |
| `less` | Scroll inside file | `less logs.txt` |
| `grep` | Search text | `grep "error" sys.log` |
| `find` | Search files | `find / -name "*.conf"` |
| `tail -f` | Live log view | `tail -f /var/log/auth.log` |
| `wc` | Count words/lines | `wc -l file.txt` |

---

### 🔐 Permissions & Users
| Command | Description | Example |
|--------|-------------|---------|
| `chmod` | Change permissions | `chmod +x script.sh` |
| `chown` | Change owner | `sudo chown user file` |
| `whoami` | Show user | `whoami` |
| `sudo` | Admin privileges | `sudo apt update` |
| `passwd` | Change password | `passwd` |

---

### 📊 System Monitoring
| Command | Description | Example |
|--------|-------------|---------|
| `top` / `htop` | Monitor system | `htop` |
| `ps` | List processes | `ps aux` |
| `kill` | Kill a process | `kill 2221` |
| `df -h` | Disk usage | `df -h` |
| `du -sh` | Folder size | `du -sh /home` |
| `free -m` | RAM usage | `free -m` |
| `uname -a` | System version | `uname -a` |
| `uptime` | System uptime | `uptime` |

---

### 🌐 Networking
| Command | Description | Example |
|--------|-------------|---------|
| `ping` | Check connectivity | `ping google.com` |
| `ip addr` | Network details | `ip addr show` |
| `ifconfig` | Old network tool | `ifconfig` |
| `ssh` | Remote login | `ssh user@host` |
| `scp` | Secure file copy | `scp file user@host:/path` |
| `tar` | Archive/Extract | `tar -czvf data.tar.gz folder/` |

---

# 📖 Recommended Learning Resources

- 📘 Linux Journey — *Beginner Interactive Lessons*  
  https://linuxjourney.com  

- 📗 The Linux Command Line (Free Book)  
  https://linuxcommand.org/tlcl.php  

- 🕹 OverTheWire: Bandit — *Hack your way through challenges*  
  https://overthewire.org/wargames/bandit  

- 🧪 TryHackMe — Linux Fundamentals  
  https://tryhackme.com/room/linuxfundamentals  

- ▶️ Net Ninja Linux Tutorials  
  https://youtube.com/playlist?list=PL4cUxeGkcC9iSUQijlxawrdwYlVppYRVD  

---


# 🤝 How to Contribute

1. Fork the repository  
3. Improve any section or add new command explanations  
4. Submit a Pull Request  
5. Get featured in the **Contributors Section**  

> 💬 Even fixing a small typo improves the project!

---


# 📜 License

Licensed under **MIT License**  
© 2025 **K921-cyber**

---

# ⭐ Support the Project

If this project helped you:  
👉 **Give it a ⭐ on GitHub**  
👉 Share it with other learners  

> “Teach a man Linux, and he controls the server.” 😎🐧

---

# 📂 Contribute & Learn Linux

### 📌 Master Commands (Click to View Files)

- [Introduction to Linux & Basic Commands](linux-intro.md)
- [`basic directory command`](info/linux-intro.md) – Searching directories
- [`pwd`](info/pwd.md) – Show absolute path
- [`cat`](info/cat.md) – Display file content
- [`grep`](info/grep.md) – Search patterns
- [`find`](info/find.md) – Search files anywhere
- [`chmod`](info/chmod.md) – Manage permissions
- [`touch`](info/touch.md) – Create files
- [`echo`](info/echo.md) – Print text & shell operators
- [`whoami`](info/whoami.md) – Show current user
- [`nano`](info/nano.md) – Terminal text editor
- [`ps`](info/ps.md) – Running processes
- [`kill`](info/kill.md) – Terminate a process
- [`tar`](info/tar.md) – Archive tool
- [`top`](info/top.md) – Live system monitor
- [`file`](info/file.md) – Identify file types
- [`ping`](info/ping.md) – Network connectivity
- [`head`](info/head.md) – First lines of file
- [`wc`](info/wc.md) – Count words/lines
- [`mkdir`](info/mkdir.md) – Create directories
- [`tail`](info/tail.md) – Last lines of file
- [`du`](info/du.md) – Disk usage summary
- [`df`](info/df.md) – Disk space usage
- [`free`](info/free.md) – Memory usage
- [`uname`](info/uname.md) – System info
- [`uptime`](info/uptime.md) – System running time

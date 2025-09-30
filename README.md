<h1 align="center">🐧 Linux Learning Path 🚀</h1>

<p align="center">
   <img src="https://readme-typing-svg.herokuapp.com?size=28&color=00FFAA&center=true&vCenter=true&width=600&lines=Master+Linux+Step+by+Step;Learn+Commands+Like+a+Pro;Open+Source+%7C+Cybersecurity+%7C+DevOps" alt="Typing SVG" />
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Linux-Learning%20Path-blue?logo=linux&logoColor=white" />
   <img src="https://img.shields.io/badge/Open%20Source-❤-brightgreen?logo=opensourceinitiative" />
   <img src="https://img.shields.io/badge/Contributions-Welcome-orange?logo=github" />
   <img src="https://img.shields.io/github/stars/K921-cyber/linux-learning-path?style=social" />
   <img src="https://komarev.com/ghpvc/?username=K921-cyber&label=Profile+Views&color=blueviolet" />
</p>

---

> 💡 *"The shell is mightier than the sword."*  
> Whether you’re a dev, pentester, or cloud engineer — **Linux is your superpower.**

---

## 🌟 Why This Repo?

✅ Beginner-friendly walkthroughs  
✅ Practical command examples + cheat sheets  
✅ Cybersecurity & DevOps context  
✅ Contribute & grow together 🤝  
✅ No fluff — just real, usable knowledge

---

## 🐧 What is Linux?

Linux is a **free, open-source kernel** created by Linus Torvalds in 1991. Combined with GNU tools, it becomes a full OS — called a **“distribution” (distro)**.

> 🔧 Think of Linux as the engine. Distributions (Ubuntu, Kali, etc.) are the cars built around it.

👉 [Install Linux for Free (Guide)](#-common-linux-distributions)

---

## 🚀 Why Learn Linux?

<details>
<summary>Click to expand 🔽</summary>

- 🆓 **Free & Open Source** — Modify, share, learn without limits
- 🔒 **Secure by Design** — Permissions, users, logs = defense-first OS
- ⚙️ **Automation Heaven** — Bash, Python, Cron — automate EVERYTHING
- ☁️ **Cloud Native** — AWS, Azure, GCP? All run on Linux under the hood
- 🛡️ **Hackers’ Playground** — Kali, Parrot, BlackArch — all Linux-based
- 💻 **Developer Essential** — Git, Docker, Kubernetes, CI/CD — all love Linux

</details>

---

## 🖥️ Common Linux Distributions

| Distro | Logo | Best For | Try It |
|--------|------|----------|--------|
| **Ubuntu** | ![Ubuntu](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/120px-UbuntuCoF.svg.png) | Beginners, Devs, Desktop | [Download](https://ubuntu.com/download) |
| **Kali Linux** | ![Kali](https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg) | Pentesting, Security | [Download](https://www.kali.org/get-kali/) |
| **Debian** | ![Debian](https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/Debian_logo.svg/120px-Debian_logo.svg.png) | Stability, Servers | [Download](https://www.debian.org/) |
| **Arch Linux** | ![Arch](https://upload.wikimedia.org/wikipedia/commons/1/13/Arch_Linux_%22Crystal%22_icon.svg) | Advanced Users, DIY | [Download](https://archlinux.org/) |
| **Fedora** | ![Fedora](https://upload.wikimedia.org/wikipedia/commons/9/9a/Fedora_logo.svg) | Cutting-edge Tech | [Download](https://fedoraproject.org/) |

> 💡 **Newbie? Start with Ubuntu.** Want to hack ethically? Grab **Kali Linux**.

---

## 🎯 What Can You DO With Linux?

<div align="center">

![Terminal GIF](https://media.giphy.com/media/l0HlG8vJkDQZzUjXO/giphy.gif)

</div>

- 🌐 Host websites (Apache, Nginx)
- 🐍 Code & debug in Python, C++, Rust, Go
- 🛡️ Run security tools: nmap, Wireshark, Metasploit
- 🤖 Automate tasks with Bash/Python scripts
- ☁️ Manage servers on AWS, DigitalOcean, Linode
- 🧪 Experiment safely in VMs or containers

---

## 📚 Command Cheatsheets (Click to Expand!)

<details>
<summary>📁 Navigation & Files</summary>

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Show current directory | `pwd` → `/home/user` |
| `ls` | List files | `ls -la` → show hidden + details |
| `cd` | Change directory | `cd /var/log` |
| `mkdir` | Create folder | `mkdir myproject` |
| `touch` | Create empty file | `touch notes.txt` |
| `cp` | Copy file/folder | `cp file1.txt backup/` |
| `mv` | Move/rename | `mv old.txt new.txt` |
| `rm` | Delete file | `rm temp.txt` *(careful!)* |

</details>

<details>
<summary>🔍 Search & Text Tools</summary>

| Command | Description | Example |
|---------|-------------|---------|
| `cat` | Display file content | `cat file.txt` |
| `less` | Scroll through large files | `less big.log` |
| `grep` | Search text patterns | `grep "error" syslog.log` |
| `find` | Search for files | `find / -name "*.conf"` |
| `head` / `tail` | View start/end of file | `tail -f logfile.log` |
| `wc` | Count lines/words | `wc -l file.txt` |

</details>

<details>
<summary>🔐 Permissions & Users</summary>

| Command | Description | Example |
|---------|-------------|---------|
| `chmod` | Change permissions | `chmod +x script.sh` |
| `chown` | Change owner | `sudo chown user:group file` |
| `whoami` | Show current user | `whoami` → `kali` |
| `sudo` | Run as admin | `sudo apt update` |
| `passwd` | Change password | `passwd` |

</details>

<details>
<summary>📊 System Monitoring</summary>

| Command | Description | Example |
|---------|-------------|---------|
| `top` / `htop` | Live process viewer | `htop` *(install first)* |
| `ps` | List processes | `ps aux \| grep firefox` |
| `kill` | Terminate process | `kill 1234` |
| `df` | Disk space | `df -h` |
| `du` | Folder size | `du -sh /home` |
| `free` | Memory usage | `free -m` |
| `uname` | System info | `uname -a` |
| `uptime` | System uptime | `uptime` |

</details>

<details>
<summary>📦 Archives & Networking</summary>

| Command | Description | Example |
|---------|-------------|---------|
| `tar` | Compress/extract | `tar -czvf archive.tar.gz folder/` |
| `ping` | Test connectivity | `ping google.com` |
| `ifconfig` / `ip` | Network config | `ip addr show` |
| `ssh` | Remote login | `ssh user@server.com` |
| `scp` | Secure copy | `scp file.txt user@host:/path` |

</details>

---

## 📂 Folder Structure

```<h1 align="center">🐧 Linux Learning Path 🚀</h1>

<p align="center">
   <img src="https://readme-typing-svg.herokuapp.com?size=24&color=00FF00&width=600&lines=Master+Linux+Step+by+Step;Learn+Commands+Like+a+Pro;Open+Source+%7C+Cybersecurity+%7C+DevOps" alt="Typing SVG" />
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Linux-Learning%20Path-blue?logo=linux&logoColor=white" />
   <img src="https://img.shields.io/badge/Open%20Source-❤-brightgreen?logo=opensourceinitiative" />
   <img src="https://img.shields.io/badge/Contributions-Welcome-orange?logo=github" />
   <img src="https://img.shields.io/github/stars/K921-cyber" />
</p>

---

🧠 *Whether you're a developer, sysadmin, or security enthusiast—understanding Linux opens the door to powerful tools and career opportunities.*

---

## ✨ About This Repo
This repository is a **Linux learning journey** where I document important concepts, commands, and practical use cases.  
Whether you’re a beginner or brushing up on Linux skills, this repo will help you learn effectively.  

---

## <img src="https://upload.wikimedia.org/wikipedia/en/thumb/8/80/Wikipedia-logo-v2.svg/1024px-Wikipedia-logo-v2.svg.png" width="60"/> Table of Contents
- [🔹 Background on Linux](#-background-on-linux)
- [🔹 What is Linux?](#-what-is-linux)
- [🔹 Why is Linux Important?](#-why-is-linux-important)
- [🔹 Common Distributions](#-common-linux-distributions)
- [🔹 Commands & Cheatsheets](#-Contribute-&-Learn-Linux)

---

## <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/330px-Tux.svg.png" width="60"/>  Background on Linux


Linux is a free and open-source operating system kernel first developed by Linus Torvalds in 1991. Over time, it became the foundation for hundreds of Linux distributions used across desktops, servers, mobile devices, and embedded systems.

if Linux not installed go -here

##📌 What is Linux?
Linux itself is just a **kernel** — the part of the OS that manages hardware.  
To become a full OS, it’s bundled with software like **GNU tools, shells, and graphical interfaces**. Together, they form a **Linux distribution (distro).**
Linux powers everything from supercomputers and smartphones to cloud platforms and ethical hacking labs.

👉 [Install Linux here](#)

> 💡 Linux powers everything from **supercomputers** and **smartphones** to **cloud platforms** and **ethical hacking labs**.

---

## 🚀 Why is Linux Important?
- 🆓 **Open Source:** Freely available and customizable  
- 🔧 **Flexible:** Works on microcontrollers → massive servers  
- 🔒 **Secure:** Designed with user permissions & isolation  
- 👨‍💻 **Dev-Friendly:** Perfect for coding, scripting & DevOps  
- 🌐 **Network-Ready:** Tools for monitoring & networking  

---

## <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/330px-Tux.svg.png" width="60"/> Common Linux Distributions  

| Distribution | Logo | Best For |
|--------------|------|----------|
| **Ubuntu**   | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/2048px-UbuntuCoF.svg.png" width="60"/> | Beginner-friendly and widely supported |
| **Kali**     | <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" width="60"/> | Cybersecurity & penetration testing |
| **Debian**   | <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png" width="60"/> | Stability and reliability |
| **Arch**     | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Arch_Linux_%22Crystal%22_icon.svg/1200px-Arch_Linux_%22Crystal%22_icon.svg.png" width="60"/> | Lightweight, fully customizable |
| **CentOS**   | <img src="https://cdn.freebiesupply.com/logos/large/2x/centos-1-logo-png-transparent.png" width="60"/> | Enterprise-grade server OS |


---

## <img src="https://i.pinimg.com/originals/32/88/2d/32882dbcd4424eb8e814ce8e62e68361.gif" width="60">What You Can Do With Linux
- 🌍 Run web servers (Apache, NGINX)  
- 🐍 Code in any major language (Python, C, Java)  
- 🛡️ Perform cybersecurity tasks & forensics  
- ⚙️ Automate tasks using shell scripts  
- 🔍 Monitor and secure networks  
- ☁️ Manage cloud instances (AWS, Azure, GCP)  

---

##  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/330px-Tux.svg.png" width="60"/>Contribute & Learn Linux

- [Introduction to Linux and Basic Commands](linux-intro.md)
- [`basic directory command`](info/linux-intro.md) -In directory search
- [`pwd`](info/pwd.md) -Display the absolute path
- [`cat`](info/cat.md) –Read concatenate and display
- [`grep`](info/grep.md) –Search for patterns in text
- [`find`](info/find.md) -Search through the given set of info 
- [`chmod`](info/chmod.md) -Change the access permissions of files and directories
- [`touch`](info/touch.md) -Creates new empty files
- [`echo and Shell operator`](info/echo.md) -Print the words
- [`whoami`](info/whoami.md) -Prints the current effective username
- [`nano`](info/nano.md) -Terminal based text editor
- [ `ps`](info/ps.md) -Information about active processes
- [`kill`](info/kill.md) -Terminate or signal process
- [`tar`](info/tar.md) -Create, maintain, modify, extract files
- [`top`](info/top.md) -Process monitoring tool
- [`file`](info/file.md) -Determines type of file
- [`ping`](info/ping.md) -Checks the cconnectivity
- [`head `](info/head.md) -View first few lines
- [`wc`](info/wc.md) -Count lines,words,charcters nad bytes
- [`mkdir`](info/mkdir) -Create new directory and folders
- [`tail`](info/tail.md) -View last part of file
- [`du`](info/du.md) -Estimate and summarize the disk usage
- [`df`](info/df.md) -Check disk space usage
- [`free`](info/free.md) -Check RAM and swap memory usage
- [`uname`](info/uname.md) -Prints system information
- [`uptime`](info/uptime.md) -Display how long system had been running 



## 🔗 Learn More

- [Linux Journey](https://linuxjourney.com)
- [The Linux Command Line Book (PDF)](https://linuxcommand.org/tlcl.php)
- [TryHackMe: Linux Fundamentals](https://tryhackme.com/room/linuxfundamentals)



Want to add commands, examples, or tips? Feel free to **fork & PR** 🚀  

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


- 🆓 **Free & Open Source** — Modify, share, learn without limits
- 🔒 **Secure by Design** — Permissions, users, logs = defense-first OS
- ⚙️ **Automation Heaven** — Bash, Python, Cron — automate EVERYTHING
- ☁️ **Cloud Native** — AWS, Azure, GCP? All run on Linux under the hood
- 🛡️ **Hackers’ Playground** — Kali, Parrot, BlackArch — all Linux-based
- 💻 **Developer Essential** — Git, Docker, Kubernetes, CI/CD — all love Linux


---

## 🖥️ Common Linux Distributions

| Distro | Logo | Best For | Try It |
|--------|------|----------|--------|
| **Ubuntu** |  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/2048px-UbuntuCoF.svg.png" width="60"/> | Beginners, Devs, Desktop | [Download](https://ubuntu.com/download) |
| **Kali Linux** |  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" width="60"/> | Pentesting, Security | [Download](https://www.kali.org/get-kali/) |
| **Debian** |  <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png" width="60"/>  | Stability, Servers | [Download](https://www.debian.org/) | 
| **Arch Linux** | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Arch_Linux_%22Crystal%22_icon.svg/1200px-Arch_Linux_%22Crystal%22_icon.svg.png" width="60"/>  | Advanced Users, DIY | [Download](https://archlinux.org/) |
| **Fedora** | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Fedora_icon_%282021%29.svg/1044px-Fedora_icon_%282021%29.svg.png" width="60" /> | Cutting-edge Tech | [Download](https://fedoraproject.org/) |

> 💡 **Newbie? Start with Ubuntu.** Want to hack ethically? Grab **Kali Linux**.

---

## 🎯 What Can You DO With Linux?

<div align="center">

![Terminal GIF](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWt1MHptazlpbnQwN3ljcnA4ZGVidmY0dnczN3RicHFkNm02dGZ5MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/dDwicM3uFUqfC/giphy.gif)

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


---

## 📖 Learn More (Free Resources)

🔗 [Linux Journey (Interactive)](https://linuxjourney.com)  
📘 [The Linux Command Line (Free Book)](https://linuxcommand.org/tlcl.php)  
🎮 [OverTheWire: Bandit (Game-Based Learning)](https://overthewire.org/wargames/bandit/)  
🧪 [TryHackMe: Linux Fundamentals](https://tryhackme.com/room/linuxfundamentals)  
📺 [YouTube: The Net Ninja - Linux Tutorials](https://youtube.com/playlist?list=PL4cUxeGkcC9iSUQijlxawrdwYlVppYRVD)

---

## 🤝 How to Contribute

1. Fork this repo 🍴
2. Add a command guide, fix a typo, or improve an example ✍️
3. Submit a Pull Request 🔄
4. Get credited in our [🌟 Contributors](#-contributors) section!

> 💬 *No contribution is too small — even fixing a typo helps!*

---

## 📜 License

MIT © [K921-cyber](https://github.com/K921-cyber)  
📚 Free to learn, share, teach — just don’t plagiarize 😊

---

⭐ **Star this repo if it helps you!**  
📬 **Questions?** Open an Issue — I reply within 24h!

> “Give a man a fish, he eats for a day. Teach him Linux, he owns the server.” — Ancient Hacker Proverb 😎🐧



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



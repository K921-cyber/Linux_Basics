# 🖥️ uname – System Information  

The `uname` command is used to **print system information** such as the kernel name, version, and other system details.  
It helps in identifying the operating system and hardware platform.  

---

## 📌 Overview  

`uname` stands for **Unix Name**.  
It can display:  
- Kernel name  
- Node (hostname)  
- Kernel release and version  
- Machine hardware name  
- Processor and operating system type  

---

## ⚙️ Common Examples  

| Command        | Description                                |
|----------------|--------------------------------------------|
| `uname`        | Show the kernel name (default output)      |
| `uname -a`     | Show all available system information      |
| `uname -r`     | Display the kernel release                 |
| `uname -v`     | Display the kernel version                 |
| `uname -n`     | Show the network node hostname             |
| `uname -m`     | Show machine hardware name (architecture)  |
| `uname -p`     | Show processor type (if available)         |
| `uname -o`     | Show operating system type                 |

---

## 🧠 Option Breakdown  

| Option | Description                           |
|--------|---------------------------------------|
| `-a`   | All system information                |
| `-s`   | Kernel name (default)                 |
| `-n`   | Node/hostname                         |
| `-r`   | Kernel release                        |
| `-v`   | Kernel version                        |
| `-m`   | Machine hardware name                 |
| `-p`   | Processor type                        |
| `-o`   | Operating system                      |

---

## ✅ Use Cases  

- 🔍 **Check Kernel Version**  
  Useful for troubleshooting system compatibility.  

- 🖥️ **Verify Architecture**  
  Determine if the system is 32-bit or 64-bit.  

- 🌐 **Hostname Lookup**  
  Quickly view the system’s network hostname.  

---

💡 *Pro Tip:*  
Use `uname -a` for a **complete system overview** in one line.  

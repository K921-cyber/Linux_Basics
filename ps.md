# 🧠 `ps` – Process Status

The `ps` command displays **information about active processes** on a system. It is commonly used for monitoring, troubleshooting, and managing running programs.

---

## 📌 Overview

`ps` stands for **Process Status**. It provides a snapshot of the current processes and can be combined with various options to display useful details such as **PID**, **TTY**, **CPU usage**, and **memory usage**.

---

## ⚙️ Common Examples

| Command            | Description                                              |
|--------------------|----------------------------------------------------------|
| `ps`               | Show current user’s active processes                     |
| `ps -e`            | Show all processes                                       |
| `ps -ef`           | Full-format listing of all processes                     |
| `ps aux`           | Display all processes with detailed information          |
| `ps -u <username>` | Display processes owned by a specific user               |
| `ps -p <pid>`      | Display information about a specific process             |
| `ps -ef | grep ssh`| Find SSH-related processes                               |

---

## 🧠 Option Breakdown

| Option | Description                                 |
|--------|---------------------------------------------|
| `-e`   | Show all processes                          |
| `-f`   | Full-format listing                         |
| `a`    | Show processes of all users                 |
| `u`    | Display user-oriented format                |
| `x`    | Include processes without controlling terminal |
| `-p`   | Select process by PID                       |

---

## ✅ Use Cases

- 🔎 **Monitoring**  
  Check which processes are consuming CPU or memory.

- 🛠️ **Debugging**  
  Investigate hanging or misbehaving applications.

- 🔐 **Security**  
  Detect unwanted or unauthorized processes running on the system.

- 👥 **User Process Management**  
  List and manage processes started by a specific user.

---

📎 *Pro Tip:* Combine `ps` with `grep` or `less` for advanced filtering:
```bash
ps aux | grep apache

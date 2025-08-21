
# 🔍 top – Task Manager for Linux

The `top` command displays real-time information about **running processes**, CPU usage, memory consumption, and system load.  
It’s like the Linux version of Task Manager, but in the terminal.

---

## 📌 Overview

`top` is a **process monitoring tool** that helps administrators and users identify resource-hungry processes and manage them.  
It updates the display every few seconds, giving a live view of system performance.

---

## ⚙️ Common Examples

| Command          | Description                                          |
|------------------|------------------------------------------------------|
| `top`            | Launch `top` to monitor system processes             |
| `top -u username`| Show processes for a specific user                    |
| `top -n 5`       | Refresh the display 5 times and then exit             |
| `top -p 1234`    | Show details for a specific process ID (PID)          |
| `top -o %MEM`    | Sort processes by memory usage                        |

---

## 🧠 Option Breakdown

| Option   | Description                                      |
|----------|--------------------------------------------------|
| `-u`     | Show only processes for the given username        |
| `-n`     | Number of iterations before `top` exits           |
| `-p`     | Show only specific process IDs                    |
| `-o`     | Sort output by a given column (e.g., `%CPU`, `%MEM`) |

---

## ✅ Use Cases

- 📊 **System Monitoring**  
  Quickly see which processes are consuming the most resources.

- 🛠️ **Performance Debugging**  
  Identify CPU spikes or memory leaks in real-time.

- 🔍 **User-specific Tracking**  
  Focus on the processes of a particular user for troubleshooting.

---

💡 *Pro Tip:* While `top` is running, press:
- `M` → Sort by memory usage
- `P` → Sort by CPU usage
- `k` → Kill a process
- `q` → Quit

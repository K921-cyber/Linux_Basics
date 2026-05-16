
# 💀 `kill` – Terminate Processes by PID

The `kill` command is used to **terminate or signal processes** by their Process ID (PID). It's especially useful when you need to stop unresponsive or rogue programs.

---

## 📌 Overview

`kill` sends **signals** to running processes. By default, it sends the `SIGTERM` signal to **gracefully ask a process to terminate**. You can also send other signals such as `SIGKILL` to forcefully kill a process.

---

## ⚙️ Common Examples

| Command            | Description                                         |
|--------------------|-----------------------------------------------------|
| `kill <pid>`       | Send default signal (SIGTERM) to a process          |
| `kill -9 <pid>`    | Forcefully kill a process using SIGKILL             |
| `kill -15 <pid>`   | Gracefully terminate a process using SIGTERM        |
| `kill -l`          | List all available signals                          |
| `kill -s SIGSTOP <pid>` | Stop (pause) a process                         |
| `kill -s SIGCONT <pid>` | Resume a stopped process                       |

---

## 🧠 Signal Breakdown

| Signal   | Number | Description                        |
|----------|--------|------------------------------------|
| `SIGTERM`| 15     | Graceful termination               |
| `SIGKILL`| 9      | Forceful kill (can't be caught)    |
| `SIGSTOP`| 19     | Pause process                      |
| `SIGCONT`| 18     | Continue paused process            |
| `SIGHUP` | 1      | Reload configuration               |

---

## ✅ Use Cases

- 🛑 **Stop Frozen Applications**  
  Terminate unresponsive processes with `kill -9`.

- 🔁 **Reload Configurations**  
  Send `SIGHUP` to make daemons reload their config without restarting.

- ⏸️ **Pause/Resume**  
  Temporarily suspend and resume processes (e.g., CPU-intensive tasks).

- 🔒 **Security**  
  Kill suspicious or unauthorized processes running in the background.

---

📎 *Pro Tip:* Use `ps aux | grep <name>` to find the PID of a process before using `kill`.

```bash
ps aux | grep firefox
kill -9 12345

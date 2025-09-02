# 📂 du – Disk Usage  

The `du` command is used to **estimate and summarize disk space usage** of files and directories.  

---

## 📌 Overview  

- Shows how much space a directory or file is taking  
- Useful for finding which folders consume the most storage  
- Can display results in human-readable format (KB, MB, GB)  

---

## ⚙️ Common Examples  

| Command            | Description                                        |
|--------------------|----------------------------------------------------|
| `du`               | Show disk usage of current directory (in KB)       |
| `du -h`            | Human-readable (KB, MB, GB)                        |
| `du -sh *`         | Show size of each item in current directory        |
| `du -sh /var/log`  | Show total size of `/var/log` folder               |
| `du -ah`           | Show size of all files + directories recursively   |
| `du -sh --max-depth=1` | Summarize only top-level directories          |

---

## 🧾 Example Output  

```bash
4.0K    ./scripts
12M     ./downloads
1.5G    ./videos
2.0G    .

# 📜 less – View File Content (Scroll-Friendly)  

The `less` command lets you **view file content one screen at a time** without opening an editor.  
It’s more advanced than `cat` because it allows scrolling, searching, and navigation.  

---

## 📌 Overview  

- Displays large files page by page  
- Allows moving forward/backward through content  
- Supports searching inside files  
- Doesn’t load the entire file into memory (efficient for big logs)  

---

## ⚙️ Common Examples  

| Command              | Description                                |
|----------------------|--------------------------------------------|
| `less file.txt`     | Open a file with `less`                    |
| `less /var/log/syslog` | View system log file                     |
| `ls -l | less`      | Pipe command output into `less`            |
| `less +100 file.txt` | Open file starting at line 100             |

---

## 🧠 Navigation Keys  

| Key       | Action                               |
|-----------|--------------------------------------|
| `Space`   | Move forward one page                |
| `b`       | Move back one page                   |
| `Enter`   | Move forward one line                |
| `/word`   | Search for “word” forward            |
| `?word`   | Search for “word” backward           |
| `n`       | Repeat last search                   |
| `q`       | Quit `less`                          |

---

## ✅ Use Cases  

- 🔍 **Log Analysis** – Scroll through massive log files without crashing your terminal.  
- 📄 **File Preview** – Quickly check text files without editing.  
- 🚀 **Efficiency** – Handles big files better than `cat` or `more`.  

---

💡 *Pro Tip:* Combine with pipes like `dmesg | less` for real-time kernel or system message review.  

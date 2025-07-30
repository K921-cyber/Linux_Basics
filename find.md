# 🔎 find – Locate Files & Directories

The `find` command is used to **search for files and directories** in a directory hierarchy based on various criteria such as name, size, date, type, and permissions.

---

## 📌 Overview

Unlike `locate`, `find` searches the file system in real-time. It’s very powerful and customizable for administrative and automation tasks.

---

## ⚙️ Common Examples

| Command                                       | Description                                           |
|-----------------------------------------------|-------------------------------------------------------|
| `find / -name "file.txt"`                    | Search for `file.txt` starting from root             |
| `find . -type f -name "*.sh"`                | Find all `.sh` files in current directory            |
| `find /var -mtime -1`                        | Files modified in the last 1 day in `/var`           |
| `find . -size +1M`                           | Files larger than 1MB                                |
| `find /tmp -type f -empty`                   | Empty files in `/tmp`                                |
| `find . -type f -exec chmod 644 {} \;`       | Change permission of all files in current dir        |

---

## 🧠 Option Breakdown

| Option     | Meaning                                   |
|------------|-------------------------------------------|
| `-name`    | Search by file name                       |
| `-type`    | Specify file type (f = file, d = dir)     |
| `-mtime`   | Match modification time                   |
| `-size`    | Search by file size                       |
| `-empty`   | Match empty files or directories          |
| `-exec`    | Run command on matched files              |

---

## ✅ Use Cases

- 🧹 **Cleanup Scripts**  
  Find and delete temporary files, empty files, or old logs.

- 🔐 **Security Checks**  
  Locate files with insecure permissions.

- 📦 **Storage Audits**  
  Identify large files consuming disk space.

- ⚙️ **Automation**  
  Combine `find` with `exec` to automate batch actions.

---

📎 *Note:* Always test with `-print` or `-ls` before using `-exec rm`.

---

✨ `find` is the Swiss Army knife of file searching — versatile and script-friendly. Master this, and you'll be a Linux ninja 🥷

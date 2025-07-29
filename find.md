# 🐧 Daily Linux Command – `find`

## 🔍 Description:
The `find` command is used to **search for files and directories** in a directory hierarchy.

---

## ⚙️ Basic Syntax:
```bash
find [path] [options] [expression]
```
Find all .txt files in a directory:
-----------------------
find /home/user-name/Documents -name "*.txt"

 Find files larger than 100MB
 ----
 find . -type f -size +100M

 Delete all .log files (Be careful!)
 ---
 find . -name "*.log" -delete

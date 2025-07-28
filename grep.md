# 🔍 Linux Command: `grep`

**Command:** `grep`  
**Purpose:** Searches for specific text patterns in files or command output.

---

## 🔧 Syntax

```bash
grep [options] pattern [file...]

--------------------------------------

```

Search a word in a file:

grep "root" /etc/passwd
-------------------------

Case-insensitive search:

grep -i "linux" file.txt
-------------------------

Recursive search in directories:
grep -r "sudo" /etc
-------------------------


Show line numbers with matches:
grep -n "error" logfile.log
-------------------------


Regex example — lines starting with 'a'
grep "^a" file.txt


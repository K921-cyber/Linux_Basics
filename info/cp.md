


# 📄 cp – Copy Files and Directories

The `cp` command is used to **copy files or directories** from one location to another in Linux/Unix systems.  
It’s commonly used for creating backups or duplicating files.

---

## 📌 Overview

- Copy files within the same directory  
- Copy files to another directory  
- Copy entire directories with all their contents  

---

## ⚙️ Common Examples

| Command | Description |
|---------|-------------|
| `cp file1.txt file2.txt` | Copy `file1.txt` → `file2.txt` |
| `cp file.txt /home/user/` | Copy file into another directory |
| `cp -i file.txt backup.txt` | Prompt before overwrite |
| `cp -v file.txt /tmp/` | Show progress while copying |
| `cp -r folder/ backup/` | Copy directories recursively |
| `cp -u source.txt dest.txt` | Copy only if source is newer than destination |

---

## 🧠 Option Breakdown

| Option | Description |
|--------|-------------|
| `-i` | Ask before overwriting |
| `-v` | Verbose – show what is happening |
| `-r` | Recursive – copy entire directories |
| `-u` | Copy only if source is newer |
| `-p` | Preserve attributes (timestamps, mode, ownership) |

---

## ✅ Use Cases

- 📦 **Backup Important Files**  
  Quickly copy configs, scripts, or documents.  

- 🗂 **Duplicate Project Folders**  
  Copy entire directories with structure intact.  

- 🔄 **Safe Overwrites**  
  Use `-i` to avoid accidental data loss.  

---

💡 *Pro Tip:*  
Use `cp -rp folder newfolder` to **safely copy a directory** while preserving file attributes.


# 📄 cp – Copy Files and Directories

The `cp` command is used to **copy files or directories** from one location to another in Linux/Unix systems.  
It’s commonly used for creating backups or duplicating files.

---

## 📌 Overview

- Copy files within the same directory  
- Copy files to another directory  
- Copy entire directories with all their contents  

---

## ⚙️ Common Examples

| Command | Description |
|---------|-------------|
| `cp file1.txt file2.txt` | Copy `file1.txt` → `file2.txt` |
| `cp file.txt /home/user/` | Copy file into another directory |
| `cp -i file.txt backup.txt` | Prompt before overwrite |
| `cp -v file.txt /tmp/` | Show progress while copying |
| `cp -r folder/ backup/` | Copy directories recursively |
| `cp -u source.txt dest.txt` | Copy only if source is newer than destination |

---

## 🧠 Option Breakdown

| Option | Description |
|--------|-------------|
| `-i` | Ask before overwriting |
| `-v` | Verbose – show what is happening |
| `-r` | Recursive – copy entire directories |
| `-u` | Copy only if source is newer |
| `-p` | Preserve attributes (timestamps, mode, ownership) |

---

## ✅ Use Cases

- 📦 **Backup Important Files**  
  Quickly copy configs, scripts, or documents.  

- 🗂 **Duplicate Project Folders**  
  Copy entire directories with structure intact.  

- 🔄 **Safe Overwrites**  
  Use `-i` to avoid accidental data loss.  

---

💡 *Pro Tip:*  
Use `cp -rp folder newfolder` to **safely copy a directory** while preserving file attributes.

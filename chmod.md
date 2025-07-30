# 🔐 chmod – Change File Permissions

The `chmod` command (short for **change mode**) is used in Linux to **modify the permissions** of files and directories. Permissions determine who can **read**, **write**, or **execute** a file. This command is critical for system security and user access control.

---

## 📌 Overview

Every file in Linux has three types of permissions for three kinds of users:

- **User (u)** – The owner of the file  
- **Group (g)** – Users who are part of the file’s group  
- **Others (o)** – All other users

Each of these can have the following permissions:

- **r** – Read  
- **w** – Write  
- **x** – Execute

Permissions can be modified using **numeric (absolute) mode** or **symbolic mode**.

---

## ⚙️ Common Examples

| Command                         | Description                                                  |
|----------------------------------|--------------------------------------------------------------|
| `chmod 755 file.sh`             | User: rwx, Group: r-x, Others: r-x                           |
| `chmod 644 document.txt`        | User: rw-, Group: r--, Others: r--                           |
| `chmod +x script.sh`            | Adds execute permission to all users                         |
| `chmod u+x file.sh`             | Adds execute permission to the user only                    |
| `chmod g-w file.sh`             | Removes write permission from the group                     |
| `chmod o=r file.sh`             | Sets read-only permission for others                        |

---

## 🧠 Symbolic Mode Breakdown

Symbolic mode uses letters and symbols to describe changes:

- **Users**:  
  - `u` – user  
  - `g` – group  
  - `o` – others  
  - `a` – all (user + group + others)

- **Operators**:  
  - `+` – adds a permission  
  - `-` – removes a permission  
  - `=` – sets the exact permission

- **Permissions**:  
  - `r` – read  
  - `w` – write  
  - `x` – execute

### 🔧 Example:
```bash
chmod g+wx file.txt

# 🔐 chmod – Change File Permissions

The `chmod` command is used to **change the access permissions** of files and directories in Unix/Linux systems. It's essential for controlling who can **read, write, or execute** a file.

---

## 📌 Overview

`chmod` stands for **"change mode"**. It modifies the **permission bits** of a file or directory using either **symbolic notation** (like `u+x`) or **octal values** (like `755`).

Each file in Linux has three permission types for three user categories:

- **User (u)** – owner
- **Group (g)** – group members
- **Others (o)** – everyone else

Permissions:
- `r` – read
- `w` – write
- `x` – execute

---

## ⚙️ Common Examples

| Command               | Description                                          |
|-----------------------|------------------------------------------------------|
| `chmod +x script.sh` | Make `script.sh` executable for everyone              |
| `chmod u+x file`     | Add execute permission for the user only             |
| `chmod 755 file`     | Set rwxr-xr-x (User: all, Group: read-exec, Others: read-exec) |
| `chmod 644 file`     | Set rw-r--r-- (User: read-write, Group/Others: read) |
| `chmod -R 755 dir/`  | Recursively set permissions for directory and its contents |

---

## 🧠 Symbolic Mode Breakdown

| Symbol | Meaning                              | Example              | Result                                           |
|--------|--------------------------------------|----------------------|--------------------------------------------------|
| `u`    | user (owner)                         | `chmod u+x file`     | Adds execute permission for user                |
| `g`    | group                                | `chmod g-w file`     | Removes write permission from group             |
| `o`    | others                               | `chmod o=r file`     | Sets others' permission to read-only            |
| `a`    | all (user + group + others)          | `chmod a+x script`   | Adds execute permission to everyone             |
| `+`    | add permission                       | `chmod +x file`      | Adds execute permission to all                  |
| `-`    | remove permission                    | `chmod -w file`      | Removes write permission from all               |
| `=`    | set exact permission                 | `chmod u=r file`     | Sets user permission to read-only               |

---

## ✅ Use Cases

- 🛡️ **Securing Scripts**  
  Use `chmod 700 script.sh` to make scripts private (only owner can run).

- 👥 **Sharing Files Safely**  
  Use `chmod 644` to allow others to read but not modify your files.

- 🗃️ **Directory Permissions**  
  Use `chmod 755` on folders so users can access but not alter them.

- 🔄 **Recursive Updates**  
  Use `chmod -R` when applying permission changes to entire directories.

---

💡 *Pro Tip:* Always check existing permissions with `ls -l` before changing them. Combine with `chown` if ownership also needs adjustment.

---

🚀 `chmod` is vital for system security, file sharing, and script management. Mastering it is a must for every Linux user and sysadmin.


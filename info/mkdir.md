# 📂 mkdir – Create Directories  

The `mkdir` command is used to **create new directories (folders)** in Linux.  
It’s a simple yet powerful way to organize files right from the terminal.  

---

## 📌 Overview  

- Creates single or multiple directories  
- Can create nested directories with one command  
- Allows setting permissions at the time of creation  

---

## ⚙️ Common Examples  

| Command                     | Description                                      |
|-----------------------------|--------------------------------------------------|
| `mkdir test`                | Create a directory named `test`                  |
| `mkdir dir1 dir2 dir3`      | Create multiple directories at once              |
| `mkdir -p projects/app/logs`| Create nested directories in one go              |
| `mkdir -m 700 private`      | Create a directory with custom permissions (700) |

---

## 🧠 Key Options  

| Option | Description                                               |
|--------|-----------------------------------------------------------|
| `-p`   | Create parent directories if they don’t exist             |
| `-m`   | Set file mode (permissions) for the directory             |
| `-v`   | Verbose output (shows what is being created)              |

---

## ✅ Use Cases  

- 📦 **Project Setup**  
  `mkdir -p project/{src,bin,docs,tests}`  

- 🔒 **Private Storage**  
  `mkdir -m 700 secrets`  

- ⚡ **Automation**  
  Useful in scripts to create required folder structures.  

---

💡 *Pro Tip:*  
Combine `mkdir -p` with `{}` expansion to create complex folder trees fast!  

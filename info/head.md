# 📄 head – Display the Beginning of a File

The `head` command is used to **view the first few lines** of a file in the terminal.  
By default, it shows the **first 10 lines**, but you can customize the count.

---

## 📌 Overview

`head` is handy for **previewing files** without opening them fully.  
It can:
- Display the top lines of a file
- Preview logs, configs, or big datasets
- Work with multiple files at once

---

## ⚙️ Common Examples

| Command              | Description                                      |
|----------------------|--------------------------------------------------|
| `head file.txt`      | Show the first 10 lines of `file.txt`            |
| `head -n 20 file.txt`| Show the first 20 lines of `file.txt`            |
| `head -c 50 file.txt`| Show the first 50 characters of `file.txt`       |
| `head file1 file2`   | Show the first 10 lines of multiple files        |
| `head -q file1 file2`| Show contents without file headers when multiple |

---

## 🧠 Option Breakdown

| Option | Description                                |
|--------|--------------------------------------------|
| `-n`   | Specify the number of lines to display     |
| `-c`   | Specify the number of bytes (characters)   |
| `-q`   | Suppress file headers in multi-file output |
| `-v`   | Always show file headers                   |

---

## ✅ Use Cases

- 📖 **Preview Large Files**  
  Quickly check the start of big logs or datasets.

- 🔍 **Verify Config Files**  
  Inspect the top lines of config files for headers.

- 📝 **Multi-File Comparison**  
  Look at the beginning of multiple files in sequence.

---

💡 *Pro Tip:*  
Combine with `tail` for a **full file preview**:  
```bash
(head file.txt; echo "..."; tail file.txt)

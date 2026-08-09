# 📄 cat – Concatenate and Display Files

The `cat` command is used to **read**, **concatenate**, and **display** the contents of files directly in the terminal.  
It’s quick and convenient for viewing text files without opening an editor.

---

## 📌 Overview

`cat` stands for **concatenate**.  
It can:
- Display file contents
- Combine multiple files into one
- Create new files from terminal input

---

## ⚙️ Common Examples

| Command              | Description                                          |
|----------------------|------------------------------------------------------|
| `cat file.txt`       | Display contents of `file.txt`                        |
| `cat file1 file2`    | Display contents of multiple files in sequence        |
| `cat file1 > file2`  | Overwrite `file2` with the contents of `file1`         |
| `cat file1 >> file2` | Append the contents of `file1` to `file2`              |
| `cat > newfile.txt`  | Create a new file and write to it (Ctrl+D to save)     |
| `cat -n file.txt`    | Display file contents with line numbers                |

---

## 🧠 Option Breakdown

| Option | Description                            |
|--------|----------------------------------------|
| `-n`   | Number all output lines                |
| `-b`   | Number non-empty output lines only     |
| `-E`   | Display `$` at the end of each line    |
| `-s`   | Squeeze multiple blank lines into one  |

---
---
## Examples

```
cat file.txt
```
<img width="1038" height="95" alt="image" src="https://github.com/user-attachments/assets/ab840b60-662f-4cb3-9e11-a39e78f00d2f" />

---
```
cat file1 file2
```
<img width="1136" height="110" alt="image" src="https://github.com/user-attachments/assets/136671e7-c206-4f31-b56a-2837a29d124c" />

---
```
cat file1 > file
```
<img width="1306" height="232" alt="image" src="https://github.com/user-attachments/assets/63c16dd9-0b8e-41ea-89f4-fad104bc1cc2" />

---
```
cat file1 >> file2
```
<img width="1188" height="251" alt="image" src="https://github.com/user-attachments/assets/761ae00c-684a-4b8a-bf99-6d70ce778f06" />

---
```
cat > newfile.txt
```
<img width="1130" height="172" alt="image" src="https://github.com/user-attachments/assets/2630f330-a499-4385-9052-ab07dd660211" />

---
```
cat -n newfile.txt
```
<img width="1194" height="135" alt="image" src="https://github.com/user-attachments/assets/62f35804-0267-4d23-8256-c2ad581d0dcf" />

---

## ✅ Use Cases

- 📖 **Quickly Viewing Files**  
  Display contents of scripts, logs, or configuration files.

- 📝 **Creating Files from Terminal**  
  Use `cat > filename` to make a file without an editor.

- 📦 **Merging Files**  
  Combine multiple files into a single file easily.

---

💡 *Pro Tip:*  
Use `cat file.txt | less` for smooth scrolling through large files.


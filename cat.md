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

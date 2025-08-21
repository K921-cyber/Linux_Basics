
# 🔍 grep – Search Text Using Patterns

The `grep` command stands for **Global Regular Expression Print**. It is used to **search for specific patterns or strings** within files or output streams.

---

## 📌 Overview

`grep` scans through files or input and prints lines that match a given pattern. It supports regular expressions, making it a powerful tool for pattern matching.

---

## ⚙️ Common Examples

| Command                                  | Description                                              |
|------------------------------------------|----------------------------------------------------------|
| `grep "hello" file.txt`                 | Finds lines containing "hello" in `file.txt`             |
| `grep -i "hello" file.txt`              | Case-insensitive search                                  |
| `grep -r "main()" ./src`                | Recursively searches for "main()" in the `src` directory |
| `grep -v "error" logfile.log`           | Show lines that do **not** contain "error"               |
| `grep -n "root" /etc/passwd`            | Show line numbers along with matches                     |
| `ps aux | grep nginx`                   | Find `nginx` process using pipeline                      |

---

## 🧠 Option Breakdown

| Option | Meaning                        |
|--------|--------------------------------|
| `-i`   | Ignore case distinctions       |
| `-v`   | Invert match                   |
| `-r`   | Recursive search               |
| `-n`   | Show line numbers              |
| `-l`   | Print only names of matching files |
| `-e`   | Use multiple patterns          |

---

---
## Example

---

## ✅ Use Cases

- 🧪 **Log File Analysis**  
  Identify error messages or keywords in massive logs.

- 📂 **Codebase Searching**  
  Quickly locate functions, variables, or syntax patterns.

- 🔐 **Security Audits**  
  Search sensitive strings (e.g., passwords, keys) across files.

- 🧼 **Filter Output**  
  Combine with `ps`, `netstat`, or `ls` to refine results.

---

📎 *Note:* Combine with `awk`, `sed`, or `cut` for advanced filtering power.

---


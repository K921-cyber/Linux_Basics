
# 🔢 wc – Word, Line, and Character Count

The `wc` command is used to **count lines, words, characters, and bytes** in a file.  
It’s a quick way to measure the size and structure of text files.

---

## 📌 Overview

`wc` stands for **word count**, but it does much more. It can:
- Count the number of **lines**
- Count the number of **words**
- Count the number of **characters/bytes**
- Work on multiple files at once

---

## ⚙️ Common Examples

| Command                | Description                                  |
|------------------------|----------------------------------------------|
| `wc file.txt`          | Show lines, words, and characters in `file.txt` |
| `wc -l file.txt`       | Count only the lines                        |
| `wc -w file.txt`       | Count only the words                        |
| `wc -c file.txt`       | Count the bytes (file size in bytes)        |
| `wc -m file.txt`       | Count the characters                        |
| `wc file1 file2`       | Show counts for multiple files              |

---

## 🧠 Option Breakdown

| Option | Description                        |
|--------|------------------------------------|
| `-l`   | Count lines only                   |
| `-w`   | Count words only                   |
| `-c`   | Count bytes (file size in bytes)   |
| `-m`   | Count characters (Unicode-aware)   |
| `-L`   | Show length of the longest line    |

---

## ✅ Use Cases

- 📊 **Measure Text Files**  
  Get quick statistics on documents or logs.  

- 📝 **Word Counts**  
  Useful for checking essay or code documentation lengths.  

- ⚡ **Log Analysis**  
  Count the number of lines in large log files.  

---

💡 *Pro Tip:*  
Combine with `cat` or `grep` for advanced usage:  
```bash
grep "error" log.txt | wc -l

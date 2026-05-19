

# 📄 file – Identify File Type

The `file` command is used to **determine the type of a file** in Linux/Unix.  
Instead of just looking at the extension, it checks the file’s **content (magic numbers, headers, etc.)** to identify what it really is.

---

## 📌 Overview

- Detects file type regardless of extension  
- Works with text, binaries, executables, images, compressed files, etc.  
- Useful for analyzing unknown files  

---

## ⚙️ Common Examples

| Command | Description |
|---------|-------------|
| `file document.txt` | Shows if it’s ASCII text, UTF-8 text, etc. |
| `file image.jpg` | Detects if it’s a JPEG image |
| `file program` | Identifies if it’s an ELF binary, script, or executable |
| `file archive.zip` | Identifies the compression format |
| `file *` | Runs `file` on all files in the current directory |

---

## 🧠 Output Examples

```bash
$ file report.pdf
report.pdf: PDF document, version 1.7

$ file image.png
image.png: PNG image data, 800 x 600, 8-bit colormap, non-interlaced

$ file script.sh
script.sh: Bourne-Again shell script, ASCII text executable


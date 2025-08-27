# ✏️ nano – Simple Text Editor in Terminal  

The `nano` command opens a **terminal-based text editor** that’s beginner-friendly.  
It’s often used to quickly edit configuration files, scripts, or notes directly from the terminal.  

---

## 📌 Overview  

- Easy-to-use command-line editor  
- Built into most Linux distributions  
- Shows shortcut keys at the bottom for guidance  

---

## ⚙️ Common Examples  

| Command                | Description                                |
|------------------------|--------------------------------------------|
| `nano file.txt`        | Open (or create) `file.txt` for editing    |
| `nano /etc/hosts`      | Edit the system hosts file (need sudo)     |
| `nano -B notes.txt`    | Open file and create a backup automatically|
| `nano +15 script.sh`   | Open `script.sh` and jump to line 15       |

---

## 🧠 Key Shortcuts  

| Shortcut      | Action                                |
|---------------|----------------------------------------|
| `Ctrl + O`    | Write (save) changes                   |
| `Ctrl + X`    | Exit nano                              |
| `Ctrl + W`    | Search inside the file                 |
| `Ctrl + K`    | Cut the current line                   |
| `Ctrl + U`    | Paste (after cutting)                  |
| `Ctrl + G`    | Help menu                              |

---

## ✅ Use Cases  

- ✍️ **Editing Config Files**  
  Example: `nano /etc/ssh/sshd_config`  

- 📝 **Quick Notes**  
  Create notes without needing GUI editors.  

- 💻 **Scripting**  
  Edit and save bash scripts on the fly.  

---

💡 *Pro Tip:*  
If you mess up, press `Ctrl + C` to cancel actions or `Ctrl + Z` to suspend nano.  

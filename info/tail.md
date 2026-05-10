# 🔻 tail – Display the Last Lines of a File  

The `tail` command is used to **view the last part of files** directly from the terminal.  
It’s especially useful for monitoring logs or checking the most recent updates in files.  

---

## 📌 Overview  

- Displays the **last 10 lines by default**  
- Can follow a file in real time  
- Handy for debugging and monitoring logs  

---

## ⚙️ Common Examples  

| Command              | Description                                              |
|----------------------|----------------------------------------------------------|
| `tail file.txt`      | Show the last 10 lines of `file.txt`                     |
| `tail -n 20 file.txt`| Show the last 20 lines of `file.txt`                     |
| `tail -f file.txt`   | Continuously monitor new lines added to `file.txt`       |
| `tail -c 50 file.txt`| Show the last 50 **bytes** of `file.txt`                 |
| `tail -n +5 file.txt`| Show file contents starting from line 5                  |

---

## 🧠 Option Breakdown  

| Option  | Description                                     |
|---------|-------------------------------------------------|
| `-n N`  | Show the last **N lines** of a file             |
| `-c N`  | Show the last **N bytes** of a file             |
| `-f`    | Keep following the file as it grows (live view) |
| `-q`    | Suppress file headers when viewing multiple     |

---

## ✅ Use Cases  

- 📖 **Log Monitoring**  
  Track system or application logs live using `tail -f`.  

- 🐞 **Debugging**  
  See the most recent output/errors without opening the whole file.  

- 📊 **Data Analysis**  
  Quickly inspect the bottom portion of large datasets or reports.  

---

💡 *Pro Tip:* Combine with `grep` → `tail -f file.log | grep "ERROR"` to monitor logs for errors in real time.  

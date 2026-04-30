# 🔎 free – Memory Usage  

The `free` command is used to **check RAM and swap memory usage** on your system.  
It shows how much memory is available, used, free, and cached.  

---

## 📌 Overview  

- Displays system memory usage (RAM + Swap)  
- Helps monitor system performance  
- Can show results in human-readable format (MB/GB)  

---

## ⚙️ Common Examples  

| Command     | Description                                    |
|-------------|------------------------------------------------|
| `free`      | Show memory usage in KB                       |
| `free -h`   | Human-readable format (MB, GB)                |
| `free -m`   | Show output in MB                             |
| `free -g`   | Show output in GB                             |
| `watch free -h` | Continuously monitor memory in real-time  |

---

## 🧠 Output Example  

```bash
              total        used        free      shared  buff/cache   available
Mem:           16Gi        8Gi        2Gi       500Mi         6Gi         7Gi
Swap:           2Gi       512Mi       1.5Gi


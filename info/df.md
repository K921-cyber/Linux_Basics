# 📦 df – Disk Space Usage  

The `df` command is used to **check disk space usage** on mounted filesystems.  
It shows available, used, and total space in your storage devices.  

---

## 📌 Overview  

- Displays disk usage of all mounted partitions  
- Helps monitor storage capacity  
- Can show output in human-readable format (MB/GB)  

---

## ⚙️ Common Examples  

| Command       | Description                                   |
|---------------|-----------------------------------------------|
| `df`          | Show disk usage in 1K blocks                 |
| `df -h`       | Human-readable format (MB, GB)               |
| `df -T`       | Show filesystem type along with usage         |
| `df -i`       | Show inode usage instead of block usage       |
| `df -h /home` | Check space usage of `/home` specifically     |

---

## 🧠 Output Example  

```bash
Filesystem      Size  Used Avail Use% Mounted on
/dev/sda1       100G   40G   55G  42% /
tmpfs           2.0G  4.0M  2.0G   1% /run
/dev/sdb1       500G  300G  200G  60% /data

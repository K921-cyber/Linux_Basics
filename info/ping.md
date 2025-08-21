
# 🌐 ping – Test Network Connectivity

The `ping` command is used to **check connectivity** between your machine and another host (IP address or domain).  
It works by sending ICMP Echo Request packets and waiting for Echo Replies.

---

## 📌 Overview

- Test if a host is **reachable**  
- Measure **latency (response time)**  
- Diagnose **network issues**  

---

## ⚙️ Common Examples

| Command | Description |
|---------|-------------|
| `ping google.com` | Ping Google’s servers to test internet connectivity |
| `ping -c 4 8.8.8.8` | Send exactly **4 packets** to Google DNS |
| `ping -i 2 example.com` | Send ping every **2 seconds** |
| `ping -s 1000 host` | Send packets of **1000 bytes** (default is 56 bytes) |
| `ping -t 192.168.1.1` (Windows) | Ping continuously until stopped (Ctrl+C) |

---

## 🧠 Output Example

```bash
$ ping -c 4 google.com
PING google.com (142.250.192.206): 56 data bytes
64 bytes from 142.250.192.206: icmp_seq=0 ttl=118 time=23.4 ms
64 bytes from 142.250.192.206: icmp_seq=1 ttl=118 time=22.9 ms
64 bytes from 142.250.192.206: icmp_seq=2 ttl=118 time=23.1 ms
64 bytes from 142.250.192.206: icmp_seq=3 ttl=118 time=23.0 ms

--- google.com ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3003ms
rtt min/avg/max/mdev = 22.9/23.1/23.4/0.2 ms

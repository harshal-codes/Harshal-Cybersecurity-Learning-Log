# 🌐 Networking & Linux Basics Revision Log
### 📅 Date: 2025-03-06
---

## 🧵 **Networking Basics Revision**

### 1️⃣ OSI Model Summary
| Layer | Name | Function |
|---|---|---|
| 7 | Application | End-user interaction (HTTP, FTP) |
| 6 | Presentation | Data formatting & encryption (SSL/TLS) |
| 5 | Session | Start/Stop communication sessions |
| 4 | Transport | Reliable delivery (TCP/UDP) |
| 3 | Network | Routing (IP Addresses, Routers) |
| 2 | Data Link | Framing, MAC Address, Switches |
| 1 | Physical | Hardware transmission (Cables, Wi-Fi) |

### 2️⃣ TCP/IP Model Summary
| Layer | Name | Example Protocols |
|---|---|---|
| 4 | Application | HTTP, FTP, DNS, SSH |
| 3 | Transport | TCP, UDP |
| 2 | Internet | IP, ICMP |
| 1 | Network Access | Ethernet, Wi-Fi |

---

### 3️⃣ Key Protocols Revised
| Protocol | Purpose |
|---|---|
| **HTTP** | Web communication |
| **DNS** | Domain name to IP resolution |
| **SSH** | Secure remote access |
| **FTP** | File transfer |
| **DHCP** | IP assignment |
| **ICMP** | Error reporting (ping) |
| **HTTPS** | Secure web communication |

---

### 📝 Personal Notes
- OSI helps in understanding how data flows between devices.
- TCP/IP is practical, as it's the actual model used on the internet.
- Protocols like DNS, HTTP, and SSH are critical in **both web development & cybersecurity**.
- DNS poisoning and SSH brute force are common attacks.

---

## 🐧 Linux Basics Practice

### 1️⃣ File & Permission Commands
| Command | Description |
|---|---|
| `ls -al` | List files with permissions |
| `chmod 644 file.txt` | Set read/write for owner, read-only for group & others |
| `chown user:group file.txt` | Change file ownership |

---

### 2️⃣ File Search & System Navigation
| Command | Description |
|---|---|
| `find / -name "*.conf"` | Find all .conf files |
| `pwd` | Show current directory |
| `cat /etc/os-release` | Display Linux distro info |

---

### 3️⃣ Networking Commands Practiced
| Command | Purpose |
|---|---|
| `ping google.com` | Test network connectivity |
| `netstat -tuln` | Show active ports/services |
| `ip a` | Show IP addresses (alternative to `ifconfig`) |
| `traceroute google.com` | Show path to target host |
| `nslookup google.com` | DNS lookup for domain |
| `curl ifconfig.me` | Show public IP address |

---

### 🔐 Personal Notes
- Networking commands help during **pentesting & troubleshooting**.
- Learning `netstat` and `ip a` is essential for **host discovery**.
- `find` and `chmod` are useful in **file forensics & securing files**.

---

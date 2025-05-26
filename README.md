# Cyber Security Internship - Task 1

## 🔍 Task: Scan Your Local Network for Open Ports

### Objective
To discover open ports on devices in my local network using Nmap and understand network exposure and associated security risks.

---

## 🛠 Tools Used
- **Nmap** for network scanning
- *(Optional)* Wireshark for packet inspection

---

## 🔗 IP Range Used
- `192.168.1.0/24` *(Replace with your actual range)*

---

## 🧪 Command Used
```bash
nmap -sS 192.168.1.0/24 -oN scan_result.txt

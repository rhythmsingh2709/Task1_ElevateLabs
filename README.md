# Task 1 — Port Scanning & Network Reconnaissance

This repository contains my work for **Task 1 of the Cyber Security Internship**.  
The objective was to use **Nmap** to scan the local network, discover active hosts, identify open ports, and analyze exposed services. This helps understand how network reconnaissance is performed and what risks open ports pose.

---

## 🔧 Tools Used
- **Nmap** — network scanning tool
- **ifconfig** — to identify the local IP range


---

## 📜 Commands Used


# Install nmap
sudo apt update && sudo apt install nmap -y

# Find local IP range
ifconfig

# Perform SYN scan with service & OS detection
sudo nmap -sS -sV -O -T4 192.168.1.0/24

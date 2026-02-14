# Nmap Network Scanning Lab

## 📌 Project Title
TCP SYN Scan using Nmap

## 🎯 Objective
To perform network scanning using Nmap and identify active hosts and open ports in a local network.

## 🛠 Tools Used
- Nmap
- Command Prompt (Windows)
- Wireshark (optional for packet analysis)

## 🖥 System Used
- Windows OS
- Local IP Range: 192.168.0.0/24

## 📋 Tasks Performed
1. Installed Nmap from official website.
2. Identified local IP address using `ipconfig`.
3. Performed TCP SYN scan using:
   nmap -sS 192.168.0.0/24
4. Identified active hosts and open ports.
5. Saved scan results as text file.
6. (Optional) Analyzed SYN packets using Wireshark.

## 🔎 Sample Command Used
nmap -sS 192.168.0.0/24 -oN nmap_scan.txt

## 📊 Output Observations
- Active devices detected on local network.
- Open ports such as 80 (HTTP), 443 (HTTPS), and 22 (SSH) identified.
- Closed and filtered ports were also observed.

## ⚠ Security Observations
- Open ports increase attack surface.
- Unnecessary services should be disabled.
- Firewall configuration is important.

## 📚 Learning Outcome
- Understood TCP SYN scanning technique.
- Learned how to detect open ports.
- Gained basic knowledge of network security assessment.

## 👤 Author
Yashpreet Saxena

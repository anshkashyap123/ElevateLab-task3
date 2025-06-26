# ElevateLab-task3

# 🔍 Nmap Full Vulnerability Scan

This project contains the results of a full vulnerability scan performed on the IP address `192.168.1.72` using **Nmap** and its `vuln` script engine.

---

## 📌 Scan Details

- **Date:** June 26, 2025  
- **Tool:** [Nmap](https://nmap.org/)  
- **Target:** `192.168.1.72`  
- **Command Used:**

```bash
nmap -p- -T4 -A -v --script vuln 192.168.1.72

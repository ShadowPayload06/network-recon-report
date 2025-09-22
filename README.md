🔍 Nmap Network Recon & Security Analysis

This repository documents a basic network reconnaissance and vulnerability assessment workflow using **Nmap** and **Wireshark**. It was created as part of an internship project focused on identifying open ports, analyzing services, and evaluating potential security risks in a local network.
---
# 📁 Files Included

- `scan_nmap.txt` – Raw Nmap scan output (TCP SYN scan)
- `scan_results.txt` – Saved scan results in text format
- `Nmap Service Analysis.txt` – Detailed breakdown of services running on open ports
- `Potential Security Risks.txt` – Risk assessment and mitigation recommendations
---
# 🧪 Workflow Summary
# Step-by-Step Process:
1. **Install Nmap** from [official site](https://nmap.org)
2. **Identify local IP range** (e.g., `192.168.1.0/24`)
3. **Run TCP SYN scan**:  
   ```bash
   nmap -sS 192.168.1.0/24

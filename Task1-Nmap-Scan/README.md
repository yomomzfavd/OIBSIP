Nmap Network Scan on Vulnerable Windows Machine

Objective
To scan a vulnerable Windows machine using **Nmap** in order to identify open ports and services that could be exploited in a real-world scenario.



Tools Used
- Nmap (v7.94)
- Host OS: Windows 10 Vulnerable VM
- Scan executed on: Kali Linux

  Target Details
- **Target IP Address: 192.168.1.102
- **Target System: Vulnerable Windows VM (Win7)

---

Nmap Scan Commands Used

```bash
nmap 192.168.1.102
nmap -vS 192.168.1.102
nmap -sV 192.168.1.102 -oN nmap_scan_results.txt

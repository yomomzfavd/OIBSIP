# Task 7: Vulnerability Scanning with Nikto

## Objective
The goal of this task was to perform a basic vulnerability scan on a web server using **Nikto**, a widely used open-source web server scanner. The aim was to identify potential security issues such as misconfigurations, outdated software, and common vulnerabilities.

## Tools
- **Nikto** (installed on Kali Linux)

## Steps
1. Installed Nikto on Kali (it comes preinstalled in most versions).
2. Ran the following command to scan the target web server:
   ```bash
   nikto -h http://<192.168.1.101> -output nikto_scan_results.txt

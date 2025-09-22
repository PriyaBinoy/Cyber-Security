Network Scan Report – Task 1

Scan Date: 22 Sep 2025
Network Range: 192.168.1.0/24
Scan Type: TCP SYN scan (nmap -sS)
Scan File: nmap_scan_results.txt

Hosts & Open Ports

192.168.1.1

Open/Filtered: 21 (FTP), 22 (SSH filtered), 23 (Telnet filtered), 53 (DNS), 80 (HTTP), 443 (HTTPS)

Notes/Risks: FTP can be insecure; default web interfaces should have strong passwords; check SSH/Telnet access policies.

192.168.1.6

No open ports detected

Notes/Risks: Low risk

192.168.1.9

No open ports detected

Notes/Risks: Low risk

192.168.1.8

Open: 135 (MSRPC), 139 (NetBIOS-SSN), 445 (Microsoft-DS)

Notes/Risks: SMB ports could be exploited for unauthorized access or ransomware; restrict to internal network.

Commands Used
nmap -sS 192.168.1.0/24 -oN nmap_scan_results.txt



# Python Port Scanner

A beginner cybersecurity tool built using Python's socket library 
to scan open ports on a target host.

## Features
- Scans a range of TCP ports on any target IP or hostname
- Displays open ports in real time
- Shows scan start time and total open ports found

## Tools & Technologies
- Python 3
- Socket library
- Datetime library

## How to Run
```bash
python port_scanner.py
```
Enter target IP, start port, and end port when prompted.

## Example Output
```
==================================================
Scanning Target: 192.168.1.1
Scanning started at: 2026-03-05 10:00:00
==================================================

[OPEN] Port 22
[OPEN] Port 80
[OPEN] Port 443

Scan complete. 3 open ports found.
```

## Legal Disclaimer
This tool is intended for educational purposes only.
Only scan systems you own or have explicit permission to test.

## Author
Vijayarama Mohith Varma | Cybersecurity M.S. | CISSP

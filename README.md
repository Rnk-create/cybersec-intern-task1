# Task 1 — Nmap (plain text only)

This repo contains the Nmap scan results saved as plain text.

Files:
- scan_results.txt : human-readable nmap output
- open_ports.txt   : (optional) extracted lines showing open ports
- observations.txt : notes and recommendations

Command used:
sudo nmap -sS -p- -T4 192.168.1.0/24 -oN scan_results.txt

Note: only scanned devices I own / have permission to scan.

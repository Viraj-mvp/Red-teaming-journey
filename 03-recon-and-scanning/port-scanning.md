
# Port Scanning

## Purpose

Identify open ports (entry points)

---

## Full Scan

```bash
nmap -sS -p- 192.168.100.10

TCP Connect Scan
nmap -sT -p- 192.168.100.10
States
State	Meaning
Open	Service available
Closed	Service exists but not accessible
Filtered	Firewall blocking
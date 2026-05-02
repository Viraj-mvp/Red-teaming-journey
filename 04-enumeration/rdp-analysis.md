RDP Analysis



\## Target Port



3389 (RDP)



\---



\## Check Availability



bash

nmap -p 3389 192.168.100.10



Connect

xfreerdp /v:192.168.100.10



Attack Possibilities



* Weak passwords
* Credential reuse
* Brute force



Key Insight



\-RDP is a high-value target for gaining full system access


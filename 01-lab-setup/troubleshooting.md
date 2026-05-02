\# Troubleshooting Notes



\## Issue: All Ports Closed in Nmap



\### Symptoms



\* Nmap shows all ports closed

\* Services confirmed running via netstat



\### Root Cause



\* Windows Firewall (Domain Profile) still active

\* Network categorized incorrectly



\### Fix



\* Disable firewall via:



```

netsh advfirewall set allprofiles state off

```



\* Set network to Private:



```

Set-NetConnectionProfile -NetworkCategory Private

```



\---



\## Key Insight



"Closed ports do not always mean no services—often they indicate filtering."




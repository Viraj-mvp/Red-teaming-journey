\# Network Architecture



\## Overview



The lab environment uses a dual-network setup:



\* \*\*NAT Network\*\*



&#x20; \* Provides internet access

&#x20; \* Used for updates and tool installation



\* \*\*Host-only Network\*\*



&#x20; \* Internal isolated network

&#x20; \* Used for attacker-target communication



\---



\## Configuration



\### Kali Linux



\* eth0 → NAT → 192.168.59.x

\* eth1 → Host-only → 192.168.100.x



\### Windows 10



\* Adapter 1 → NAT

\* Adapter 2 → Host-only



\---



\## Connectivity Verification



From Kali:



```

ping 192.168.100.10

```



Expected:



\* Successful ICMP responses

\* Low latency



\---



\## Key Learning



\* Network segmentation is critical

\* Internal networks are primary targets in real engagements




# Networking Basics (Attacker Perspective)

## Key Concepts

### IP Addressing
- Identifies devices on a network
- Example:
  - 192.168.100.10 (target)
  - 192.168.100.128 (attacker)

### Subnet
- Defines network boundaries
- Same subnet → direct communication

Example:
192.168.100.0/24

---

## Important Ports

| Port | Service | Relevance |
|------|--------|----------|
| 80   | HTTP   | Web attacks |
| 443  | HTTPS  | Secure web |
| 445  | SMB    | File sharing, lateral movement |
| 139  | NetBIOS| Legacy Windows |
| 3389 | RDP    | Remote access |
| 135  | RPC    | Windows communication |

---

## Protocols

- TCP → Reliable communication
- UDP → Faster, no guarantee
- ICMP → Used for ping

---

## Attacker Thinking

Open port = Entry point

Example:
Port 445 → SMB → Enumerate shares → Extract users → Gain access

---

## Key Insight

Understanding network behavior is more important than running tools.
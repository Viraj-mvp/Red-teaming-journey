# SMB Enumeration

## Target Port

445 (SMB)

---

## Commands

### List shares

```bash
smbclient -L //192.168.100.10 -N
Enum with enum4linux
enum4linux 192.168.100.10
What to Look For
Shared folders
Usernames
Permissions
Attack Path

SMB → Users → Passwords → Access

Key Insight

SMB is one of the most common entry points in Windows environments
# Villain Framework Reverse Shell Report

## ⚙️ Setup Info
- Payload: `windows/reverse_tcp/powershell`
- LHOST: 192.168.56.1
- LPORT: 4444

## 🔁 Payload Delivery Method
- The generated PowerShell payload was transferred to the target Windows 10 VM and executed through a local PowerShell console.
Upon execution, the payload established a reverse TCP connection back to the attacker's Kali Linux machine running Villain.

## 🖥️ Captured Info
- Hostname: KRISHNA
- IP Address: 192.168.56.101
- User: _value_

## 🔎 Enumeration Performed
```powershell
whoami
ipconfig
systeminfo
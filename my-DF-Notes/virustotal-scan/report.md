# VirusTotal Analysis Report

## 📁 File Info
- Filename: infected.zip
- File inside: 	0264b1aac95de6398f0c7d469beb5697ea4a9872d7254c9a63cf95294f1414ee
- Hashes:
  - MD5: 
        f1fd4cf59c5cfb5e4ab5fd8570889fdb
  - SHA1: 48543fec63c090153308892c3cdfc411979c4b45
  - SHA256: 
ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1

## 🧪 Detection
| **Engine**                                  | **Detection Name**               |
| ------------------------------------------- | -------------------------------- |
| Microsoft                                   | Trojan\:Win32/Egairtigado!rfn    |
| Kaspersky                                   | HEUR\:Trojan.MSIL.Taskun.gen     |
| ESET-NOD32                                  | A Variant Of MSIL/Kryptik.AOBM   |
| Fortinet                                    | MSIL/Formbook.HDZY!tr            |
| TrendMicro                                  | TrojanSpy.Win32.NEGASTEAL.YXFG5Z |
| Avast / AVG                                 | Win32\:MalwareX-gen \[Pws]       |
| Sophos                                      | Troj/Krypt-AQM                   |
| Malwarebytes                                | Trojan.MalPack.PNG.Generic       |
| BitDefender / GData / Emsisoft              | Trojan.GenericKDZ.112786         |
| Panda                                       | Trj/Chgt.AD                      |
| Sangfor                                     | Infostealer.Msil.Taskun.Vl0s     |
| DrWeb                                       | Trojan.Packed2.49940             |
|                                  |


## 📡 Network Indicators
No hardcoded domains/IPs shown in static scan

Likely connects to C2 servers for data exfiltration based on family behavior

Uses WMI calls and clipboard monitoring — potential for credential theft

## 📊 Behavioral Summary
-Anti-analysis techniques:

Long sleep delays (sandbox evasion)

Debugger detection

Malicious actions:

Clipboard monitoring (password theft)

WMI-based system reconnaissance

Potential spreading capability

Technical notes:

Compiled in .NET Framework v4.0.30319

Uses Windows Forms and multiple system libraries (System.Data, System.Drawing, System.Core)

## 🗣️ Community Insight
- Community Score: -12 (highly malicious consensus)

Classified as an Infostealer (Taskun/Formbook variant)

## 🔐 Public Link
- https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1/behavior

## 🖼️ Screenshots
Include screenshots of your logged-in VT dashboard and scan results.
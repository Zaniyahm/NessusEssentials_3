# Vulnerability Scan Report (Nessus Essentials)

## 🔧 Tool Used
Nessus Essentials (free edition)

## 🎯 Target
Local machine: 192.168.24.206 (Windows 11)

## 📊 Summary of Findings

| Vulnerability            | Severity | Port |
|--------------------------|----------|------|
| SMB Signing not required | Medium   | 445  |
| OpenSSL outdated         | High     | 443  |
| Oracle listener open     | High     | 1521 |
| MySQL root open access   | Critical | 3306 |
| MSRPC service exposed    | Medium   | 135  |

## 🛡️ Fixes/Mitigations

- **SMB Signing:** Enable SMB signing via Group Policy.
- **OpenSSL:** Update to latest secure version.
- **Oracle Listener:** Secure with firewall & password.
- **MySQL:** Set a strong root password.
- **MSRPC:** Block external access on port 135.

## 📝 What I Did
1. Installed Nessus Essentials.
2. Ran a full system vulnerability scan on local IP.
3. Waited about 30min for scan to complete.
4. Noted critical vulnerabilities.
5. Researched fixes for each issue.
6. Created this summary and fix list.

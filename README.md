# cyber-security-internship-task3
A Basic Vulnerability Scan
Nessus Essentials Vulnerability Assessment Report
Scan Name: My Basic Network Scan
Scanner: Local Scanner
Scan Type: Basic Network Scan
Date: Today
Total Vulnerabilities Detected: 24
Severity Breakdown
- High: 1
- Medium: 2
- Mixed: 2
- Info: 19
High Severity Vulnerabilities
1. Oracle TNS Listener Remote Poisoning
Severity: High (7.3 CVSS)
Family: Databases
Count: 1
Description: This vulnerability allows remote attackers to manipulate the Oracle TNS Listener.
Impact: Unauthorized access, traffic hijacking, database disruption.
Recommendation:
- Upgrade Oracle components
- Restrict listener access
- Apply security patches
Medium Severity Vulnerabilities
2. SMB Signing Not Required
Severity: Medium (5.3 CVSS)
Description: SMB connections not enforced to use signing.
Impact: MITM attacks
Recommendation: Enable SMB signing
3. SSL Certificate Signed Using Weak Hashing Algorithm
Severity: Medium (5.3 CVSS)
Recommendation: Replace with SHA-256 certificate
Mixed Severity
4. SSL (Multiple Issues)
Count: 13
5. TLS (Multiple Issues)
Count: 3
Informational Findings
- SMB, HTTP, SSH, DCE enumeration
Overall Security Posture
Main risks from Oracle Listener, SSL/TLS issues, SMB misconfiguration.
Next Steps
- Patch Oracle
- Fix SMB signing
- Regenerate SSL certs
- Disable outdated TLS versions
- Rescan after fixes

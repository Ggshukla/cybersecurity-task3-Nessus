## Task 3 - Vulnerability Scan using Nessus Essentials

## Tool Used
- Nessus Essentials (Free version by Tenable)

## Target Scanned
- Localhost (127.0.0.1)

## Scan Details
- **Scan Type**: Advanced Scan
- **Start**: Today at 11:06 PM
- **End**: 11:14 PM
- **Duration**: 8 minutes
- **Severity Base**: CVSS v3.0

## Vulnerability Summary
- Critical: 0
- High: 0
- Medium: 1
- Low: 0
- Info: 21
- Total: 22 vulnerabilities

## Notable Finding
## SMB Signing not required (Medium - CVSS 5.3)
- **Description**: SMB signing is not enforced, which may allow man-in-the-middle attacks.
- **Fix**: Enable SMB signing via Group Policy or Registry Editor in Windows.

## SSL & SMB Multiple Issues (Mixed & Informational)
- Multiple insecure protocols and legacy services were detected.
- These are usually safe to ignore on localhost but may be risky on open networks.

## Report Files
- `screenshots/scan-summary.png`
- `screenshots/smb-vulnerability.png`
- `nessus-report.pdf` *(if exported)*

## Screenshots
See the `/screenshots/` folder in this repository for detailed visuals.

---

## ✅ Key Learnings
- Hands-on use of a real-world security scanner
- Understanding CVSS, risk classification, and vulnerability descriptions
- Basics of system-level misconfigurations


# Methodology

## 1. Assessment Planning
The audit scope was defined around enterprise security controls, including authentication, access rights, patch management, logging, network administration, web server configuration, and Linux system hardening.

## 2. Windows and Active Directory Review
Windows domain controllers were reviewed for:
- Password policy strength
- Account lockout configuration
- Built-in Administrator account naming
- Domain Admin membership
- Enterprise Admin membership
- Schema Admin membership
- Windows LAN Manager and NetBIOS-related settings
- Patch management practices

## 3. Linux Server Review
The Ubuntu support server was reviewed for:
- Patch management
- Sudo group membership
- File and directory permissions
- Running services and unnecessary daemons
- SSH configuration
- Host-based firewall configuration

## 4. Web Server Review
Web server configuration was reviewed for:
- TLS/SSL availability
- HTTP versus HTTPS exposure
- Default IIS files
- Directory browsing
- Web service hardening

## 5. Logging and Monitoring Review
Logging controls were reviewed by examining:
- Windows Security, System, and Application logs
- Audit policy configuration
- Local log retention
- Centralized logging gaps
- Alerting limitations

## 6. Risk Rating
Each finding was assigned a risk rating based on potential impact, exploitability, and remediation effort. Ratings were organized as Critical, High, Medium, Low, or Informational.

## 7. Remediation Planning
Each observation was paired with practical remediation recommendations, including configuration changes, access control improvements, hardening steps, and monitoring improvements.

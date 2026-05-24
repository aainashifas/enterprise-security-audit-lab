# Findings Summary

## Authentication and Password Security
The audit identified weak password controls, insufficient account lockout settings, and legacy authentication exposure. These weaknesses increase the risk of brute-force attacks, credential theft, and unauthorized access.

## Active Directory Privilege Management
Privileged groups contained more accounts than necessary. Excessive Domain Admin and Enterprise Admin membership increases the impact of account compromise and violates the principle of least privilege.

## Patch Management
The assessment found inconsistent patching practices across Windows and Linux systems. Missing or delayed updates increase exposure to known vulnerabilities.

## Linux System Hardening
The Ubuntu support server had several hardening gaps, including unnecessary services, insecure SSH configuration, broad sudo access, and missing host-based firewall controls.

## Web Server Security
The web server was exposed over HTTP without TLS/SSL protection. Default IIS content was also present, increasing information disclosure and reconnaissance risk.

## Logging and Monitoring
Security, system, and application logs were generated locally, but centralized log forwarding and automated alerting were limited or missing. This reduces visibility during incident detection and response.

## Overall Conclusion
The audit showed that the environment had several common enterprise security weaknesses related to authentication, privilege management, patching, web security, Linux hardening, and monitoring. The strongest remediation priorities are enforcing least privilege, strengthening authentication controls, enabling secure transport, improving patch management, and centralizing logs.

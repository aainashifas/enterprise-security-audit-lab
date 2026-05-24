# Remediation Plan

## Priority 1: Strengthen Authentication Controls
- Disable insecure legacy authentication where possible.
- Enforce stronger password complexity and minimum length requirements.
- Increase account lockout duration to reduce brute-force risk.
- Review authentication protocols and remove unnecessary legacy services.

## Priority 2: Reduce Privileged Access
- Limit Domain Admin and Enterprise Admin membership to only required accounts.
- Remove unnecessary users from privileged groups.
- Conduct recurring privileged access reviews.
- Apply role-based access control where possible.

## Priority 3: Improve Patch Management
- Establish a formal patch management policy.
- Apply critical patches within a defined timeframe.
- Use automated patch management tools where available.
- Track patch deployment and exceptions.

## Priority 4: Harden Linux Systems
- Remove unnecessary sudo access.
- Disable unnecessary daemons and services.
- Configure SSH to disable direct root login.
- Prefer SSH key-based authentication.
- Enable and enforce a host-based firewall such as UFW or iptables.

## Priority 5: Secure Web Services
- Enable HTTPS using a valid TLS certificate.
- Redirect HTTP traffic to HTTPS.
- Remove default IIS files and sample content.
- Apply a web server hardening checklist.

## Priority 6: Improve Logging and Monitoring
- Forward logs to a centralized logging or SIEM platform.
- Configure alerts for suspicious authentication, privilege changes, and service modifications.
- Retain logs according to investigation and compliance needs.
- Regularly review audit policy settings.

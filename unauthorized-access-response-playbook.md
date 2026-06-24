# Unauthorized Access Response Playbook

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  

---

## Overview

This playbook outlines the steps to take when unauthorized access to a system, account, or data is detected or suspected. Unauthorized access includes external attackers, compromised credentials, and insider threats.

---

## Step 1 — Detection and Identification

- Confirm unauthorized access is real and not a false positive
- Identify which systems, accounts, or data were accessed
- Determine how access was gained
- Establish the timeline of access
- Identify what data or systems the attacker touched
- Assign an Incident Lead immediately

**Common indicators:**
- Login from unusual location or device
- Access outside normal working hours
- Multiple failed login attempts followed by success
- Unexpected changes to files, settings, or user accounts
- Alerts from SIEM or intrusion detection system

---

## Step 2 — Containment

- Revoke access for the compromised account immediately
- Force logout all active sessions on affected accounts
- Block the attacker IP address at the firewall
- Disable any backdoor accounts created by the attacker
- Preserve all logs and audit trails as evidence
- Do not alert the attacker that they have been detected

---

## Step 3 — Eradication

- Remove any accounts or access created by the attacker
- Revoke all API keys and tokens that may be compromised
- Scan affected systems for malware or persistence mechanisms
- Review and tighten access controls and permissions
- Patch the vulnerability used to gain access

---

## Step 4 — Recovery

- Restore affected accounts with new credentials and MFA
- Verify integrity of data that was accessed or modified
- Restore any altered files from clean backups
- Monitor affected systems and accounts for 30 days
- Conduct a full access review across all systems

---

## Step 5 — Notification and Reporting

- Notify executive leadership within 24 hours of confirmation
- If personal data was accessed, follow NDPR and GDPR breach notification requirements
- Report to law enforcement if criminal activity is suspected
- Notify affected users if their data was accessed
- Prepare a formal incident report within 7 days

---

## Step 6 — Post-Incident Review

- Conduct a full review within 2 weeks of resolution
- Document how access was gained and what was accessed
- Review privileged access and apply least privilege principles
- Implement additional monitoring on high value systems
- Update this playbook based on findings

---

## Access Control Review Checklist

- [ ] All inactive accounts disabled or removed
- [ ] Privileged access limited to those who need it
- [ ] MFA enabled on all accounts especially admin
- [ ] Login activity monitored and alerted
- [ ] Access reviewed quarterly
- [ ] Offboarding process removes access immediately

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

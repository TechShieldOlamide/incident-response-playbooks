# Ransomware Incident Response Playbook

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  

---

## Overview

This playbook outlines the steps to take when a ransomware attack is detected or suspected. Ransomware encrypts business data and demands payment for restoration. Speed of response is critical to limiting damage.

---

## Step 1 — Detection and Identification

- Confirm ransomware activity — look for encrypted files, ransom notes, unusual system behaviour
- Identify which systems and data are affected
- Determine how the ransomware entered the environment (phishing, RDP, malicious download)
- Log the date and time of discovery
- Assign an Incident Lead immediately
- Do not pay the ransom without legal and executive approval

---

## Step 2 — Containment

- Disconnect affected systems from the network immediately
- Do not shut down affected systems — memory may contain decryption keys
- Disable shared drives and network shares to prevent spread
- Revoke access credentials for affected accounts
- Alert all staff not to open suspicious emails or links
- Isolate backups from the network immediately

---

## Step 3 — Eradication

- Identify the ransomware strain using tools like ID Ransomware (id-ransomware.malwarehunterteam.com)
- Check for available decryption tools at nomoreransom.org
- Remove all malicious files and processes
- Patch the vulnerability used to gain entry
- Audit all user accounts for unauthorized changes

---

## Step 4 — Recovery

- Restore systems from the most recent clean backup
- Verify backup integrity before restoration
- Rebuild systems from scratch if backups are compromised
- Test restored systems thoroughly before bringing back online
- Monitor all systems closely for 7 days post-recovery

---

## Step 5 — Notification and Reporting

- Notify executive leadership immediately upon confirmation
- Report to law enforcement if data was stolen
- If personal data was accessed, follow NDPR and GDPR breach notification requirements
- Notify cyber insurance provider if applicable
- Prepare a formal incident report within 7 days

---

## Step 6 — Post-Incident Review

- Conduct a full review within 2 weeks of resolution
- Document the attack vector, timeline, and impact
- Review and strengthen backup procedures
- Conduct staff phishing awareness training
- Update this playbook based on findings

---

## Prevention Checklist

- [ ] Regular offline backups tested and verified
- [ ] Email filtering and anti-phishing controls in place
- [ ] RDP disabled or protected with MFA
- [ ] Endpoint detection and response tool deployed
- [ ] Staff trained on phishing and social engineering
- [ ] Patch management process in place

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

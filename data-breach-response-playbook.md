# Data Breach Response Playbook

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  

---

## Overview

This playbook outlines the steps to take when a data breach is detected or suspected. It applies to any incident involving unauthorized access to, disclosure of, or loss of personal or sensitive business data.

---

## Step 1 — Detection and Identification

- Confirm the breach is real and not a false positive
- Identify what data was affected and how many records
- Determine the source of the breach
- Log the date and time of discovery
- Assign an Incident Lead immediately

**Questions to answer:**
- What systems were affected?
- What type of data was exposed (PII, financial, credentials)?
- Is the breach ongoing or contained?

---

## Step 2 — Containment

- Isolate affected systems immediately
- Revoke compromised credentials and API keys
- Block suspicious IP addresses at the firewall
- Preserve logs and evidence before making changes
- Notify the IT and security team

**Do not delete any logs or evidence at this stage.**

---

## Step 3 — Eradication

- Identify and remove the root cause
- Patch the vulnerability that was exploited
- Scan for malware or backdoors
- Reset all potentially compromised passwords
- Audit access controls and permissions

---

## Step 4 — Recovery

- Restore affected systems from clean backups
- Verify systems are functioning normally before going live
- Monitor systems closely for 72 hours post-recovery
- Confirm no attacker persistence remains

---

## Step 5 — Notification and Reporting

**NDPR (Nigeria):**
- Report to NITDA within 72 hours of becoming aware
- Notify affected individuals if their data was exposed

**GDPR (EU users):**
- Report to the relevant supervisory authority within 72 hours
- Notify affected data subjects without undue delay if high risk

**Internal reporting:**
- Brief executive leadership within 24 hours
- Prepare a formal incident report within 7 days

---

## Step 6 — Post-Incident Review

- Conduct a full review within 2 weeks of resolution
- Document what happened, what was done, and what failed
- Update security policies and controls based on findings
- Share lessons learned with relevant teams

---

## Severity Levels

| Level | Description | Response Time |
|---|---|---|
| Critical | Large scale breach, regulatory impact | Immediate |
| High | Limited breach, sensitive data exposed | Within 4 hours |
| Medium | Potential exposure, under investigation | Within 24 hours |
| Low | No confirmed exposure, precautionary | Within 72 hours |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

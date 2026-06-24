# Phishing Attack Response Playbook

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  

---

## Overview

This playbook outlines the steps to take when a phishing attack is detected or reported. Phishing attacks trick staff into revealing credentials, clicking malicious links, or transferring funds. They are the most common entry point for larger attacks.

---

## Step 1 — Detection and Identification

- Confirm the phishing attempt is real
- Identify how many staff received the email
- Determine if anyone clicked the link or provided credentials
- Identify the sender domain and phishing infrastructure
- Log the date and time of discovery
- Assign an Incident Lead immediately

**Common indicators:**
- Urgent requests for credentials or payments
- Sender domain slightly different from legitimate domain
- Links pointing to unfamiliar or misspelled domains
- Unexpected attachments

---

## Step 2 — Containment

- Block the phishing sender domain at the email gateway
- Remove the phishing email from all inboxes immediately
- Reset credentials for any staff who clicked or responded
- Enable MFA on all affected accounts immediately
- Notify all staff about the phishing attempt
- Preserve the original email as evidence

---

## Step 3 — Eradication

- Scan affected systems for malware
- Review email gateway logs for similar messages
- Check for any unauthorized account activity
- Revoke any active sessions on compromised accounts
- Review and update email filtering rules

---

## Step 4 — Recovery

- Restore access for affected staff with new credentials
- Verify no unauthorized changes were made to accounts or systems
- Monitor affected accounts closely for 30 days
- Confirm no data was exfiltrated

---

## Step 5 — Notification and Reporting

- Notify executive leadership if credentials or data were compromised
- If personal data was accessed, follow NDPR and GDPR breach notification requirements
- Report sophisticated or targeted attacks to relevant authorities
- Prepare a formal incident report within 7 days

---

## Step 6 — Post-Incident Review

- Conduct a full review within 2 weeks
- Identify why the phishing email bypassed existing controls
- Run a phishing simulation within 30 days to test staff awareness
- Update email filtering and security awareness training
- Update this playbook based on findings

---

## Phishing Reporting Process for Staff

1. Do not click any links or download attachments
2. Report the email to the security team immediately
3. Do not delete the email until instructed
4. If you clicked a link, report it immediately — no judgment
5. Change your password immediately if you entered credentials

---

## Prevention Checklist

- [ ] Email filtering with anti-phishing controls enabled
- [ ] DMARC, DKIM, and SPF configured on all domains
- [ ] Staff phishing awareness training conducted quarterly
- [ ] MFA enabled on all accounts
- [ ] Clear reporting process communicated to all staff

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

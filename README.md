# Incident-Response-Report
# 📄 Incident Response: Suspicious Academic Offer via Email

## Overview
This repository contains documentation and analysis related to a phishing attempt targeting ASD Academy students. The incident involved an unsolicited email offering grade improvement through a suspicious HTML file upload.

## 📅 Incident Details
- **Incident Title:** Suspicious Academic Offer via Email  
- **Reported By:** Hrushikesh  
- **Incident Date:** 19 August 2025  
- **Report Date:** 24 August 2025  
- **Source Email:** maheshimp@proton.me  
- **Recipient Email:** training@asdacademy.in  
- **Subject Line:** Urgent Bumper Offer - Upload the Test  

## 🕵️ Summary
An external sender impersonated an academic opportunity, urging students to submit assignments via a linked HTML file (`hi.html`). The file was designed to create a ZIP archive using a hardcoded password (`ramram`), potentially exposing sensitive data.

## 📁 Artifacts Collected
- Email file: `Urgent Bumper Offer.eml`
- HTML attachment: `hi.html`
- ZIP archive: `treasure.zip`
- Sender domain: `proton.me`

## 🔍 Technical Analysis
- HTML file uses `zip.js` to package uploaded files.
- ZIP archive is encrypted with a static password.
- No institutional branding or verification present.
- Potential for data exfiltration or malware delivery.

## 🚨 Recommended Actions
1. **Do not interact** with the HTML file or its links.
2. **Quarantine** the email and attachment for forensic analysis.
3. **Notify students** about the phishing attempt.
4. **Block sender domain** if necessary.
5. **Conduct security scans** on affected systems.
6. **Report to authorities** if fraud is confirmed.

## 🛡️ Repository Purpose
This repo serves as a centralized space for:
- Sharing forensic findings
- Tracking mitigation steps
- Collaborating on response protocols
- Educating stakeholders on phishing risks

## 📬 Contact
For questions or contributions, please reach out to:
**Hrushikesh** – [your email/contact here]

---

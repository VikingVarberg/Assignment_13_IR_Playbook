# Assignment_13_IR_Playbook - DocuPhishing Incident Response Playbook
IR playbook developed for the course Ethical Hacking for Halmstad University.

A structured incident response (IR) playbook for document-based phishing attacks aligned with NIST SP 800-61 Rev. 2 and mapped to the MITRE ATT&CK framework

This repository provides a practical, end-to-end approach for detecting, analysing, containing, eradicating, and recovering from DocuPhishing incidents, with focus on consistency, documentation, and continuous improvement.

---

# Overview

DocuPhishing is a phishing technique where threat actors leverage seemingly legitimate documents and trusted cloud services (for example PDFs, Office documents, SharePoint, Dropbox, etc etc) to trick users into executing malicious content or leaking credentials.

These attacks often:
- Abuse trusted platforms to bypass technical controls
- Rely heavily on social engineering
- Target cloud identities and email infrastructure
- Result in credential theft, malware execution, or data exfiltration

This playbook is designed to help security teams respond to such incidents in a repeatable and auditable manner, aligned with security standards

---

## Objectives

- Providing a clear and structured IR-workflow for DocuPhishing incidents
- Align response activities with NIST SP 800-61 
- Map attacker behaviour to MITRE ATT&CK tactics and techniques
- Improve detection, response time and decision-making
- Support documentation, escalation and post-incident improvement

---

## Framework Alignment

### NIST Incident Response Lifecycle
- **Preparation**
- **Detection & Analysis**
- **Containment, Eradication & Recovery**
- **Post-Incident Activity**

### MITRE ATT&CK
The playbook maps observed attacker behaviour to relevant:
- Tactics (Initial Access, Execution, Credential Access etc)
- Techniques (Phishing, Account Manipulation, Email Collection etc)

This mapping helps defenders understand where the attacker is in the kill chain and respond accordingly.

---

# NETWORKWALKS-HOROIHEOMA-B084-WK4-PENETRATION-TESTING
Black-Box Web Application Penetration Testing Assessment environment: Mediroza Hospital demonstration environment Programme: Networkwalks Cybersecurity Internship Batch: B084. Assessment type: Authorized educational security assessment. Platform: Kali Linux

<h2 align="center">Week 4 | Web Application Penetration Testing</h2>

<p align="center">
  <strong>Mediroza Hospital – Security Assessment</strong><br>
  Networkwalks Cybersecurity Internship | Batch B084
</p>

---

## Project Overview

This repository documents my Week 4 practical penetration-testing assessment as part of the **Networkwalks Cybersecurity Internship**.

The assessment evaluated a web application from an external perspective, focusing on application security, authentication, access controls, exposed resources and document security.

The exercise followed a structured approach covering reconnaissance, enumeration, vulnerability assessment, evidence review, risk evaluation and remediation.

> **Public Repository Notice:** Sensitive target identifiers, patient information, personal records, recovered passwords, database contents and confidential evidence have been excluded. This repository is a sanitized learning record.

## Objectives

- Identify the external attack surface of a web application.
- Perform domain, DNS and web-technology reconnaissance.
- Review publicly exposed application paths and resources.
- Assess authentication and access-control behaviour.
- Examine document encryption and metadata security.
- Evaluate potential information-exposure risks.
- Document observations and recommend remediation.

## Scope & Methodology

The assessment was conducted as an authorized educational exercise within the internship's defined scope.

| Phase | Activities |
|:---|:---|
| Reconnaissance | WHOIS, DNS, HTTP headers and technology discovery |
| Enumeration | Application paths, directories and exposed resources |
| Security Assessment | Authentication, input handling and access-control review |
| Evidence Review | Observation recording and evidence validation |
| Risk Assessment | Likelihood, impact and severity evaluation |
| Remediation | Corrective actions and security recommendations |

Testing was limited to the approved scope. No denial-of-service activity or out-of-scope testing was intended.

## Activities Performed

### 1. Reconnaissance & Enumeration

- WHOIS and domain registration reconnaissance
- DNS record enumeration (A, MX and NS)
- HTTP response-header inspection
- Web technology and server fingerprinting
- Public application path and resource review
- TCP port and service discovery
- Web content and directory exposure review

### 2. Web Application Security

- Authentication response and username-enumeration review
- SQL injection investigation and validation
- Patient portal access-control assessment
- Directory exposure review
- Database backup exposure assessment

### 3. Document Security

- PDF encryption and permissions analysis
- Authorized offline password-strength assessment
- PDF metadata inspection
- Potential information-disclosure review

## Tools & Technologies

| Tool | Purpose |
|:---|:---|
| Kali Linux | Assessment environment |
| WHOIS | Domain reconnaissance |
| Dig / DNSRecon | DNS enumeration |
| WhatWeb | Technology fingerprinting |
| cURL / Wget | HTTP and resource inspection |
| Nmap | Port and service discovery |
| Nessus (Tenable) | Vulnerability assessment |
| Burp Suite | Web application inspection |
| Firefox Developer Tools | Browser-side analysis |
| John the Ripper | Offline password-strength assessment |
| pdf2john / qpdf | PDF encryption analysis |
| ExifTool | Document metadata inspection |

## Findings Summary

The assessment documented **six findings** across four severity levels.

| Severity | Number of Findings | Distribution |
|:---|---:|---:|
| 🔴 Critical | 1 | 16.7% |
| 🟠 High | 2 | 33.3% |
| 🟡 Medium | 1 | 16.7% |
| 🔵 Low | 2 | 33.3% |
| **Total** | **6** | **100%** |

### Areas Reviewed

- Authentication and input-validation weaknesses
- Access-control concerns
- Exposed application resources
- Database backup exposure risks
- Document password security
- Metadata information disclosure

Detailed evidence and sensitive artefacts are excluded from this public repository. Refer to the original authorized assessment report for the full findings.

## Remediation Recommendations

| Security Area | Recommended Action |
|:---|:---|
| SQL Injection | Use parameterized queries and prepared statements |
| Access Control | Enforce server-side authorization on protected resources |
| Backup Security | Store database backups outside publicly accessible directories |
| Authentication | Use consistent error messages and rate limiting |
| Document Security | Apply appropriate encryption and password policies |
| Metadata | Remove unnecessary sensitive document metadata |
| Server Configuration | Disable directory indexing and unnecessary services |
| Monitoring | Review authentication events and access logs |
| Verification | Retest after remediation |

## Evidence & Screenshots

<img width="270" height="385" alt="wordlist generator" src="https://github.com/user-attachments/assets/c7ea6bbe-8340-4d4b-a057-1e7a0914e994" />


<img width="602" height="461" alt="hash calculator" src="https://github.com/user-attachments/assets/788b9b75-f122-4723-8a46-af96f64a60fe" />
<img width="345" height="404" alt="password cracker" src="https://github.com/user-attachments/assets/54cb4073-f2a3-4710-88e2-da92ffccb010" />
<img width="922" height="439" alt="Nessus 1" src="https://github.com/user-attachments/assets/33b67ab2-5f4f-420b-9af7-b2bdd8c77ed3" />
<img width="909" height="459" alt="Nessus 2" src="https://github.com/user-attachments/assets/48d08cea-dc43-45ee-a317-52024b133113" />
<img width="907" height="441" alt="Nessus" src="https://github.com/user-attachments/assets/63dd0cdb-5281-49b9-b9c7-05d68401d14c" />
<img width="894" height="466" alt="patient portal" src="https://github.com/user-attachments/assets/55ed59aa-c13b-44dd-9cef-4256048a8fab" />
<img width="956" height="461" alt="mediroza" src="https://github.com/user-attachments/assets/1b3dc9e9-3cae-4e88-afc1-de657417ae53" />
<img width="923" height="491" alt="burpsuite " src="https://github.com/user-attachments/assets/bf404a2b-36fa-48a4-8919-335bd4198340" />

"C:\Users\Administrator\Pictures\burpsuite recording.mp4"


Only approved, sanitized screenshots and non-sensitive evidence should be uploaded. Do not publish patient documents, personal data, database dumps, password lists, recovered credentials, session details, private keys or unredacted target information.

## Key Learning Outcomes

- Web application reconnaissance and attack-surface mapping
- DNS enumeration and service discovery
- Web technology fingerprinting
- Authentication and access-control assessment
- Understanding SQL injection risks
- Document encryption and metadata security
- Evidence handling and risk assessment
- Practical remediation reporting

**Key takeaway:** Effective penetration testing goes beyond running tools. It requires validating observations, understanding security impact, handling evidence responsibly and communicating practical remediation.

## Authorization & Responsible Use

This repository documents an authorized educational assessment. All techniques and tools discussed must only be used on systems and networks where explicit permission has been granted.

This portfolio does not authorize testing of the original assessment environment or any other system.

## Acknowledgements

My sincere appreciation to **Waqas Karim (CCIE)** and the **Networkwalks team** for their guidance, mentorship and support throughout the internship.

---

**Author:** Horoiheoma Chimezie  
**Programme:** Networkwalks Cybersecurity Internship – Batch B084  
**Project:** Week 4 – Web Application Penetration Testing & Security Assessment

<p align="center">
  <strong>Cybersecurity | Penetration Testing | Web Application Security</strong>
</p>

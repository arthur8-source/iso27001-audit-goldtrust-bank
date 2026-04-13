#  Risk Register

## ISO/IEC 27001:2022 Risk Assessment

**Organization:** GoldTrust Bank Ltd (Simulated Environment)

---

##  Risk Assessment Methodology

The risk assessment is based on a qualitative scoring model:

* **Likelihood:**
  1 = Low | 2 = Medium | 3 = High

* **Impact:**
  1 = Low | 2 = Medium | 3 = High

* **Risk Score = Likelihood × Impact**

| Score | Risk Level      |
| ----- | --------------- |
| 1–2   | Low             |
| 3–4   | Medium          |
| 6–9   | High / Critical |

---

## 🛡️ Risk Register

| ID  | Asset                  | Threat              | Vulnerability          | Likelihood | Impact | Score | Risk Level | Treatment             | Control Reference |
| --- | ---------------------- | ------------------- | ---------------------- | ---------- | ------ | ----- | ---------- | --------------------- | ----------------- |
| R1  | Customer Database      | Data Breach         | Weak access control    | 3          | 3      | 9     | Critical   | Implement MFA & RBAC  | A.8.2             |
| R2  | Core Banking System    | Unauthorized Access | No MFA                 | 3          | 3      | 9     | Critical   | Enforce MFA           | A.5.17            |
| R3  | Web Application        | SQL Injection       | Poor input validation  | 2          | 3      | 6     | High       | Secure coding & WAF   | A.8.28            |
| R4  | Network Infrastructure | DDoS Attack         | No IDS/IPS             | 2          | 3      | 6     | High       | Deploy IDS/IPS        | A.8.20            |
| R5  | Employee Email System  | Phishing            | Lack of awareness      | 3          | 2      | 6     | High       | Security training     | A.6.3             |
| R6  | Backup System          | Data Loss           | No backup policy       | 2          | 3      | 6     | High       | Automated backups     | A.8.13            |
| R7  | Employee Laptops       | Malware             | No endpoint protection | 2          | 2      | 4     | Medium     | Deploy EDR            | A.8.7             |
| R8  | Internal Network       | Insider Threat      | Excess privileges      | 2          | 3      | 6     | High       | Least privilege       | A.8.2             |
| R9  | Mobile Banking App     | Data Interception   | Weak encryption        | 2          | 3      | 6     | High       | Enforce HTTPS/TLS     | A.8.24            |
| R10 | Server Room            | Physical Intrusion  | Weak access control    | 2          | 2      | 4     | Medium     | CCTV & access control | A.7.1             |
| R11 | Logging System         | Undetected Attacks  | No SIEM                | 3          | 3      | 9     | Critical   | Implement SIEM        | A.8.16            |
| R12 | Admin Accounts         | Privilege Abuse     | No review process      | 2          | 3      | 6     | High       | Access reviews        | A.8.2             |

---

##  Key Risk Insights

* **Critical Risks Identified:**

  * Weak authentication (no MFA)
  * Lack of monitoring (no SIEM)
  * Poor access control mechanisms

* **High-Risk Areas:**

  * Web application security
  * Network protection
  * Backup and recovery

* **Human Risk Factors:**

  * Phishing susceptibility
  * Insider threats

---

##  Risk Treatment Strategy

The organization will apply the following approaches:

* **Mitigate:** Implement controls (MFA, SIEM, encryption)
* **Avoid:** Eliminate high-risk processes where possible
* **Transfer:** Use third-party services (e.g., cloud security)
* **Accept:** Accept low-risk items with management approval

---

##  Conclusion

This risk register identifies critical vulnerabilities affecting the confidentiality, integrity, and availability of information systems. Immediate remediation is required for high and critical risks to align with ISO/IEC 27001:2022 requirements and strengthen the organization’s security posture.

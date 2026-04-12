#  Risk Register

## ISO/IEC 27001:2022 Risk Assessment

**Organization:** GoldTrust Bank Ltd (Simulated)

---

##  Risk Scoring Methodology

* **Likelihood:** Low (1), Medium (2), High (3)
* **Impact:** Low (1), Medium (2), High (3)
* **Risk Score = Likelihood × Impact**

| Score | Risk Level    |
| ----- | ------------- |
| 1–2   | Low           |
| 3–4   | Medium        |
| 6–9   | High/Critical |

---

##  Risk Register Table

| ID  | Asset                  | Threat                       | Vulnerability          | Likelihood | Impact | Score | Risk Level | Treatment                    | Control Reference |
| --- | ---------------------- | ---------------------------- | ---------------------- | ---------- | ------ | ----- | ---------- | ---------------------------- | ----------------- |
| R1  | Customer Database      | Data Breach                  | Weak access controls   | 3          | 3      | 9     | Critical   | Implement MFA, RBAC          | A.8.2             |
| R2  | Core Banking System    | Unauthorized Access          | No MFA enabled         | 3          | 3      | 9     | Critical   | Enforce MFA                  | A.5.17            |
| R3  | Network Infrastructure | DDoS Attack                  | No traffic filtering   | 2          | 3      | 6     | High       | Deploy WAF, IDS/IPS          | A.8.20            |
| R4  | Employee Email System  | Phishing Attack              | Lack of user awareness | 3          | 2      | 6     | High       | Security awareness training  | A.6.3             |
| R5  | Employee Laptops       | Malware Infection            | No endpoint protection | 2          | 2      | 4     | Medium     | Install EDR solutions        | A.8.7             |
| R6  | Backup Systems         | Data Loss                    | No regular backups     | 2          | 3      | 6     | High       | Implement automated backups  | A.8.13            |
| R7  | Web Application        | SQL Injection                | Poor input validation  | 2          | 3      | 6     | High       | Secure coding practices, WAF | A.8.28            |
| R8  | Internal Network       | Insider Threat               | Excessive privileges   | 2          | 3      | 6     | High       | Least privilege principle    | A.8.2             |
| R9  | Physical Server Room   | Unauthorized Physical Access | Weak physical security | 2          | 2      | 4     | Medium     | Access control systems, CCTV | A.7.1             |
| R10 | Mobile Banking App     | Data Interception            | Lack of encryption     | 2          | 3      | 6     | High       | Enforce HTTPS, encryption    | A.8.24            |

---

##  Key Observations

* Multiple **critical risks** identified around access control and authentication
* Lack of **multi-factor authentication (MFA)** is a major security gap
* Human-related risks (phishing, insider threats) remain significant
* Network and application-level protections require strengthening

---

##  Risk Treatment Strategy

GoldTrust Bank Ltd will adopt the following treatment approaches:

* **Mitigate:** Apply security controls (e.g., MFA, encryption, WAF)
* **Avoid:** Discontinue high-risk activities where applicable
* **Transfer:** Use third-party services (e.g., cloud security providers)
* **Accept:** Accept low-level risks with management approval

---

##  Conclusion

This risk assessment highlights critical vulnerabilities in authentication, network security, and user awareness. Immediate remediation is required to align with ISO/IEC 27001:2022 standards and ensure the confidentiality, integrity, and availability of information assets.

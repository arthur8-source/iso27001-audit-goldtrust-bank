
#  Audit Findings Report

## ISO/IEC 27001:2022 Internal Audit

**Organization:** GoldTrust Bank Ltd (Simulated)

---

##  Audit Overview

**Audit Type:** Internal ISO/IEC 27001:2022 Audit
**Audit Scope:**

* Core banking systems
* Mobile banking application
* Internal IT infrastructure
* Customer data processing systems

**Audit Criteria:** ISO/IEC 27001:2022 Standard (Annex A Controls)

**Audit Objective:**
To evaluate the effectiveness of the Information Security Management System (ISMS) and identify gaps in compliance with ISO/IEC 27001:2022.

---

##  Summary of Findings

| Severity | Count |
| -------- | ----- |
| High     | 4     |
| Medium   | 4     |
| Low      | 2     |

---

##  High Severity Findings

### 1. Lack of Multi-Factor Authentication (MFA)

* **Control Reference:** A.5.17 (Authentication Information)
* **Observation:** Access to critical systems is based solely on username and password.
* **Risk:** Increased likelihood of unauthorized access and account compromise.
* **Impact:** Potential data breaches and financial loss.
* **Recommendation:** Implement MFA across all critical systems, including core banking and administrative access.

---

### 2. Absence of Formal Backup Strategy

* **Control Reference:** A.8.13 (Information Backup)
* **Observation:** No structured or automated backup process is in place.
* **Risk:** Loss of critical data in case of system failure or cyber incidents.
* **Impact:** Business disruption and data unavailability.
* **Recommendation:** Implement automated, regular backups with offsite storage and periodic testing.

---

### 3. No Centralized Logging or Monitoring (SIEM)

* **Control Reference:** A.8.16 (Monitoring Activities)
* **Observation:** Logs are not centrally collected or analyzed.
* **Risk:** Delayed detection of security incidents.
* **Impact:** Increased dwell time for attackers.
* **Recommendation:** Deploy a SIEM solution for real-time monitoring and alerting.

---

### 4. Lack of Secure Software Development Practices

* **Control Reference:** A.8.28 (Secure Coding)
* **Observation:** No formal secure development lifecycle (SDLC) is implemented.
* **Risk:** Vulnerabilities such as SQL injection may go undetected.
* **Impact:** Compromise of web and mobile applications.
* **Recommendation:** Adopt secure coding standards and conduct regular code reviews and penetration testing.

---

##  Medium Severity Findings

### 5. Inadequate Security Awareness Training

* **Control Reference:** A.6.3 (Information Security Awareness)
* **Observation:** Employees have not received formal security training.
* **Risk:** Increased susceptibility to phishing attacks.
* **Recommendation:** Conduct regular security awareness training and phishing simulations.

---

### 6. Weak Privileged Access Management

* **Control Reference:** A.8.2 (Privileged Access Rights)
* **Observation:** Privileged accounts are not periodically reviewed.
* **Risk:** Abuse of elevated privileges.
* **Recommendation:** Enforce least privilege and conduct periodic access reviews.

---

### 7. Insufficient Network Security Controls

* **Control Reference:** A.8.20 (Network Security)
* **Observation:** Firewall is deployed but lacks advanced protections (IDS/IPS).
* **Risk:** Increased exposure to network-based attacks.
* **Recommendation:** Implement IDS/IPS and network segmentation.

---

### 8. Incomplete Encryption Implementation

* **Control Reference:** A.8.24 (Use of Cryptography)
* **Observation:** Encryption is not consistently enforced across systems.
* **Risk:** Data interception during transmission.
* **Recommendation:** Enforce end-to-end encryption for all sensitive data.

---

##  Low Severity Findings

### 9. Physical Security Improvements Needed

* **Control Reference:** A.7.1 (Physical Security Perimeter)
* **Observation:** Basic controls exist but lack surveillance enhancements.
* **Recommendation:** Improve CCTV coverage and access logging.

---

### 10. Lack of Formal Incident Response Plan

* **Control Reference:** A.5.24 (Information Security Incident Management)
* **Observation:** No documented incident response procedures.
* **Recommendation:** Develop and implement an incident response plan.

---

##  Overall Assessment

The audit indicates that while some foundational controls are in place, the organization’s ISMS is **not yet fully aligned with ISO/IEC 27001:2022 requirements**.

Critical gaps exist in:

* Authentication mechanisms
* Monitoring and detection
* Data protection and backup
* Secure development practices

---

##  Conclusion

Immediate remediation is required for high-risk findings to reduce the organization’s exposure to cyber threats.

A structured implementation of security controls, aligned with ISO/IEC 27001:2022, will significantly improve the confidentiality, integrity, and availability of information assets.

---

##  Auditor’s Statement

This audit was conducted based on a simulated environment and reflects best practices in ISO/IEC 27001 auditing and risk assessment. The findings and recommendations are intended to guide improvements toward compliance and security maturity.

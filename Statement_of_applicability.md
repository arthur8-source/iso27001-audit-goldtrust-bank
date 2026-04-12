#  Statement of Applicability (SoA)

## ISO/IEC 27001:2022

**Organization:** GoldTrust Bank Ltd (Simulated)

---

##  Purpose

The Statement of Applicability (SoA) defines the set of security controls selected from **ISO/IEC 27001:2022 Annex A**.

It outlines:

* Which controls are **applicable**
* Which controls are **excluded**
* Justifications for inclusion or exclusion
* Implementation status of each control

---

##  Scope

This SoA applies to:

* Core banking systems
* Mobile banking applications
* Internal IT infrastructure
* Customer data processing systems

---

##  Control Applicability Table

| Control ID | Control Name                                   |  (Applicable) | Implementation Status | Justification                                               |
| ---------- | ---------------------------------------------- | ----------------- | --------------------- | ----------------------------------------------------------- |
| A.5.1      | Policies for Information Security              | Yes               | Implemented           | Required for governance and compliance                      |
| A.5.7      | Threat Intelligence                            | No                | Not Implemented       | Organization currently lacks threat intelligence capability |
| A.5.17     | Authentication Information                     | Yes               | Partially Implemented | Password-based authentication exists; MFA not enforced      |
| A.5.23     | Information Security for Use of Cloud Services | Yes               | Planned               | Cloud adoption underway for mobile banking                  |
| A.6.3      | Information Security Awareness                 | Yes               | Not Implemented       | No formal training program in place                         |
| A.7.1      | Physical Security Perimeter                    | Yes               | Implemented           | Data center secured with access controls                    |
| A.8.2      | Privileged Access Rights                       | Yes               | Partially Implemented | Privileges assigned but not regularly reviewed              |
| A.8.7      | Protection Against Malware                     | Yes               | Partially Implemented | Basic antivirus deployed; no EDR solution                   |
| A.8.13     | Information Backup                             | Yes               | Not Implemented       | Backup strategy not formally defined                        |
| A.8.20     | Network Security                               | Yes               | Partially Implemented | Firewall exists; IDS/IPS not deployed                       |
| A.8.24     | Use of Cryptography                            | Yes               | Partially Implemented | Encryption used but not enforced across all systems         |
| A.8.28     | Secure Coding                                  | Yes               | Not Implemented       | No formal secure development lifecycle (SDLC)               |
| A.8.16     | Monitoring Activities                          | Yes               | Not Implemented       | No centralized logging or SIEM solution                     |
| A.5.30     | ICT Readiness for Business Continuity          | Yes               | Planned               | Business continuity plan under development                  |

---

##  Summary of Control Status

* **Implemented Controls:** Basic governance and physical security measures are in place
* **Partially Implemented Controls:** Authentication, access control, and network security require improvement
* **Not Implemented Controls:**

  * Security awareness training
  * Backup processes
  * Monitoring and logging (SIEM)
  * Secure software development practices

---

##  Key Gaps Identified

* Absence of **Multi-Factor Authentication (MFA)**
* Lack of **Security Awareness Training Program**
* No **formal backup and recovery strategy**
* Limited **network monitoring and detection capabilities**
* No **secure coding standards or SDLC process**

---

##  Recommendations

To achieve ISO/IEC 27001 compliance, GoldTrust Bank Ltd should:

* Implement **Multi-Factor Authentication (MFA)** across all critical systems
* Deploy a **Security Information and Event Management (SIEM)** solution
* Establish a **formal backup and disaster recovery plan**
* Introduce **security awareness training programs**
* Adopt **secure coding practices and SDLC frameworks**

---

##  Conclusion

This Statement of Applicability demonstrates that while foundational controls exist, significant improvements are required to achieve full compliance with ISO/IEC 27001:2022.

The identified gaps align closely with the organization’s risk profile and should be addressed as part of a structured Information Security Management System (ISMS) implementation roadmap.


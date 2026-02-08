# Ethical Security Operations License (ESOL)

**Version:** 1.1

**Release Date:** 05.02.2026

**Jurisdiction:** Germany (Berlin)

**Maintainer:** @Volkan Şah & @BadTin and some Cats

---

## 📌 Overview

The **Ethical Security Operations License (ESOL)** is a high-integrity, restrictive usage license. It is designed to be layered on top of any standard software license (e.g., MIT, Apache, GPL) to enforce ethical boundaries in cybersecurity.

While the base license governs the copying and modification of the code, the **ESOL v1.1** governs the **legal and ethical execution** of the Work.

---
<details> </details>

<summary>📄 Full License Text (ESOL v1.1)</summary>

### Section 1: Preamble and Scope

The **Ethical Security Operations License (ESOL v1.1)** is an **additional, non-severable condition** supplementing the primary license under which the covered software (hereinafter "the Work") is distributed.

By downloading, copying, modifying, or executing the Work, the Licensee **irrevocably agrees** to adhere to both the terms of the primary license and the specific, mandatory ethical constraints defined herein. **Lack of awareness of these terms does not constitute a defense.**

### Section 2: Mandatory Ethical Use and Purpose

The grant of rights under this License is **expressly and exclusively conditioned** upon the Licensee's continuous adherence to the following use limitations:

1. **Authorized Use Only:** The Work shall be used **exclusively** for:
* Defensive security operations (Blue Teaming).
* Authorized penetration testing (Red Teaming) with documented consent.
* Vulnerability research on systems owned or explicitly authorized by the researcher.
* Security compliance auditing with contractual authorization.


2. **Explicit Written Authorization Required:** Any security testing, scanning, exploitation, or enumeration against **any system not wholly owned by the Licensee** requires **explicit, documented, written authorization** from the rightful owner **prior to execution**. Verbal permission or implicit consent (including bug bounty programs without specific scope) does **not** constitute authorization.
3. **Educational Use Constraints:** Educational or research use must occur only in isolated, controlled environments (VMs, labs) and must not target production systems or public infrastructure.

### Section 3: Prohibited Use (Malicious Activities)

The Licensee is **strictly and unconditionally prohibited** from using the Work for:

* **Unauthorized Access:** Scanning, probing, or accessing any system without explicit prior written authorization.
* **Malicious Operations:** Creating, distributing, or facilitating malware, ransomware, phishing, or social engineering.
* **Service Disruption:** Any form of DoS/DDoS or unauthorized degradation of system performance.
* **Data Exploitation:** Unauthorized copying, modification, or deletion of data not owned by the Licensee.
* **Legal Violations:** Any activity violating the Computer Fraud and Abuse Act (CFAA), GDPR, national cybercrime laws (e.g., StGB § 202a/b/c in Germany), or international treaties.

### Section 4: Compliance Verification and Audit Rights

The Licensor reserves the right to:

* Request documentation of authorization for any deployment of the Work.
* Audit compliance upon reasonable notice if misuse is suspected.
* Publicly disclose violations (including Licensee identity) to protect the security community.

### Section 5: No Warranty Regarding Legal Compliance

**THE WORK IS PROVIDED "AS IS".** THE LICENSOR MAKES NO REPRESENTATION THAT USE OF THE WORK, EVEN IN COMPLIANCE WITH THIS LICENSE, WILL BE LEGAL IN ALL JURISDICTIONS. THE LICENSEE BEARS SOLE RESPONSIBILITY FOR LEGAL COMPLIANCE.

### Section 6: Violation and Termination

Violation of **any** provision of this ESOL v1.1 constitutes a **material breach** resulting in:

1. **Immediate Automatic Termination** of all rights under both the primary license and this ESOL.
2. **Obligation to Cease Use** and destroy all copies of the Work.
3. **Liability for Damages:** Including direct/consequential damages, legal costs, and reputational harm.
4. **Criminal Reporting:** The Licensor reserves the right to report violations to law enforcement.

### Section 7: Severability and Precedence

If any provision is held unenforceable, the remaining provisions remain in effect. **In any conflict between a primary license (e.g., MIT, GPL) and ESOL v1.1, the ESOL v1.1 takes precedence regarding ethical use constraints.**

### Section 8: Jurisdiction and Dispute Resolution

This License shall be governed by the laws of **Germany (Berlin)**. Disputes shall be resolved through binding arbitration.


 </details>
---

## 🛠 How to Apply ESOL to Your Project

To make your project "ESOL-Protected," add the following statement to your `LICENSE` file or your primary `README.md`:

> **Licensing Statement:** > This Work is dual-licensed under the **[INSERT BASE LICENSE, e.g., MIT]** and the **Ethical Security Operations License (ESOL v1.1)**. The ESOL is a mandatory, non-severable condition of use. By using this software, you agree to all ethical constraints defined in the ESOL v1.1.

---

## 🔄 Compatibility Matrix

| Base License | Compatible? | Conflict Resolution |
| --- | --- | --- |
| **MIT / BSD / ISC** | ✅ Yes | ESOL adds usage restrictions. |
| **Apache 2.0** | ✅ Yes | ESOL complements the patent/usage clauses. |
| **GPL v2 / v3** | ✅ Yes* | ESOL acts as a "Usage Covenant" (Nutzungsvorbehalt). |
| **Commercial** | ✅ Yes | ESOL provides a baseline for ethical conduct. |

**Note: Under strict OSI definitions, usage restrictions may move a project from "Free Software" to "Source Available / Ethical Software".*

---

> *Repository maintained for the security community. Checked & Validated on 07.02.2026.*


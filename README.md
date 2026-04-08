# State-Authorization-Risk

**Overview: State Auth Case Study**

This artifact demonstrates a structured governance framework for determining when cybersecurity incidents trigger regulatory escalation and notification obligations across state and federal jurisdictions. The scenario reflects a hypothetical higher education institution operating in California (non-SARA), potentially exposed to multi-state and federal regulatory requirements. In this case, the Director of Finance’s email was hacked, and a confidential vendor requested a $50K wire transfer. The wire has not been sent, but the attacker still has access to the Director’s email and communications. Confidential information exists in the account, and the exact data accessed is unknown.

Frameworks referenced:
NIST CSF
NIST 800-53 (specifically the IR, RA, IA families)
FERPA regulatory considerations

**Why This Matters:**

Failure to correctly identify and act on regulatory notification obligations during a cyber incident can result in legal penalties, loss of state authorization to operate, and significant reputational damage. Since the institution is in California, failing to meet BPPE compliance standards could risk losing its authorization to operate in the state.

**Risk Context & Assessment**

Primary Risk Domains:
-Regulatory non-compliance (state, federal, education-specific)
-Exposure of student PII (FERPA-protected data)
-Multi-state breach notification obligations
-Delayed or incorrect escalation decisions
-Reputational impact and loss of institutional trust

Risk Characteristics:
-Likelihood: Moderate (based on common incident scenarios)
-Impact: High (legal + operational + reputational)
-Inherent Risk: High due to regulatory complexity
-Residual Risk: Reduced through structured escalation criteria and governance clarity

**Decision & Rationale**

Escalation Criteria & Ownership:

![Escalation Chart](https://github.com/user-attachments/assets/568984cd-a9a9-42a5-a5f9-7e2408e95663)

**Regulatory Notification Rationale**

Regulatory escalation is triggered when one or more of the following conditions are met:
Exposure or suspected exposure of protected student data (FERPA)
Breach impacting California residents (state breach notification laws)
Multi-state student impact requiring cross-jurisdiction compliance
Material incident affecting institutional operations or reporting obligations
Confirmed compromise of privileged or administrative accounts
Legal thresholds for disclosure are met or exceeded

**Governance Flow & Maturity Path**

<img width="476" height="442" alt="image" src="https://github.com/user-attachments/assets/f9b4926e-8d28-40d1-8ad9-aff044a98580" />


**Regulatory Bodies Considered**

-California Bureau for Private Postsecondary Education (BPPE)
-U.S. Department of Education
-State Attorneys General (multi-state scenarios)
-Secretary of State (where applicable)


**Outcome**

-Defined escalation thresholds reduce ambiguity during incidents
-Improved response time and regulatory accuracy
-Strengthened audit readiness and documentation consistency


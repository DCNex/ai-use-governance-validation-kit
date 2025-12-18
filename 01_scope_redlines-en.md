### Purpose
This section defines the **scope of permissible AI usage** and **non-negotiable redlines**
for enterprise AI / LLM adoption in the financial industry, in alignment with the
Taiwan FSC “Guidelines for the Use of AI in the Financial Industry”.

The design follows a **risk-based and proportional approach**, ensuring innovation
while maintaining accountability, customer protection, and financial stability. :contentReference
>README available in: [中文](README.md) | [English](README-en.md)
---

### In-scope AI usage
The following use cases are generally in scope, subject to risk tiering and validation:

- Internal productivity tools (e.g., drafting, summarization, knowledge retrieval)
- Decision-support systems with **human review and final accountability**
- Customer service assistance with disclosure and fallback options
- Risk analysis, monitoring, and anomaly detection that do not result in
  fully automated customer-impacting decisions

> All in-scope use cases must pass **use case intake, validation, and monitoring**
as defined in subsequent sections.

---

### Out-of-scope / Redlines (Non-negotiable)
The following scenarios are **prohibited** unless explicitly approved through
regulatory-compliant pilot or sandbox mechanisms:

1. **Fully automated decisions** that directly affect customer rights or obligations
   without meaningful human oversight.
2. Use of **personal data or sensitive customer information** beyond approved
   data classification and handling rules.
3. AI outputs used as **final judgments** in credit, pricing, claims, or eligibility
   determinations without professional review.
4. Deployment of AI systems with **unknown model behavior, insufficient testing,
   or lack of auditability**.
5. Concealed use of AI in customer-facing services without appropriate disclosure
   or explanation.

These redlines reflect FSC expectations on **customer protection, accountability,
and transparency**. 

---

### Risk-based tiering
AI use cases should be classified using a **risk-based approach**:

- **High Risk**  
  - Direct customer impact  
  - Requires formal approval, human-in-the-loop (HITL),
    enhanced validation, and continuous monitoring

- **Medium Risk**  
  - Indirect customer impact or internal decision support  
  - Requires validation, logging, and periodic review

- **Low Risk**  
  - Internal productivity with no customer impact  
  - Requires baseline controls and usage monitoring

Risk tiering determines the **depth of controls**, not the eligibility to use AI. 

---

### Generative AI-specific constraints
For generative AI systems:

- Outputs **must not be treated as authoritative or final**
- Professional judgment remains mandatory for high-risk use cases
- Training and prompting data must respect data classification and privacy rules
- Model limitations and risks should be documented and monitored

This aligns with FSC guidance that generative AI remains a **tool**, not a decision-maker. 

---

### Trade-offs & Exceptions
- **Speed vs. control**: Medium-risk use cases may allow limited early use,
  provided validation and audit trails are completed within a defined timeframe.
- **Business exceptions**: Any exception requires joint approval from
  Product Owner and Compliance, with documented rationale and expiry.
- **Hard stop conditions**: Any breach involving privacy, customer rights,
  or uncontrolled automation triggers immediate suspension and escalation.

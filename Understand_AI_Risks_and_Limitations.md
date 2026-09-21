# Understand AI Risks & Limitations

## 1. Hallucinations
AI systems may generate outputs that appear correct but are factually inaccurate or misleading.  
- **Definition**: Producing false or fabricated information without malicious intent.  
- **Example**: AI suggesting a non-existent CVE vulnerability during analysis.  
- **Impact**: Can mislead analysts if not validated, leading to wasted effort or incorrect conclusions.  

---

## 2. False Conclusions
AI may misinterpret data and produce incorrect results.  
- **Causes**: Poor training data, biased datasets, or incomplete context.  
- **Example**: Flagging legitimate admin activity as malicious.  
- **Impact**: False positives increase workload, while false negatives may allow threats to slip through.  

---

## 3. Missing Context
AI often struggles when critical context is absent.  
- **Definition**: Lack of environmental, organizational, or situational details.  
- **Example**: AI misclassifying a login from a new location as suspicious without knowing the user is traveling.  
- **Impact**: Misaligned recommendations that don’t fit real-world SOC operations.  

---

## 4. Data Privacy Concerns
AI systems rely on large datasets, which may include sensitive information.  
- **Risks**:  
  - Exposure of confidential logs or incident data.  
  - Leakage of personally identifiable information (PII).  
  - Compliance violations (GDPR, HIPAA, etc.).  
- **Best Practice**: Avoid feeding sensitive data into external AI systems without proper safeguards.  

---

## 5. Human Validation Requirements
AI outputs must always be reviewed by human analysts before implementation.  
- **Why**:  
  - AI lacks full situational awareness.  
  - Recommendations may conflict with business or compliance needs.  
  - Human judgment ensures accuracy and practicality.  
- **Best Practice**: Treat AI as a **decision-support tool**, not a decision-maker.  

---

## Summary
AI in security operations is powerful but not infallible.  
Risks include **hallucinations, false conclusions, missing context, privacy concerns, and the need for human validation**.  
SOC analysts must apply **critical thinking, validation, and compliance checks** to ensure AI outputs strengthen security rather than introduce new risks.

# Development and Data  
*(Legal, Privacy, and AI-Related Risks)*

## Context
The development phase is where most **data-related decisions are made informally**.

Teams collect, copy, transform, test, and experiment with data to:
- build features
- fix bugs
- train or fine-tune AI models
- validate performance

These activities often happen under time pressure, with limited documentation, making this stage **one of the highest-risk phases** for privacy and compliance failures.

---

## Common Risk Areas

### 1. Use of Real User Data in Development and Testing

**What typically happens**  
Production user data is copied into development or testing environments to save time or improve accuracy.

**Why it happens**  
- Lack of anonymised test datasets  
- Pressure to replicate real-world behaviour  
- Limited awareness of privacy implications  

**Risk**  
Personal data may be accessed by more people than necessary, increasing exposure and misuse risk.

**Impact**  
- Potential privacy violations  
- Increased breach surface  
- Loss of user trust  

**Preventive thinking**  
Use anonymised or synthetic data wherever possible and restrict access to live datasets.

---

### 2. Purpose Drift During AI Development

**What typically happens**  
Data collected for one feature or service is reused to train or improve AI models without revisiting the original purpose.

**Why it happens**  
- AI development encourages reuse of large datasets  
- Experimental model training lacks clear boundaries  
- Assumption that internal reuse is harmless  

**Risk**  
Processing personal data beyond its originally disclosed purpose.

**Impact**  
Weakens the validity of user consent and exposes the organisation to compliance risk.

**Preventive thinking**  
Re-evaluate data usage when introducing AI features and document purpose alignment clearly.

---

### 3. Training Data Quality and Accuracy

**What typically happens**  
AI models are trained on datasets that may be outdated, incomplete, or biased.

**Why it happens**  
- Limited control over data sources  
- Historical data reused without review  
- Speed prioritised over validation  

**Risk**  
Inaccurate or biased outputs affecting users or clients.

**Impact**  
- Harmful or unfair outcomes  
- Reduced reliability of the product  
- Reputational damage  

**Preventive thinking**  
Establish basic checks for data relevance, accuracy, and representativeness before training.

---

### 4. Embedded Personal Data in AI Models

**What typically happens**  
Once trained, AI models may retain patterns derived from personal data even if the original dataset is deleted.

**Why it happens**  
- Technical complexity of retraining models  
- Limited awareness of data persistence in models  

**Risk**  
Difficulty in fully ceasing processing after consent withdrawal or data deletion requests.

**Impact**  
Legal and ethical concerns around data erasure and ongoing processing.

**Preventive thinking**  
Design AI workflows that minimise personal data reliance and allow for retraining when necessary.

---

### 5. Lack of Transparency in AI Outputs

**What typically happens**  
AI systems generate recommendations or decisions without clear explanations.

**Why it happens**  
- Use of complex or black-box models  
- Focus on performance over interpretability  

**Risk**  
Users and clients cannot understand how outcomes are generated.

**Impact**  
- Reduced trust  
- Difficulty responding to complaints or challenges  
- Accountability gaps  

**Preventive thinking**  
Maintain documentation explaining AI logic at a functional level, even if technical details are complex.

---

### 6. Over-Collection of Data “Just in Case”

**What typically happens**  
Teams collect more data than immediately required, anticipating future AI use.

**Why it happens**  
- Storage is inexpensive  
- AI models benefit from large datasets  
- Unclear future product roadmap  

**Risk**  
Violation of data minimisation principles.

**Impact**  
- Increased compliance exposure  
- Higher breach impact  
- Unnecessary long-term storage  

**Preventive thinking**  
Collect data based on current, defined needs and reassess when requirements change.

---

### 7. Third-Party AI Tools and APIs

**What typically happens**  
Developers use external AI tools for analytics, testing, or automation.

**Why it happens**  
- Faster development  
- Limited in-house AI expertise  

**Risk**  
Unclear data handling practices by third parties.

**Impact**  
- Loss of control over personal data  
- Cross-border data transfer concerns  
- Contractual and accountability gaps  

**Preventive thinking**  
Understand data flows and document third-party dependencies before integration.

---

### 8. Logging, Prompts, and AI Output Storage

**What typically happens**  
System logs, prompts, and AI outputs are stored for debugging or performance review.

**Why it happens**  
- Debugging needs  
- Model improvement efforts  

**Risk**  
Sensitive personal data may be unintentionally stored or exposed.

**Impact**  
- Data leakage risks  
- Increased breach consequences  

**Preventive thinking**  
Limit retention of logs and avoid storing personal data in prompts where possible.

---

## Why this stage matters the most
Decisions made during development:
- are hard to reverse later  
- shape how data flows through the system  
- determine whether AI systems remain controllable  

Most privacy failures are **design failures**, not policy failures.

---

## Key takeaway
AI does not remove responsibility — it **raises the standard of care**.

Strong privacy outcomes during development depend less on legal knowledge and more on:
- thoughtful design choices  
- documentation  
- early risk awareness  

---

## Note
This section focuses on **risk identification and awareness**, not legal advice or technical prescriptions.

The objective is to help software teams think more clearly about **how data and AI interact during development**.

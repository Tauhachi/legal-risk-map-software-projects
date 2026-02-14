# Risk Scenarios  
*(How Legal, Privacy, and AI Issues Arise in Practice)*

## Purpose of this file
This section presents **short, realistic scenarios** showing how legal, privacy, and AI-related risks typically emerge in software projects.

These are not extreme cases.  
They reflect **everyday decisions** made under time and business pressure.

---

## Scenario 1: Training an AI Feature Using Client Data

A software company launches an AI-based analytics feature.  
To improve accuracy, developers reuse historical client data without updating contracts or disclosures.

**What went wrong**
- Purpose of data use was expanded silently
- Client expectations were not revisited

**Result**
- Client questions usage after noticing unusual outputs
- Trust damage and contractual disputes arise

---

## Scenario 2: AI Output Treated as Final Decision

An AI tool is used to prioritise customer requests.  
Over time, human review is removed to increase efficiency.

**What went wrong**
- AI recommendations became de facto decisions
- No review mechanism existed

**Result**
- Certain users consistently receive poor outcomes
- Complaints escalate without clear explanations

---

## Scenario 3: Real User Data in Testing Environments

To debug issues quickly, engineers copy production data into test systems.

**What went wrong**
- Access controls were weaker in test environments
- Data exposure increased unnecessarily

**Result**
- Internal data leak during testing
- Loss of confidence among clients

---

## Scenario 4: Model Behaviour Changes After Scaling

An AI model is retrained to handle increased load.  
Outputs subtly change, affecting client workflows.

**What went wrong**
- Model updates were not communicated
- Clients assumed consistent behaviour

**Result**
- Confusion and dissatisfaction
- Disputes over service expectations

---

## Scenario 5: Third-Party AI Tool Introduced Quietly

A team integrates an external AI API to speed up development.

**What went wrong**
- Data sent to third party without full assessment
- Limited understanding of data retention practices

**Result**
- Client raises concerns about data handling
- Emergency review and rollback required

---

## Why these scenarios matter
None of these situations involve:
- bad intent
- advanced technical failure
- deliberate misuse  

They arise from **ordinary decisions made without structured risk thinking**.

---

## Key takeaway
Most legal and privacy problems in software projects are:
- predictable  
- preventable  
- rooted in communication gaps  

Scenario-based thinking helps teams identify risks **before** they escalate.

---

## Note
These scenarios are illustrative and anonymised.  
They are intended to support learning and discussion, not attribution or legal analysis.

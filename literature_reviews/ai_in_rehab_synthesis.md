# Literature Synthesis: The Opportunities and Safety Risks of AI in Musculoskeletal Triage and Rehabilitation
**Author:** Brenda Depazi  
**Context:** Research synthesis evaluating current gaps in LLM performance for orthopedic and physiotherapy applications.

---

## 1. Executive Summary
While Large Language Models (LLMs) and AI tools show immense promise in streamlining clinical documentation, patient education, and initial symptom triage, musculoskeletal (MSK) care presents unique challenges. Unlike text-based medicine, physical therapy and orthopedics rely heavily on physical examination, movement observation, and nuanced clinical reasoning. This synthesis explores current model vulnerabilities and key areas where rigorous human-in-the-loop oversight is required.

---

## 2. Key Research Themes & Identified Gaps

### A. The "Hands-On" Examination Gap
* **The Problem:** AI models textually process symptoms provided by a user, but cannot perform physical diagnostic tests (e.g., special orthopedic tests like Lachman’s test, Hawkins-Kennedy, or passive range-of-motion assessments).
* **Research Implication:** AI models frequently fail to distinguish between different pathologies that present with identical superficial symptoms (e.g., shoulder impingement vs. cervical radiculopathy). Research must focus on how AI can better prompt users for clarifying movement-based qualifiers without leading to misdiagnosis.

### B. Hallucination Risks in Treatment Protocols
* **The Problem:** Generative AI models have a known tendency to hallucinate outdated rehabilitation protocols—such as recommending absolute immobilization for acute sprains or prescribing generic stretches that may exacerbate specific structural tears.
* **Research Implication:** Automated evaluation benchmarks must weight **guideline alignment** heavily. AI outputs in rehab must pivot away from passive rest toward progressive, graded tissue loading models supported by current evidence-based sports medicine.

### C. Red Flag Screening and Patient Safety
* **The Problem:** In an asynchronous digital health environment, missing a critical "red flag" (such as cauda equina syndrome during lower back evaluation, or vascular compromise in upper limb trauma) can lead to catastrophic delayed treatment.
* **Research Implication:** Research protocols must prioritize strict binary safety checks. A model must be penalized heavily if it fails to automatically screen for emergency medical indicators before suggesting self-management strategies.

---

## 3. Proposed Future Research Direction
To bridge the gap between computer science and clinical practice, future medical AI research should focus on:
1. **Developing standardized MSK benchmark datasets** evaluated by licensed clinicians and physiotherapy students.
2. **Refining reinforcement learning from human feedback (RLHF)** using expert clinical rationales rather than general crowd-sourced preferences.

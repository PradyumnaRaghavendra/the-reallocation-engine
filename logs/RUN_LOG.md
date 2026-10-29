# Run Log — Setup Exercise: Your Search's Personal Layer
**Date:** 2026-10-29  
**Student:** Pradyumna Raghavendra  
**Course:** INFO 7375 — Computational Skepticism for AI  

---

## What Was Built

Three files created in `search/` folder:

1. **search/resume.json** — Structured, attested record of professional experience, education, certifications, and technical skills. Includes two fintech projects discovered during attestation pass.
2. **search/profile.yml** — Target role, visa constraints (F-1 OPT Jan 18 2027 – Jan 17 2028, STEM-eligible, confirmed with DSO), geography (Boston, NYC, Jersey City, SF, Seattle + suburbs), industry preferences (Fintech, Biotech), company preferences (400+ mid-size non-FAANG; 10-500 employee funded startups), and sponsorship requirement (mandatory gate).
3. **search/gaps.md** — Six identified gaps between attested resume and typical MLE/Data Scientist role requirements in Fintech/Biotech, with evidence-based plan to close each gap.

---

## Attestation Pass: Three Errors Caught in resume.json

1. **Missing bullet point** — Ahold Delhaize experience was missing "Collaborated with data scientists and engineers to ship ML-driven features reliably." Added to achievements.
2. **Overstated contribution** — GNN recommendation models bullet was reworded from "Developed" to "Contributed to" to reflect team contribution rather than solo work.
3. **Missing project entries** — Two fintech projects were omitted from initial extraction: "Fraud Detection Model Evaluation" and "Agentic Credit Decisioning & Collections Assistant (MCP-Connected)." Both added to projects section during verification.

---

## Top Gap from gaps.md

**End-to-end agentic AI in production with observability** — Medical Assistant RAG project is deployed but lacks observability instrumentation. Critical missing components: LangSmith tracing (latency + token cost), retrieval quality metrics (recall@k, MRR), hallucination detection (claim-level validation via LLM judge), human-in-the-loop metrics (escalation rate, approval/reject rates), and feedback loop for regression testing. Plan: instrument Medical Assistant with full observability stack and publish metrics dashboard showing tracing, retrieval quality, hallucination rates, and human-review trends.

---

## Gap Editing: Row Killed and Row Rewritten

**Row killed:** "Domain knowledge: Fintech systems & financial risk modeling"  
**Why it was wrong:** Initial extraction missed two completed fintech projects (Fraud Detection Model and Agentic Credit Decisioning system). Resume now shows relevant fintech domain work, so this gap no longer applies.

**Row rewritten (in student's own words):** "End-to-end agentic AI in production with observability"  
Rewrite reflects actual understanding: job postings explicitly ask for observability in multi-agent systems. The evidence is grounded in concrete metrics (tracing, retrieval quality, hallucination detection, human-in-the-loop metrics, feedback loops). Plan is specific and verifiable (instrument existing deployed system with LangSmith, build labeled eval set, measure recall@k and hallucination rates, establish feedback loop for regression testing).

---

## profile.yml Corrections During Drafting

**Field corrected:** `company_preferences.size_range`  
**Original (agent-drafted):** Generic range "50-1000 employees (estimated)"  
**Corrected to:** Split into two separate definitions:
- Mid-size companies (non-FAANG/non-Big Tech): 400+ employees
- Funded startups (Series A+): 10-500 employees

This distinction is critical for the engine's filtering logic and reflects the student's actual preferences and search strategy.

---

## Verification Check: Honest Answers

✓ **resume.json:** All entries are verifiable (offer letters, references, LinkedIn posts). Errors caught and fixed during attestation pass.  
✓ **profile.yml:** Visa constraints reflect actual documents. STEM eligibility confirmed with DSO.  
✓ **gaps.md:** All evidence is grounded in real demand signals (job postings, O*NET, observed patterns). No invented signals. Additional note: Student has practiced LeetCode SQL extensively and identifies SQL as one of strongest technical skills; SQL gap plan reflects this strength rather than a weakness area.

---

## Notes

- Search timeline is aggressive (land role within first 10 days of OPT eligibility to maintain 80-day buffer below 90-day ceiling).
- Two fintech projects discovered during exercise highlight importance of the attestation pass—agent extraction was incomplete.
- Agentic AI observability gap shows deepest understanding of role requirements; student wrote specific, actionable plan with verifiable metrics.

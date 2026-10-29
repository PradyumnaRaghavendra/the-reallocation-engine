# AI Use Disclosure — Setup Exercise: Your Search's Personal Layer

**Student:** Pradyumna Raghavendra  
**Date:** 2026-10-29  
**Course:** INFO 7375 — Computational Skepticism for AI  

---

## What AI Did

- **Resume extraction:** Converted PDF resume into structured JSON format with typed fields (company, title, dates, achievements, skills).
- **Profile drafting:** Generated initial `profile.yml` from my answers to intake questions (target role, visa constraints, geography, industry preferences).
- **Gaps identification:** Compared structured resume against typical MLE/Data Scientist role requirements in Fintech/Biotech sectors; drafted initial table with 7 gaps and proposed closing plans.
- **Framework & structure:** Provided the overall workflow and guidance for the attestation pass, gap editing, and verification check.

---

## What I Did

- **Attestation pass:** Reviewed extracted resume.json and identified three errors: (1) missing bullet point, (2) overstated contribution language, (3) missing project entries entirely.
- **Gap validation:** Verified that gaps were grounded in real demand signals (job postings, O*NET data, observed patterns) rather than invented from training data.
- **Corrections & clarifications:** Provided specific employee count ranges for mid-size vs startup companies; clarified that SQL is one of my strongest skills (LeetCode practice) rather than a gap area; confirmed visa status and DSO verification.
- **Gap rewriting:** Rewrote the agentic AI observability gap in my own words with specific understanding of what monitoring components matter (tracing, retrieval quality, hallucination detection, human-in-the-loop metrics, feedback loops) and why.
- **Gap deletion:** Identified and deleted the fintech domain knowledge gap because the AI had missed two completed fintech projects in the initial extraction.

---

## What the AI Could NOT Do — Specific Instances

1. **Missing project discovery:** The AI did not know about my Fraud Detection Model Evaluation project or Agentic Credit Decisioning & Collections Assistant until I mentioned them during the attestation pass. The initial extraction was incomplete, and only my domain knowledge caught this omission.

2. **A/B testing at Ahold Delhaize:** The AI could not know that I had conducted A/B testing on recommendation and personalization models during specific high-impact periods (winter-storm and Easter demand seasons). This required my firsthand recollection of the work I actually performed.

3. **Distinguishing strength from gap:** The AI initially listed SQL as a gap area ("no project uses SQL, no optimization or complex queries mentioned"). I corrected this: SQL is embedded in all my projects and is one of my strongest skills (reinforced by extensive LeetCode practice). The AI had no way to know this without my input.

4. **Deployed-but-unmonitored state:** The AI could not know that my Medical Assistant RAG project was actually deployed but lacked observability instrumentation. The gap was real, but only because I knew the project's actual deployment and monitoring status—the AI had to infer this from my resume.

5. **Company size preferences:** The AI conflated mid-size and startup company employee counts into a single generic range. Only I could clarify that mid-size (non-FAANG) means 400+, while funded startups mean 10-500. This distinction drove the engine's filtering logic.

---

## Methodology Notes

This exercise demonstrated the course's core claim: **extraction is fluent; you are the source of truth.** 

- The attestation pass wasn't bureaucratic overhead—it was the discipline of catching three real errors that the AI's confident extraction had embedded.
- The gap-editing process showed that an agent can draft a reasonable initial list, but only domain expertise (knowing my actual work, my visa status, my skill levels, my deployed systems) can validate whether the gaps are real or invented.
- The hardest part for the AI was the inverse problem: not knowing what it didn't know. I had to actively surface context (fintech projects, A/B testing, SQL strength) that the AI could not infer from my PDF resume.

---

## Summary

**Workflow:** AI extraction → my attestation and correction → AI revision → my validation.  
**Critical additions:** Two fintech projects, A/B testing details, clarified company size preferences, confirmed visa/DSO status.  
**Critical corrections:** Removed overstated language, adjusted SQL gap to reflect strength not weakness, killed inapplicable fintech domain gap.  

The three files submitted (resume.json, profile.yml, gaps.md) are verified records of my job search—not the agent's best guess, but my attested, corrected, and validated data.

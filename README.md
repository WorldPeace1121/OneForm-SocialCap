# OneForm-SocialCap

A Fil+ allocation channel powered by identity-linked forms and lightweight compliance

⸻

TL;DR
	•	What: A Fil+ allocator channel that routes DataCap via a unified “OneForm” intake and identity-linked social verification (SocialCap).
	•	Who: Storage Providers (SPs) and data clients with real-world use cases seeking predictable, auditable DataCap.
	•	How: KYB/KYC-lite + social-account binding + public application threads + rule-based scoring → staged DataCap releases.
	•	Why: Faster onboarding, transparent decisions, lower governance overhead, and verifiable accountability—separate and independent from the litekyc channel (content and decisions are isolated).

⸻

1) Overview

OneForm – SocialCap (OF-SC) is an allocator channel within the Fil+ program that standardizes intake, evaluation, and allocation. Applicants complete a single, structured form and bind official or org-verified social accounts (GitHub/X/website domain) to improve authenticity signals and reduce paperwork churn.

Key properties
	•	Unified intake: OneForm collects all essentials—entity info, dataset profile, SP pairing, retrieval plans, compliance attestations.
	•	Identity signals: Social account binding and organizational domain checks for low-friction trust.
	•	Transparent queue: Each request gets a public GitHub issue for tracking, discussion, and final verdict.
	•	Rule-based scoring: Clear rubric emphasizing real data, retrieval viability, client–SP fit, and openness.
	•	Staged allocation: DataCap is released in tranches tied to retrieval SLAs and proof-of-use.

Important: OF-SC is not the litekyc pathway. It has its own form, rubric, reviewers, and logs. Decisions in OF-SC do not inherit from or affect other channels.

⸻

2) Eligibility

Applicants should meet all of the below:
	•	Real data (or public-benefit datasets) with clear provenance and non-spam intent.
	•	Retrieval plan (HTTP/Graphsync/Bitswap) + endpoints or workflow that can be tested.
	•	Designated SP(s) willing to accept and serve the data; SPs must pass baseline ops checks.
	•	Identity signals: At least one org-traceable handle: verified website domain, verified X/Twitter org, GitHub org, or public company registry link.
	•	Compliance: Agree to OF-SC Terms, on-chain transparency, and periodic retrieval checks.

⸻

3) What We Prioritize
	•	Datasets with public value, research, or open-access goals.
	•	Usage evidence: documented consumers, APIs, or downstream apps.
	•	Sustainability: realistic size/ingestion plan; ongoing maintenance; retrieval readiness.
	•	Regional diversity and network health: reduce concentration risk across SPs/regions.

⸻

4) Apply (How It Works)
	1.	Fill OneForm (link placeholder): submit entity, dataset, SP(s), and retrieval plan.
	2.	Bind social accounts: verify at least one org-level identity signal.
	3.	Auto-created GitHub issue: your public application thread opens for reviewer Q&A.
	4.	Rubric scoring by reviewers (see §5).
	5.	Decision & tranche plan: initial DataCap tranche + milestones + retrieval checks.
	6.	Periodic reviews: pass retrieval checks → next tranche; fail → pause/adjust.

Expected timeline: Initial review target 5–10 business days from full submission (not guaranteed; complex cases may take longer).

⸻

5) Evaluation Rubric (100 pts)
	•	Identity & Authenticity (20): org signals, domain/email, prior activity.
	•	Dataset Value & Integrity (25): provenance, openness, community benefit, documentation.
	•	Retrieval Readiness (25): endpoints, bandwidth, success rates, testability.
	•	SP Fit & Redundancy (15): mapping to capable SPs; geographic and infra diversity.
	•	Operational Plan (15): ingestion schedule, maintenance, contactability, escalation.

Minimum passing score: 70. We may conditionally approve with smaller tranches.

⸻

6) Allocation & Tranches
	•	Initial Tranche: Sized to the first ingestion milestone.
	•	Follow-ups: Released after retrieval probes (randomized sub-piece checks) and milestone proofs.
	•	Ceilings/Rate Limits: May apply per applicant/SP to protect network balance.

⸻

7) Transparency & Logs
	•	All applications: public GitHub threads (redact sensitive info on request).
	•	Monthly reports: approved/denied counts, total DataCap, active tranches, retrieval stats.
	•	Conflicts of interest: declared by reviewers; conflicted reviewers abstain.

⸻

8) Retrieval Monitoring & SLAs
	•	Automated checks across HTTP/Graphsync/Bitswap (where applicable).
	•	Baseline success target: ≥ 80% over rolling window (dataset-dependent).
	•	If degraded: investigation → remediation plan → potential tranche pause/rollback.

⸻

9) Security & Privacy
	•	Data minimization: We only collect what the rubric requires.
	•	Public vs private: Sensitive docs can be shared privately; public threads reference “on file” materials.
	•	No resale of data: Application data used solely for Fil+ allocation governance.

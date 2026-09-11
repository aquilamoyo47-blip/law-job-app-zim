# AQUILA MOBILITY OS — COWORK HANDOFF

**Handoff date:** 11 September 2026  
**Primary objective:** move Aquila Moyo from Zimbabwe into legitimate international employment through a documented, evidence-gated operating system for applications, recruiter outreach, sponsorship/visa checks, CV tailoring, follow-up and interview conversion.

## What is already built

1. **Research corpus** covering cruise, UAE, UK, Germany, Australia, Canada, New Zealand, Malta and broader mobility routes.
2. **Candidate evidence pack** containing Aquila's CV and university transcript. Treat these as the factual boundary. Do not invent JITI Law Chambers duties.
3. **Command Centre spreadsheet** for applications, recruiters, documents, visa routes, budgets, rejection analytics, follow-ups, source register and agent queue.
4. **Mobility OS backend v0.1** — FastAPI + SQLite, lead state machine, evidence bank, CV family routing, recruiter outreach draft generation, Gmail/browser/proof adapters and tests.
5. **Web command-centre prototype** in `06_WEB_APP` with pipeline, jobs, approvals, CV routing, integrations and activity log.
6. Gmail account connection has been confirmed for **47aquilamoyo@gmail.com** and Mobility OS labels were created for Applications, Recruiters, Interviews, Offers & Visa, Follow-ups and Drafts.
7. GitHub account is connected. OpenAI Platform project exists. Supabase organization exists, but no dedicated production Mobility OS project has been created yet.

## State discipline — mandatory

Never confuse research with execution. Use these states exactly:

`DISCOVERED → VERIFIED_OPEN → QUALIFIED → CV_READY → HUMAN_REVIEW → APPROVED → SUBMITTED → CONFIRMED → FOLLOWUP_DUE → SCREEN → INTERVIEW → OFFER_VERIFY → VISA_PREP → OUTCOME`

Additional terminal/hold states: `REJECTED`, `CLOSED`, `QUARANTINE`.

A job is not **SUBMITTED** without real submission evidence. An inquiry is not **SENT** without a provider message ID or equivalent confirmation.

## Candidate facts that are safe to use

- LLB (Hons), Zimbabwe Ezekiel Guti University, degree conferred May 2026.
- Overall classification 2.1.
- Approximately five months Legal Attaché experience at JITI Law Chambers; detailed duties remain unverified and must NOT be invented.
- Voluntary Attaché / Secretary for Legal Affairs at Presidential Programme for Professionals — corporate governance, legal advice, document review, legal/policy analysis.
- Lead Innovator / Project Lead, Mutapa Sovereign AI — proposed/prototype local-first AI governance platform. Never imply completed national deployment.
- Strong moot, advocacy and public-speaking record.
- Interests: legal operations, compliance, AML/KYC/due diligence, regulatory operations, privacy/data protection, AI governance, responsible AI, legal technology, HR/People Ops and international mobility.
- Zimbabwean; employer-sponsored work permission required where applicable.

## Six CV families

1. Legal / Compliance / Regulatory
2. HR / People Operations
3. Cruise Crew Administration / Operations Support
4. General Administration / Guest Services / Operations
5. AI Governance / Privacy / Regulatory Technology
6. Hospitality / Customer Service — use only when job requirements can be matched without inventing service history.

## Immediate execution target

The strategic target is **100+ legitimate applications and 150+ legitimate recruiter/employer inquiries over a controlled campaign**, not fake or duplicate volume.

Do not mass blast identical messages. Segment, personalize, throttle, log, and follow up. Protect sender reputation.

## Connected-service posture

- **Gmail**: connected and usable. Draft-first until quality is validated. Record Gmail message ID on send.
- **GitHub**: connected. Use for source control and Codex handoff.
- **OpenAI Platform**: project exists; API secret must stay in server-side environment only.
- **Supabase**: organization exists; current projects seen are inactive. A dedicated Mobility OS database is still pending.
- **Canva**: no brand kit was found at the time of the handoff.
- **monday.com / Trello / Drive**: intended for CRM/approval/document-vault layers; creation was interrupted and remains pending.

## Browser automation policy

Automate discovery, navigation, prefill, tailoring and proof capture. Do **not** bypass CAPTCHA, Cloudflare, anti-bot controls, identity checks or legal declarations. Stop and hand control to Aquila at those checkpoints.

## Cowork execution order

1. Launch backend and web prototype locally.
2. Create dedicated Supabase project or reuse a clearly approved active project.
3. Migrate SQLite schema to Supabase/Postgres.
4. Create Drive document vault and upload/copy the evidence source files and CV families.
5. Build monday.com CRM / Trello approval queue.
6. Ingest current verified openings only from official or corroborated sources.
7. Generate six production CVs from the evidence bank.
8. Create the first 20-30 personalized Gmail drafts.
9. Human review; then send approved messages and log message IDs.
10. Browser-assist first verified applications, capture confirmation proof and update states.
11. Run daily rejection/reply analytics and adjust targeting.

## Definition of done for Day 1

- Dedicated source-of-truth DB exists.
- 25+ current roles are in `VERIFIED_OPEN` or `QUALIFIED` with source URLs and timestamps.
- Six CV masters exist in ATS-safe formats.
- 20-30 outreach drafts are ready for human review.
- At least 5 high-fit applications are `HUMAN_REVIEW` ready.
- No fabricated experience, no fake submission counts, no bypass attempts.

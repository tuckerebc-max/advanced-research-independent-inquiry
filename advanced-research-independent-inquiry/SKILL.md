---
name: advanced-research-independent-inquiry
description: Design, conduct, communicate, and defend bounded independent inquiry by formulating a focused question, synthesizing sources, selecting methods that fit the question, documenting ethics and evidence, analyzing findings, stating limitations, and revising claims. Use when Codex needs a research proposal, method memo, source synthesis, analysis plan, paper, presentation, defense, or QUEST extension. Do not use as a universal PhD standard, an IRB substitute, or a claim that a school project is publishable.
---

# Advanced Research and Independent Inquiry

## Outcome

Produce a transparent inquiry record connecting question, source corpus, method, evidence, analysis, limitations, ethics, communication, defense, and revision.

## Workflow

1. Contract the inquiry. Record question, domain, audience, purpose, consequence, available sources/data, method boundary, timeline, access, and ethics status. If the question is too broad or risky, return `NEEDS_INQUIRY_SCOPE`.
2. Formulate and situate. Narrow the question; review and synthesize relevant sources; identify perspectives, gaps, constructs, and plausible alternatives.
3. Justify method fit. Explain why the design, data/materials, measures, sampling, interpretation, and analysis fit the question. Distinguish transparency from replication.
4. Plan ethical work. Use fictional or low-risk data when approval is unavailable; document consent, privacy, risk, access, attribution, and stop/referral conditions. Never make an IRB or ethics determination on behalf of an institution.
5. Analyze and synthesize. Preserve raw/source links, assumptions, counterevidence, uncertainty, missingness, and alternative explanations. Do not overclaim from a method or sample.
6. Communicate and defend. Produce paper, report, presentation, poster, or oral defense for a named audience; answer questions with evidence and acknowledge limitations.
7. Reflect and revise. Record feedback, claim changes, method changes, disclosure, unresolved questions, and a next study or next inquiry.
8. Produce the learner artifact. Return proposal, search/source log, method memo, analysis notebook, findings/limitations memo, paper, defense record, and reflection.
9. Run QA. Check source locators, method fit, evidence integrity, ethics, limitations, authorship, accessibility, and domain-specific review needs.

## Guardrails

- AP Research, AP Seminar, QUEST, IB, National Academies, ACRL, and UNESCO sources are not silently generalized into one universal doctoral standard.
- Do not fabricate data, methods, results, ethics approval, citations, or participant consent.
- Use open/public or fictional materials; protect personal, clinical, educational, and confidential data.
- Escalate human-subjects research, clinical or legal questions, sensitive populations, high-impact decisions, and publication claims.

## Output contract

Return `inquiry_contract`, `question`, `source_synthesis`, `method_record`, `ethics_record`, `evidence_and_analysis`, `limitations`, `communication_artifact`, `defense_record`, `authorship_and_ai_log`, and `next_action` in the shared artifact envelope.

## Handoffs

- Route source and search work to `information-primary-source-literacy`.
- Route claim and evidence reasoning to `argumentation-reasoning-evidence`.
- Route postsecondary composition to `college-composition-postsecondary-writing`.

Read [construct-and-source-ledger.md](references/construct-and-source-ledger.md), [output-schema.json](references/output-schema.json), and [evaluation-fixtures.json](references/evaluation-fixtures.json) as needed.

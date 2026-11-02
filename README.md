# Case Study: AI Multilingual Translation for a K-12 AI Platform

**Role:** Product Owner, Encyclopaedia Britannica (Studio, an AI-powered K-12 instructional platform)
**Scope:** End-to-end ownership, from discovery through go-to-market and adoption tracking
**Outcome:** 350 new users in the first month and 52% feature engagement

*Details are limited to what was visible to customers or is already public on my resume. No confidential data, documents, or internal systems are included.*

---

## The Problem

Studio helps teachers generate instructional materials with AI, such as assessments, reading passages, and vocabulary lists. Feedback from surveys and user interviews before general availability kept surfacing the same pattern. Many U.S. schools and districts had large non-English-speaking student populations, but teachers could only generate content in English. That limited which students could actually use what teachers created.

## Discovery: Validating Before Building

The early feedback pointed to a real need, but it did not say which languages mattered most. Rather than guess, I:

- Ran competitive research on how other instructional tools handled multilingual content
- Led a dedicated round of surveys and interviews focused only on language needs
- Confirmed **Spanish and Portuguese** as the highest-demand languages across our largest market, U.S. districts

## Prioritization: Start Narrow, Prove Value

I scoped the launch to two languages instead of trying to support many at once. That kept the build small enough to ship quickly and let us measure real usage before investing in more languages.

## Key Product Decisions

**1. Translation as an action on finished content.** Teachers generate content in English first, then choose to translate it into Spanish, Portuguese, or both, and switch between versions easily. This kept the core workflow unchanged for teachers who did not need translation.

**2. Keeping translations in sync with teacher edits.** This was the hardest design problem. Teachers often edit AI output by rewording, deleting, or reordering questions. I chose to keep the English version as the single editable source, with translated versions read-only. When a teacher edits the English content, they explicitly choose to update the translations before saving.

- *Why not sync automatically on every edit?* It would have increased AI cost and risked content changing underneath a teacher mid-edit. An explicit choice kept teachers in control.
- *How we chose the design:* I tested several prototype options with teachers and picked the one they were least likely to miss.

**3. Re-translating the full document instead of patching edits.** Working with the AI team, we compared translating only the changed sections against re-translating the whole piece. Full re-translation was simpler to build, kept tone consistent across the document, and stayed cost-effective because the content was short.

**4. Managing wait time.** Translation added a noticeable delay, so we used the same progress screen teachers already knew from other tools, which kept the experience consistent.

## Delivery

- Wrote the user stories and acceptance criteria
- Partnered with design on placement and interaction
- Worked with the AI team on how content was sent for translation, so only the teacher's material was translated, not the surrounding page
- Worked with engineering on feasibility and timelines

## Go-to-Market

I presented the feature to Sales and Marketing myself, shaping the product story, the target districts to prioritize, and demo talking points. That way the feature launched with a clear message, not just a release note.

## Results

| Metric | Result |
|---|---|
| New users in month 1 | **350** |
| Feature engagement (active users who tried translation) | **52%** |

## What I Took Away

- Validate the specific answer, not just the general need. The earlier feedback showed demand, but a focused round of research decided the languages.
- Small, deliberate scope creates momentum. Two languages shipped faster and gave us real data for what to expand next.
- When AI changes content, users need to stay in control. Making sync an explicit choice built trust with teachers.

---

**Poonam Bhogale** | Product Manager | pbhogale73@gmail.com | [LinkedIn](https://www.linkedin.com/in/poonambhogale/)

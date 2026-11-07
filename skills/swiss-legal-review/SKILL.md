---
name: swiss-legal-review
description: Adversarial legal check of a Swiss small business (website, prices, privacy policy, marketing, AGB/contracts, staff, VAT) against current Swiss federal law, with a prosecutor agent, a defence agent and a judge synthesis. Use before publishing a website, AGB, offers or starting outreach in Switzerland.
---

# Swiss Legal Review (prosecutor × defence × judge)

You check a Swiss small business (Einzelunternehmen, GmbH, freelancer) against current Swiss federal law. You work in three roles: a **prosecutor** who looks for every possible violation, a **defence lawyer** who argues what the law really allows and proposes the smallest fix, and a **judge** (you, the main session) who decides and fixes what the business owns.

This is research and a checklist, **not legal advice**. Anything uncertain becomes a question for a Swiss lawyer.

## Hard rules
- Cite only law text you actually opened on **Fedlex** (fedlex.admin.ch, or the filestore fedlex.data.admin.ch when the page only returns a JavaScript shell) or on an official authority site (EDÖB, SECO, BAKOM, ESTV, BSV, IGE, cantonal offices). Mark every point **[V]** verified or **[I]** inference. Never quote an article from memory.
- Federal Supreme Court (BGer) case law counts as **[I]** unless the decision itself was opened (bger.ch, entscheidsuche.ch).
- Check the consolidation date of each law ("Stand"). Laws change; the date goes in the report.
- Do not soften the prosecutor and do not exaggerate the defence. A charge that holds stays a charge.
- Respect the user's data: write the case file without bank, ID or health data.

## Step 1 – Case file (`case.md`)
Collect the facts before any legal work. Ask only for what you cannot find in the files, website or tools you have.
- Legal form, owner, seat (canton), commercial register yes/no, UID, VAT registered yes/no, expected yearly turnover.
- Customers: businesses (B2B), consumers (B2C) or both. Languages and cantons served.
- Website: every claim about prices ("ab", "statt", "gratis", "ohne Setup", discounts, time limits), comparisons with competitors, promises (response times, rankings, guarantees), references/testimonials, demo or example content, Impressum, privacy policy, cookies/analytics, third-party scripts and fonts.
- Data flows: every provider that receives personal data (hosting, database, e-mail, CRM, chat/AI model, messengers, analytics, payment), with company name, country and safeguard (adequacy list, Swiss-US DPF certification, SCC).
- Marketing: e-mail outreach (how targets are found, volume, templates, approval, opt-out), calls, social media, ads, newsletters.
- Contracts: offer template, AGB, minimum terms, deferred payments, cancellation, rights of use, liability, place of jurisdiction.
- People: employees, family members, commissions or referral fees, foreign freelancers.
- AI: chatbots, automated replies, AI-generated content.

## Step 2 – Prosecutor (sub-agent)
Start a sub-agent with web access. Brief it with `case.md` and this role:

> You are a Swiss prosecutor and plaintiff's lawyer. Find EVERY possible violation, unenforceable clause or risk a competitor (UWG), a client, the EDÖB, SECO, the price office, AHV, tax or migration authorities could use. Open the official law texts and cite the URL. For each charge give: rule + URL, the concrete facts it hits, severity (high/medium/low), realistic consequence (civil, administrative, criminal), [V] or [I]. Do not soften.

Minimum checklist for the prosecutor: see `references/swiss-law-checklist.md`.

## Step 3 – Defence (sub-agent)
Start a second sub-agent with `case.md` and the prosecutor's charge sheet:

> You are a Swiss defence and business lawyer. For EACH charge: argue the strongest defence the law actually allows (open the sources, cite URLs, [V]/[I]), give an honest verdict (holds / partly holds / does not hold) and the minimal concrete fix that removes the risk but keeps the business model (exact wording for website, privacy policy, AGB, outreach process). End with a prioritised action list: today / before the first contract / before paying staff / can wait.

## Step 4 – Judge (you)
1. Build one table: charge · law · verdict · fix · status. Keep the prosecutor's severity and the defence's verdict visible.
2. **Fix right away what the business owns and the user asked you to change** (website text, privacy policy, AGB draft, bot prompts). Never publish or deploy without the user's go-ahead.
3. List what needs the owner (registrations, insurance, contracts with people) and what needs a lawyer (open legal questions, BGer case law, final AGB).
4. Report in the user's language: short summary, the table, then three lists (done, owner, lawyer). Sources at the end.

## Output files
- `case.md` – facts.
- `charges.md` – prosecutor.
- `defence.md` – defence.
- `review.md` (or a shared doc) – judge table, fixes, lawyer questions.

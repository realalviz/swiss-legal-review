# Swiss law checklist for small businesses

Open every text before citing it. If a Fedlex page only shows a JavaScript shell, use the Fedlex filestore version (fedlex.data.admin.ch) of the same ELI. Note the consolidation date ("Stand").

## Laws and sources

| Area | Law | Link |
|---|---|---|
| Contracts | OR – Obligationenrecht (SR 220) | https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de |
| Unfair competition | UWG (SR 241) | https://www.fedlex.admin.ch/eli/cc/1988/223_223_223/de |
| Price display | PBV (SR 942.211) | https://www.fedlex.admin.ch/eli/cc/1978/2081_2081_2081/de |
| Data protection | DSG (SR 235.1) | https://www.fedlex.admin.ch/eli/cc/2022/491/de |
| Data protection ordinance | DSV (SR 235.11), Annex 1 = countries with adequate protection | https://www.fedlex.admin.ch/eli/cc/2022/568/de |
| Cookies / local storage | FMG Art. 45c (SR 784.10) | https://www.fedlex.admin.ch/eli/cc/1997/2187_2187_2187/de |
| Consumer credit | KKG (SR 221.214.1) | https://www.fedlex.admin.ch/eli/cc/2002/593/de |
| Place of jurisdiction | ZPO (SR 272) | https://www.fedlex.admin.ch/eli/cc/2010/262/de |
| VAT | MWSTG (SR 641.20) | https://www.fedlex.admin.ch/eli/cc/2009/615/de |
| Social insurance | AHVV (SR 831.101) | https://www.fedlex.admin.ch/eli/cc/63/1185_1183_1185/de |
| Undeclared work | BGSA (SR 822.41) | https://www.fedlex.admin.ch/eli/cc/2007/71/de |
| Foreign nationals | AIG (SR 142.20) | https://www.fedlex.admin.ch/eli/cc/2007/758/de |
| Commercial register | HRegV (SR 221.411) | https://www.fedlex.admin.ch/eli/cc/2007/686/de |
| Swiss-US Data Privacy Framework list | dataprivacyframework.gov | https://www.dataprivacyframework.gov/list |
| AI and data protection | EDÖB | https://www.edoeb.admin.ch/ |
| Mass advertising by e-mail | BAKOM | https://www.bakom.admin.ch/de/wann-ist-der-massenversand-erlaubt |
| EU AI Act (EU visitors) | Regulation (EU) 2024/1689, Art. 50 | https://eur-lex.europa.eu/legal-content/DE/TXT/HTML/?uri=CELEX:32024R1689 |

## What to check (typical findings)

### Contracts and AGB (OR)
- **Art. 404 OR**: a mandate (Auftrag: support, maintenance, consulting) can be ended by either party at any time; per BGer this is mandatory. A plain "minimum term" for a service may not hold. Safer: separate the work (Werkvertrag, Art. 363 ff.) with its own price, deferred payment if needed; hosting/licence with a fixed term; services with Art. 404 reserved.
- **Art. 160–163 OR**: amounts due on early termination can be treated as a penalty and reduced by the court. Never trigger them when the business itself is at fault.
- **Art. 367, 370 OR**: acceptance clauses cannot cover hidden defects.
- **Art. 82 OR**: blocking a service while the client lawfully withholds payment for defects is risky.
- **Art. 100 OR**: liability for gross negligence and intent cannot be excluded.
- **Art. 104 OR**: 5 % default interest.
- **ZPO Art. 32, 35**: place of jurisdiction clauses do not bind consumers.
- **Ungewöhnlichkeitsregel / UWG Art. 8**: surprising or unbalanced AGB clauses against consumers fail. Put important rules in the signed offer, in bold.

### Advertising and prices (UWG, PBV)
- **UWG Art. 3 Abs. 1 lit. b, i**: misleading price statements. Example: "no setup fee" while the setup price is hidden in the monthly fee or due on early exit. Say "no upfront payment, build included, fixed term X months, total CHF Y".
- **PBV Art. 16 / UWG lit. b**: "statt"/strike-through prices only if that price was really charged (or as a labelled introductory price, max. 2 months, then really charged). PBV applies to consumer offers; UWG applies to everyone.
- **UWG lit. e**: comparisons with competitors ("rarely elsewhere", "cheaper than") must be accurate and provable (burden of proof, Art. 13a).
- **Unprovable promises**: response times, rankings ("ready for AI search"), "gratis" next to a long lock-in, fake or example references presented as clients.
- **UWG lit. s**: Impressum with name/firm, postal address, e-mail.
- **UWG lit. o**: mass advertising by e-mail/SMS needs prior consent – no B2B exception. Individually written, individually relevant e-mails to a business's published address, in small numbers, with opt-out, are the defensible practice. **lit. u**: respect the "star" (no advertising) in directories; scope beyond calls is disputed.
- Criminal side: UWG Art. 23 (on complaint), PBV fines via UWG Art. 24.

### Data protection (DSG, DSV, FMG)
- **DSG Art. 19–21**: the privacy policy must list the controller, data, purposes, recipients (categories), countries and safeguards. It must match reality (analytics, e-mail provider, CDN, AI model, messengers).
- **DSG Art. 16–17, DSV Annex 1**: transfers abroad only to adequate countries, to Swiss-US DPF certified US companies, with SCC, or under an Art. 17 exception (e.g. data the person made public, Art. 17 Abs. 1 lit. e). Check each US provider on the DPF list. Messengers based outside adequate countries (e.g. for internal lead notifications) are a frequent gap: send only an ID, keep data in the database.
- **DSG Art. 9**: when the business processes its clients' customer data it is a processor: data processing agreement (ADV), sub-processors only with the client's prior approval.
- **DSG Art. 19 Abs. 5**: prospects whose data comes from public sources must be informed (at the latest at first contact): source, purpose, opt-out.
- **DSG Art. 60–61**: fines up to CHF 250'000 for intentional breaches of information duties and transfer rules, on complaint.
- **FMG Art. 45c**: local storage/cookies: inform and allow refusal.
- **AI**: tell users they are talking to a machine, offer a human; EU visitors: AI Act Art. 50.

### People, social insurance, tax
- **AHVV Art. 7 lit. g**: commissions are wages. **Art. 34d**: below CHF 2'500 per person and year only on request, except e.g. design or cultural businesses. Register as employer, accident insurance (UVG), written agreement (agent contract OR 418a if truly independent).
- **BGSA Art. 2 Abs. 2 lit. b**: the simplified procedure excludes the spouse.
- **AIG Art. 117**: employing someone without work permission is criminal.
- **MWSTG Art. 10**: VAT from CHF 100'000 turnover (check prospectively with recurring contracts); **Art. 45**: reverse charge on services from abroad above CHF 10'000 per year. Put a VAT clause in long contracts.
- **OR Art. 931**: commercial register from CHF 100'000 turnover; **OR 945**: sole trader's firm must contain the family name – use it on offers and invoices.
- Foreign freelancers: data transfer (SCC), written assignment of copyright, NDA.

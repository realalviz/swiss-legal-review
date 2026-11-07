# Swiss Legal Review – AI skill & prompt for Swiss small businesses

An open-source **Agent Skill** (Claude Code / Claude Cowork / any agent that reads `SKILL.md`) and a **copy-paste prompt** that check a Swiss small business against current Swiss federal law – website, prices, privacy policy, e-mail marketing, AGB, staff and VAT.

It works like a mock trial:

1. **Prosecutor** – looks for every possible violation (UWG, PBV, DSG, OR, AHV…).
2. **Defence** – argues what the law really allows and proposes the smallest fix.
3. **Judge** – one table with verdicts, fixes, and the open questions for your lawyer.

Every legal point must be checked on **Fedlex** (the official federal law portal) and marked *verified* or *inference*.

> ⚠️ **Not legal advice.** This is a structured risk check that helps you prepare. Final contracts and AGB should be reviewed by a Swiss lawyer.

## Typical findings
- "No setup fee" while the setup price is hidden in the subscription → misleading price (UWG Art. 3 lit. b/i).
- "CHF 2'490 instead of 3'490" without ever selling at 3'490 → comparison price (PBV Art. 16, UWG).
- "Minimum term 24 months" for maintenance services → may not hold against Art. 404 OR.
- Privacy policy that says "no analytics" while analytics run, or omits US providers and messengers (DSG Art. 19, 16–17).
- Cold e-mails to businesses → no B2B exception in UWG Art. 3 lit. o.
- Commissions paid to family or friends → AHV wages (AHVV Art. 7 lit. g).

## Use it

### Option A – Agent Skill (Claude Code / Cowork)
Copy the folder `skills/swiss-legal-review/` into your skills directory (e.g. `~/.claude/skills/`), then ask:
> "Run a Swiss legal review of my business / my website example.ch."

### Option B – Prompt (any AI chat)
Open [`PROMPT.md`](PROMPT.md), copy it into your assistant, and fill in your business facts.

## Files
| File | What it is |
|---|---|
| `skills/swiss-legal-review/SKILL.md` | The skill: workflow with prosecutor, defence and judge sub-agents |
| `skills/swiss-legal-review/references/swiss-law-checklist.md` | Laws with Fedlex links and typical pitfalls |
| `PROMPT.md` | Standalone prompt |

---

## Deutsch
KI-Skill und Prompt für Schweizer KMU und Selbständige: prüft Website, Preise, Datenschutzerklärung, E-Mail-Akquise, AGB, Personal und MWST gegen das geltende Bundesrecht – mit Ankläger, Verteidiger und Richter. Quellen nur aus Fedlex. **Keine Rechtsberatung**; AGB vor der Verwendung von einer Anwältin oder einem Anwalt prüfen lassen.

## Français
Skill IA et prompt pour PME et indépendants en Suisse : vérifie site web, prix, déclaration de protection des données, prospection par e-mail, CG, personnel et TVA selon le droit fédéral en vigueur – avec procureur, défense et juge. Sources uniquement sur Fedlex. **Pas un conseil juridique** ; faites relire vos CG par un avocat.

## Italiano
Skill IA e prompt per PMI e indipendenti in Svizzera: controlla sito web, prezzi, informativa sulla privacy, acquisizione via e-mail, CG, personale e IVA secondo il diritto federale vigente – con accusa, difesa e giudice. Fonti solo da Fedlex. **Non è una consulenza legale**; fate verificare le CG da un avvocato.

---

Made in Grenchen by **GOAT TECH** – [goattech.ch](https://goattech.ch). Contributions welcome: open an issue or pull request (e.g. cantonal rules, new case law, translations).

License: MIT

# Accountant Plugin for Claude

Draft tax return summaries, tax-planning memos, engagement letters, and IRS notice responses — with current-law verification and practice-boundary guardrails built in.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/accountant) — AI tools, guides, and weekly digests designed specifically for accountants, CPAs, and EAs.

> **Bookkeeper too?** This plugin leans into tax and advisory work. For monthly close, reconciliations, and day-to-day client bookkeeping comms, see the companion **Bookkeeper** plugin.

## Commands

| Command | Description |
|---------|-------------|
| `/tax-return-summary` | Turn a filed 1040 result into a warm, plain-language client summary letter — without inventing a figure |
| `/tax-planning-memo` | Draft year-end or quarterly planning ideas, framed for verification rather than as guarantees |
| `/engagement-letter` | Define scope, fees, responsibilities, and boundaries for an accounting or tax engagement |
| `/irs-notice-response` | Draft a calm, professional cover letter responding to a routine IRS notice (CP2000, CP14, CP504) |

## Skills

This plugin includes skills that activate automatically when you're working on accounting and tax tasks:

- **Tax Advisory** — Individual and small-business tax planning, entity considerations, deductions, and deadlines — with a verify-first rule that turns any unsupplied citation, deadline, threshold, or figure into a verify-placeholder instead of an assertion
- **CPA Practice Standards** — Current-law verification, practice-boundary routing (legal / securities / investment / audit-defense-beyond-scope / assurance / credential limits), and client-data privacy — appended as a short flag on the narrow surfaces where it matters

## Usage examples

```
/tax-return-summary
Client: Priya Nair. Tax year 2025. Return type: 1040 joint + state.
Federal: refund of $2,140. State: balance due of $310.
Notable this year: first year with the new baby (added dependent); Priya
maxed her 401(k); sold some stock at a modest gain.
Next year: they'll want to revisit estimated payments if her side income grows.
Leave anything I didn't give you as a placeholder.
```

```
/tax-planning-memo
Client: Delgado Design LLC (S-Corp, 1 owner). Year-end planning for 2025.
Situation: net income up about 30% over last year; owner wants to know about
retirement options and whether reasonable comp is set right.
Ideas to cover: Solo 401(k) vs SEP, reasonable-comp review, year-end equipment
timing. Frame as ideas to evaluate — don't quote current limits, flag them to verify.
```

```
/engagement-letter
Firm: Northline Tax & Advisory. Client: Priya Nair.
Engagement: individual tax prep, 2025 (federal + state).
Included: 1040 prep, one state return, e-file. Excluded: bookkeeping, audit
representation, entity returns. Fee: $650 fixed, due at delivery.
```

```
/irs-notice-response
Client: Delgado Design LLC. Notice CP2000 dated last month, tax year 2023.
The notice proposes additional tax from a 1099-NEC the IRS says wasn't reported.
We partially disagree: $4,000 of it was reported on a different line; $1,200
was a duplicate 1099 the payer already corrected. Attaching the corrected 1099
and the return excerpt. Deadline is 30 days from the notice date. I have a 2848 on file.
```

## Disclaimer

This output is a professional draft — verify every figure against the return, and every citation, deadline, and threshold against current law, before sending. This plugin is not legal, investment, or assurance/attestation advice; it routes those to the right professional.

## Install

In Claude Cowork or Claude Code (plugin installs need a paid Claude plan — Pro, Max, or Team):

```
/plugin marketplace add alexclowe/awesome-claude-cowork-plugins
/plugin install accountant@awesome-claude-cowork-plugins
```

## More resources

- **Profession hub** — Free tools, guides, and the AI Career Lab pillar guide for accountants: https://theaicareerlab.com/professions/accountant
- **Accountant AI Prompts** — 60 agentic skills for tax-prep workflow, advisory, planning, IRS controversy, and client comms, with built-in current-law and practice-boundary guards. The done-for-you version of this workflow, $19 one-time: https://clowealex.gumroad.com/l/accountant-ai-prompts?ref=plugin-accountant
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=accountant
- **Weekly AI Digest** — Curated AI updates for accountants: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/accountant) on AI Career Lab give you five runs a day on a free account — no credit card required.

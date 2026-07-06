# Contractor Plugin for Claude

Draft line-item estimates, change orders, scopes of work, and client updates — with license and lien guardrails built in.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/contractor) — AI tools, guides, and weekly digests designed specifically for contractors, remodelers, and trades.

## Commands

| Command | Description |
|---------|-------------|
| `/project-estimate` | Turn a scope description into a phase-organized, line-item estimate — without inventing a single price |
| `/change-order` | Write a one-page change order for a mid-job scope change, with cost impact and a signature line |
| `/scope-of-work` | Turn a job description into a clear, itemized scope of work that prevents disputes |
| `/client-update` | Write a clear, reassuring client progress update from a few field notes |

## Skills

This plugin includes skills that activate automatically when you're working on contractor tasks:

- **Estimating & Scope** — Construction estimating structure, allowances and selections, scope/exclusions discipline, change-order structure, and markup vs. margin — with the rule that the assistant never invents a price or does the math
- **Contractor Compliance** — License display, mechanic's lien rights, permits and code verification, insurance-certificate language, and no-guarantee language — appended as a short "before sending" check on the high-cost surfaces

## Usage examples

```
/project-estimate
Kitchen remodel for Dana. Single-family, ~180 sqft kitchen.
Scope: demo existing kitchen; rough-in for relocated sink; new cabinets
(customer-provided); quartz counters; tile backsplash; LVP flooring; paint.
Sub needed: electrician for added circuits. Permit required.
Labor: my rate is $65/hr, estimated 90 hrs. Demo: $1,800. Electrician sub
bid: $2,400. Flooring materials: $2,100. Backsplash tile: allowance $1,500.
Timeline: about 3 weeks. Leave anything I didn't price as a placeholder.
```

```
/change-order
Project: Dana kitchen remodel. Change order #1. Today's date.
Original contract: $28,500. Reason: opened the north wall during demo and
found knob-and-tube wiring that has to be replaced to pass inspection.
Scope added: replace ~30 ft of knob-and-tube, add one junction box.
Cost impact: $1,650 (electrician). Schedule impact: 2 days.
```

```
/scope-of-work
Bathroom remodel for Chris. Included: demo, new tub/shower, tile surround,
new vanity, toilet, LVP floor, paint. Excluded: moving plumbing walls,
mold remediation, structural work. Customer provides: vanity and fixtures.
Allowance: $600 for tile. Permit: I pull it. Selections due before demo.
```

```
/client-update
Project: Chris bathroom. This week: finished demo and rough-in, passed the
plumbing inspection. Next: tile starts Monday, should take 3 days.
Need from Chris: final grout color by Friday. On track overall.
```

## Disclaimer

This output is a professional draft — verify all figures, math, permits, and license requirements before sending. This plugin is not legal advice; route lien, license, and contract-form questions to your attorney.

## Install

In Claude Cowork or Claude Code (plugin installs need a paid Claude plan — Pro, Max, or Team):

```
/plugin marketplace add alexclowe/awesome-claude-cowork-plugins
/plugin install contractor@awesome-claude-cowork-plugins
```

## More resources

- **Profession hub** — Free tools, guides, and the AI Career Lab pillar guide for contractors: https://theaicareerlab.com/professions/contractor
- **Contractor AI Prompts** — 50 agentic skills for estimating, change orders, project ops, client comms, and marketing, with a built-in license/lien guard. The done-for-you version of this workflow, $9 one-time: https://clowealex.gumroad.com/l/contractor-ai-prompts?ref=plugin-contractor
- **AI Readiness Audit** — 2-minute score for your business: https://theaicareerlab.com/audit?profession=contractor
- **Weekly AI Digest** — Curated AI updates for contractors: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/contractor) on AI Career Lab give you five runs a day on a free account — no credit card required.

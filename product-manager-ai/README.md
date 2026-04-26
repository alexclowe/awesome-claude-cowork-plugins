# AI Product Manager Plugin for Claude

Spec AI features, evaluate regulatory risk, plan staged rollouts, and turn user feedback into the next sprint.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/product-manager-ai) — AI tools, guides, and weekly digests designed specifically for AI product managers.

## Commands

| Command | Description |
|---------|-------------|
| `/draft-ai-spec` | Generate a product spec for an AI feature with scope, acceptance criteria, eval plan, and risk mitigations |
| `/evaluate-ai-risk` | Assess a feature against EU AI Act high-risk categories, FINRA agent rules, and FDA classification; flag gates |
| `/plan-rollout` | Design staged rollout: cohort selection, success metrics, kill criteria, comms plan |
| `/analyze-user-feedback` | Cluster AI-related issues from tickets and Slack; recommend the next sprint's top 3 fixes |

## Skills

This plugin includes skills that activate automatically when you're working on AI product tasks:

- **AI Readiness Assessment** — Audit internal infrastructure for AI launch (data quality, governance, ML platform, security review SLA)
- **Competitive Benchmarking** — Scan competitors' AI launches, flag feature gaps, benchmark pricing and positioning

## Usage examples

```
/draft-ai-spec
Feature: AI meeting summarizer for Sales reps inside our CRM. Scope: post-call
auto-summary, action-item extraction, push to Salesforce. Constraints: no PHI,
must redact PII, runs <60s. Need acceptance criteria, eval plan, and risk
mitigations.
```

```
/evaluate-ai-risk
Feature: AI agent that can place trades on behalf of retail brokerage users
within pre-set guardrails. Markets: US + EU. Need EU AI Act classification,
FINRA Reg BI / agent rules analysis, and a list of gates we must clear before
launch.
```

```
/plan-rollout
Rolling out AI meeting summarizer to 800 sales reps. Pick the cohort waves,
define kill criteria, success metrics, and a comms plan for managers.
Constraint: regulated customers in 12% of accounts must be excluded from
wave 1.
```

```
/analyze-user-feedback
650 support tickets and 1,200 Slack messages from the last 30 days mentioning
our AI assistant. Cluster the issues, separate model quality from UX, and
recommend the top 3 fixes for next sprint with rough effort and impact.
```

## Disclaimer

This plugin generates drafts for product manager review. AI risk classifications and regulatory analyses produced here are starting points only — final regulatory decisions require legal, compliance, and security review specific to your jurisdiction and product. Always validate against current EU AI Act guidance, FINRA notices, FDA guidance documents, and your company's compliance policy before launch.

## More resources

- **Profession hub** — Free tools, guides, and pillar guide for AI product managers: https://theaicareerlab.com/professions/product-manager-ai
- **Claude Cowork playbook** — How to set up Claude as your daily co-worker: https://theaicareerlab.com/resources/claude-cowork-product-manager-ai
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=product-manager-ai
- **Weekly AI Digest** — Curated AI updates for AI product managers: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/product-manager-ai) on AI Career Lab give you five runs a day on a free account — no credit card required.

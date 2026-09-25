# Founder Plugin for Claude

Plan the week, write the monthly update, synthesize customer interviews, and sequence a launch — for a one-person company.

Built by [The AI Career Lab](https://theaicareerlab.com) — AI tools, guides, and weekly digests for people who run their own business.

## Commands

| Command | Description |
|---------|-------------|
| `/weekly-plan` | Turn last week's brain-dump into a short retro and next week's plan — exactly three bets, each with a done-check and its riskiest assumption |
| `/monthly-update` | Write an honest investor-style monthly update — metrics, what shipped, what didn't and why, the real risk, specific asks |
| `/interview-synthesis` | Synthesize customer interview notes into ranked themes, attributed quotes, implications, and what to ignore |
| `/launch-plan` | Build a day-by-day launch checklist sequenced backward from your launch date, with the reason behind every step |

## Skills

This plugin includes skills that activate automatically when you're working on founder tasks:

- **Operating Rhythm** — Weekly retros, three-bet weekly plans, honest monthly updates, and metric discipline
- **Shipping Discipline** — Scope checks that cut v1 to the feature that tests the riskiest assumption, and a validation check before anything goes public

## Usage examples

```
/weekly-plan
Last week: shipped the CSV import, fixed the onboarding email bug. Stuck on the
Stripe webhook retries. Learned: two trial users churned because setup took 40 min.
The number: 312 weekly active users (was 298). Fixed next week: Tuesday 2pm call
with an accountant about taxes; Friday off. About 20 focused hours available.
Ideas competing: onboarding checklist, referral program, blog post, pricing page redo.
```

```
/monthly-update
August 2026 update for my bookings app. MRR $4,180 (was $3,760). Paying customers
61 (was 55). Shipped: calendar sync, SMS reminders, new pricing page. Didn't ship:
team accounts — underestimated permissions work. Next month: team accounts, cut
setup time in half, 10 customer calls. Ask: intro to someone who runs a multi-location salon.
```

```
/interview-synthesis
Five interviews with salon owners, notes pasted below. Hypothesis: owners will pay
more for automated no-show deposits.
```

```
/launch-plan
Launching a Chrome extension that summarizes long email threads. Launch date:
Tuesday, November 10. Channels: Product Hunt, Hacker News, my X account (2,100
followers), email list of 640. About 3 hours a day available.
```

## Disclaimer

Outputs are drafts for your review. They use only the numbers you provide — check every figure, date, and platform rule before you send or publish.

## Install

In Claude Cowork or Claude Code (plugin installs need a paid Claude plan — Pro, Max, or Team):

```
/plugin marketplace add alexclowe/awesome-claude-cowork-plugins
/plugin install founder@awesome-claude-cowork-plugins
```

## More resources

- **Founder AI Operating System** — 49 skills that run five whole jobs for a one-person company: plan my week, triage support and feedback, ship a feature, write my monthly update, and review revenue and churn. From a command center, as drafts you approve. $19 one-time: https://clowealex.gumroad.com/l/founder-ai-prompts?ref=plugin-founder
- **AI Readiness Audit** — 2-minute score for how you work: https://theaicareerlab.com/audit
- **Weekly AI Digest** — Curated AI updates: https://theaicareerlab.com/newsletter

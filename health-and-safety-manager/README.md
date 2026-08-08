# Health & Safety Manager Plugin for Claude

Draft incident write-ups, job hazard analyses, toolbox talks, inspection checklists, and corrective-action logs — so the paperwork stops being the reason findings sit open.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/health-and-safety-manager) — AI tools and guides designed specifically for EHS and HSE professionals.

## Commands

| Command | Description |
|---------|-------------|
| `/incident-report` | Draft a de-identified incident write-up from your notes — factual sequence, conditions, and contributing factors, with no blame language and no legal conclusions |
| `/toolbox-talk` | Build a five-minute toolbox talk from a topic, a season, or a recent incident — written in plain language for the crew who has to act on it |
| `/job-hazard-analysis` | Break a task into steps, surface the hazard at each step, and propose controls ordered by the hierarchy of controls rather than defaulting to PPE |
| `/safety-audit-checklist` | Generate an inspection checklist for a specific area or activity — observable checks, evidence to look for, and space to record findings |
| `/corrective-action-log` | Turn inspection findings, incident actions, and audit observations into a tracked corrective-action log with owners, due dates, and verification steps |

## Skills

This plugin includes skills that activate automatically when you're working on safety documentation:

- **Hazard Communication Style** — worker-facing safety writing conventions: plain language, imperative actions tied to the moment they apply, concrete mechanisms of harm without fear tactics, and material that opens a conversation instead of lecturing the room
- **Regulatory Caution** — the guardrails: never certify compliance, cite regulations as pointers marked `[verify current requirements]`, keep incident drafts factual with no fault or legal conclusions, and put statutory reporting obligations ahead of any draft

## Usage examples

```
/incident-report
Night shift, second-shift operator caught a glove in the infeed roller on
line 3 while clearing a jam. Guard interlock was found bypassed — unclear
for how long. Minor hand laceration, treated on site, no lost time. Jam
clearing isn't in the written procedure. Draft the write-up.
```

```
/toolbox-talk
We had a near miss on Tuesday — a reversing forklift and a pedestrian in
the loading bay, no contact. Mixed crew, some seasonal hires, about half
are not first-language English speakers. Five minutes at Monday start.
```

```
/job-hazard-analysis
Changing the blade on the panel saw. Two people, done about weekly.
Currently we lock out the disconnect and use cut-resistant gloves.
The blade is heavy enough that it's usually a two-person lift.
```

```
/corrective-action-log
Here are 14 findings from yesterday's warehouse walk: damaged racking
upright aisle 4, two blocked fire exits, expired eyewash station
inspection tag, forklift with a cracked mast guard, pallets stacked
above the rack line in three bays... Turn these into a tracked log.
```

## Disclaimer

This plugin drafts safety documentation. It does not provide legal, regulatory, or professional safety advice, and it does not determine compliance. Every output is a working draft requiring review by a qualified safety professional and verification against the site's actual conditions and applicable requirements. Regulations vary by jurisdiction and change over time — verify every requirement against a current authoritative source. Nothing this plugin produces replaces an incident investigation, professional judgment, or a statutory reporting obligation: report serious incidents to your regulator on their required timeline without waiting on any draft.

## Install

In Claude Cowork or Claude Code (plugin installs need a paid Claude plan — Pro, Max, or Team):

```
/plugin marketplace add alexclowe/awesome-claude-cowork-plugins
/plugin install health-and-safety-manager@awesome-claude-cowork-plugins
```

## More resources

- **Profession hub** — Free tools, guides, and the AI Career Lab pillar guide for health & safety managers: https://theaicareerlab.com/professions/health-and-safety-manager
- **Claude Cowork playbook** — How to set up Claude as your daily co-worker: https://theaicareerlab.com/resources/claude-cowork-health-and-safety-manager
- **Health & Safety Manager AI Prompts — coming soon.** Want the done-for-you setup (prompts, templates, and a ready-to-use Claude Project)? Join the waitlist and we'll email you the moment it ships: https://theaicareerlab.com/waitlist/health-and-safety-manager
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=health-and-safety-manager
- **Weekly AI Digest** — Curated AI updates for health & safety managers: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/health-and-safety-manager) on AI Career Lab give you five runs a day on a free account — no credit card required.

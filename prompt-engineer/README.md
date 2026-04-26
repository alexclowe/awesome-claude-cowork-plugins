# Prompt Engineer Plugin for Claude

Build evals, A/B test prompts, audit skills, and benchmark LLM outputs at production quality.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/prompt-engineer) — AI tools, guides, and weekly digests designed specifically for prompt engineers.

## Commands

| Command | Description |
|---------|-------------|
| `/eval-rubric` | Build a custom evaluation rubric for a skill or prompt covering accuracy, tone, compliance, and latency |
| `/test-batch` | Run a prompt against 10–100 synthetic test cases and produce a coverage and quality report |
| `/skill-version` | Version-control a skill, A/B test two variants, and output a statistical-significance verdict |
| `/skill-audit` | Static analysis of a SKILL.md: frontmatter, edge cases, prompt-injection surface, and length budget |

## Skills

This plugin includes skills that activate automatically when you're working on prompt-engineering tasks:

- **Prompt Optimization Loop** — Test case design, edge cases, adversarial inputs, and iteration based on eval results
- **Skill Benchmarking** — Latency, accuracy, token cost, and token-budget compliance measurement across skill variants

## Usage examples

```
/eval-rubric
Skill: customer-support-triage. Goals: route ticket to right team, draft empathetic
reply, never make refund promises. Build a rubric covering accuracy, tone, compliance,
and latency with weighted scoring.
```

```
/test-batch
Generate 50 synthetic test cases for my "/draft-cold-email" prompt. Mix legitimate
prospects, edge cases (non-English names, empty company field), and adversarial inputs
(prompt injection attempts). Run them and produce a coverage report.
```

```
/skill-version
Compare skill variant A (current production) vs variant B (new draft) on the same
40-case eval set. A/B test with paired bootstrap resampling. Output verdict with
p-value and effect size.
```

```
/skill-audit
Audit this SKILL.md: check frontmatter completeness, flag prompt-injection surface,
verify edge cases are addressed, and report token-budget compliance against a 2000-token
target.
```

## Disclaimer

This plugin produces drafts of evaluation rubrics, test cases, and statistical analyses. Statistical verdicts are based on the samples and methods you provide — small sample sizes or biased test sets will produce misleading results. The prompt engineer is responsible for validating eval design, reviewing flagged failures manually, and confirming that automated judges align with human judgment before relying on benchmarks for production decisions.

## More resources

- **Profession hub** — Free tools, guides, and pillar guide: https://theaicareerlab.com/professions/prompt-engineer
- **Claude Cowork playbook** — How to set up Claude as your daily co-worker: https://theaicareerlab.com/resources/claude-cowork-prompt-engineer
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=prompt-engineer
- **Weekly AI Digest** — Curated AI updates for prompt engineers: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/prompt-engineer) on AI Career Lab give you five runs a day on a free account — no credit card required.

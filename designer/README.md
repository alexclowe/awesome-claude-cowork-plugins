# Designer Plugin for Claude

Build AI-augmented design systems, critique designs, batch iterations, and ship dev-ready handoff specs.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/designer) — AI tools, guides, and weekly digests designed specifically for designers.

## Commands

| Command | Description |
|---------|-------------|
| `/design-system` | Capture brand colors, typography, spacing, and component patterns into a complete DESIGN.md ready for Claude Design |
| `/design-critique` | Evaluate a design against accessibility (WCAG 2.2), brand consistency, and layout principles |
| `/design-iterate` | Plan token-efficient batch iterations: which slots to lock, what to vary, target outputs |
| `/design-export` | Generate dev-handoff specs: component inventory, design tokens, interaction states, redlines |

## Skills

This plugin includes skills that activate automatically when you're working on design-related tasks:

- **Brand Voice Design** — Maintain consistent visual and verbal tone across outputs; resist generic Claude Design defaults
- **Accessibility Audit** — WCAG 2.2 contrast, focus states, keyboard nav, and screen reader semantics flagged before handoff

## Usage examples

```
/design-system
Brand: fintech app called Lumen. Primary blue #2563EB, neutral grays,
Inter for UI, Fraunces for marketing. 8pt grid. Components: button,
input, card, modal, toast. Capture into DESIGN.md.
```

```
/design-critique
Critique this checkout screen: white card on white background, primary
CTA #6366F1 on #818CF8, 14px body copy, no focus rings. Mobile only.
Flag WCAG 2.2 issues, brand drift, and layout problems.
```

```
/design-iterate
We have 6 hero variants approved. Need to test 3 CTA copy options across
2 image treatments without redesigning the hero. Plan a batch run that
locks layout tokens and varies only copy + image style.
```

```
/design-export
Hand off the dashboard navigation component. States: default, hover,
active, focus, disabled. Tokens use our spacing-4, color-primary-600,
radius-md. Generate a redline + interaction spec for the front-end team.
```

## Disclaimer

Outputs from this plugin are drafts intended for designer review. Brand guidelines, accessibility audits, and dev specs should be verified by a qualified designer or accessibility specialist before production use.

## More resources

- **Profession hub** — Free tools, guides, and the AI Career Lab pillar guide for designers: https://theaicareerlab.com/professions/designer
- **Claude Cowork playbook** — How to set up Claude as your daily co-worker: https://theaicareerlab.com/resources/claude-cowork-designer
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=designer
- **Weekly AI Digest** — Curated AI updates for designers: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/designer) on AI Career Lab give you five runs a day on a free account — no credit card required.

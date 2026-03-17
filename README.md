# AI Career Lab — Claude Code Plugins

17 profession-specific plugin suites for Claude Code. Each plugin gives Claude slash commands and auto-activating domain skills for a specific profession.

Research shows profession-specific skills boost AI accuracy by up to 52 percentage points compared to generic prompts.

## Install

```bash
# Install any plugin via Claude Code
claude plugin add alexclowe/theaicareerlab-plugins/<profession>

# Examples
claude plugin add alexclowe/theaicareerlab-plugins/veterinarian
claude plugin add alexclowe/theaicareerlab-plugins/teacher
claude plugin add alexclowe/theaicareerlab-plugins/recruiter
```

## Plugins

### Healthcare

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Pharmacist](./pharmacist) | `/drug-interaction` `/patient-counsel` `/prior-auth` `/mtm-note` | Clinical Pharmacy, Patient Communication | `alexclowe/theaicareerlab-plugins/pharmacist` |
| [Physical Therapist](./physical-therapist) | `/soap-note` `/exercise-program` `/insurance-appeal` `/progress-note` | Rehabilitation Medicine, Patient Exercise Instruction | `alexclowe/theaicareerlab-plugins/physical-therapist` |
| [Dental Hygienist](./dental-hygienist) | `/perio-narrative` `/insurance-narrative` `/patient-education` `/treatment-summary` | Clinical Dental Hygiene, Oral Health Education | `alexclowe/theaicareerlab-plugins/dental-hygienist` |
| [Chiropractor](./chiropractor) | `/soap-note` `/medical-necessity` `/pi-narrative` `/practice-marketing` | Chiropractic Clinical, Practice Growth | `alexclowe/theaicareerlab-plugins/chiropractor` |
| [Veterinarian](./veterinarian) | `/soap-note` `/discharge-summary` `/referral-letter` `/client-email` | Veterinary Medicine, Pet Owner Communication | `alexclowe/theaicareerlab-plugins/veterinarian` |

### Financial Services

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Insurance Agent](./insurance-agent) | `/policy-summary` `/renewal-letter` `/claims-doc` `/client-outreach` | Insurance Analysis, Client Retention | `alexclowe/theaicareerlab-plugins/insurance-agent` |
| [Bookkeeper](./bookkeeper) | `/financial-summary` `/reconciliation-report` `/tax-prep` `/client-email` | Financial Reporting, Tax Communication | `alexclowe/theaicareerlab-plugins/bookkeeper` |
| [Financial Advisor](./financial-advisor) | `/plan-summary` `/review-letter` `/meeting-notes` `/recommendation-memo` | Financial Planning, Advisory Communication | `alexclowe/theaicareerlab-plugins/financial-advisor` |

### Business & Marketing

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Management Consultant](./management-consultant) | `/proposal` `/executive-summary` `/strategy-memo` `/meeting-followup` | Strategic Analysis, Client Deliverables | `alexclowe/theaicareerlab-plugins/management-consultant` |
| [Social Media Manager](./social-media-manager) | `/caption` `/content-calendar` `/performance-report` `/strategy-doc` | Social Content Creation, Social Analytics | `alexclowe/theaicareerlab-plugins/social-media-manager` |
| [Recruiter](./recruiter) | `/job-description` `/candidate-outreach` `/interview-scorecard` `/offer-letter` | Talent Acquisition, Employer Branding | `alexclowe/theaicareerlab-plugins/recruiter` |
| [HR Manager](./hr-manager) | `/job-description` `/policy-draft` `/onboarding-doc` `/employee-email` | HR Operations, Talent Acquisition | `alexclowe/theaicareerlab-plugins/hr-manager` |

### Legal

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Paralegal](./paralegal) | `/legal-draft` `/research-memo` `/case-summary` `/client-letter` | Legal Writing, Legal Research | `alexclowe/theaicareerlab-plugins/paralegal` |

### Health & Wellness

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Personal Trainer](./personal-trainer) | `/workout-program` `/nutrition-plan` `/progress-report` `/fitness-content` | Exercise Science, Fitness Business | `alexclowe/theaicareerlab-plugins/personal-trainer` |

### Design & Creative

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Interior Designer](./interior-designer) | `/project-proposal` `/spec-sheet` `/concept-narrative` `/client-update` | Interior Design, Design Client Management | `alexclowe/theaicareerlab-plugins/interior-designer` |

### Education

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Teacher](./teacher) | `/lesson-plan` `/rubric` `/parent-email` `/worksheet` | Curriculum Design, Classroom Communication | `alexclowe/theaicareerlab-plugins/teacher` |

### Real Estate

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Real Estate Agent](./real-estate) | `/listing-description` `/client-email` `/cma-narrative` `/market-update` `/offer-comparison` | Real Estate Marketing, Client Communication | `alexclowe/theaicareerlab-plugins/real-estate` |

## How it works

Each plugin contains:
- **Slash commands** — type `/command-name` to run a specific workflow (e.g., `/soap-note`, `/lesson-plan`)
- **Skills** — auto-activate when Claude detects you're working on profession-relevant tasks

Commands are markdown files with system prompts. Skills are knowledge files that give Claude domain expertise. No API keys or external services required.

## Free tools

Each profession also has free web-based AI tools at [theaicareerlab.com](https://theaicareerlab.com) — no Claude account needed.

## License

MIT — see [LICENSE](./LICENSE)

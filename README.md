# AI Career Lab — Claude Code Plugins

26 profession-specific plugin suites for Claude Code. Each plugin gives Claude slash commands and auto-activating domain skills for a specific profession.

Research shows profession-specific skills boost AI accuracy by up to 52 percentage points compared to generic prompts.

## Install

```bash
# Install any plugin via Claude Code
claude plugin add alexclowe/awesome-claude-cowork-plugins/<profession>

# Examples
claude plugin add alexclowe/awesome-claude-cowork-plugins/therapist
claude plugin add alexclowe/awesome-claude-cowork-plugins/nurse
claude plugin add alexclowe/awesome-claude-cowork-plugins/attorney
```

## Plugins

### Healthcare

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Pharmacist](./pharmacist) | `/drug-interaction` `/patient-counsel` `/prior-auth` `/mtm-note` | Clinical Pharmacy, Patient Communication | `alexclowe/awesome-claude-cowork-plugins/pharmacist` |
| [Physical Therapist](./physical-therapist) | `/soap-note` `/exercise-program` `/insurance-appeal` `/progress-note` | Rehabilitation Medicine, Patient Exercise Instruction | `alexclowe/awesome-claude-cowork-plugins/physical-therapist` |
| [Dental Hygienist](./dental-hygienist) | `/perio-narrative` `/insurance-narrative` `/patient-education` `/treatment-summary` | Clinical Dental Hygiene, Oral Health Education | `alexclowe/awesome-claude-cowork-plugins/dental-hygienist` |
| [Chiropractor](./chiropractor) | `/soap-note` `/medical-necessity` `/pi-narrative` `/practice-marketing` | Chiropractic Clinical, Practice Growth | `alexclowe/awesome-claude-cowork-plugins/chiropractor` |
| [Veterinarian](./veterinarian) | `/soap-note` `/discharge-summary` `/referral-letter` `/client-email` | Veterinary Medicine, Pet Owner Communication | `alexclowe/awesome-claude-cowork-plugins/veterinarian` |
| [Therapist](./therapist) | `/session-note` `/treatment-plan` `/pre-auth` `/client-letter` | Clinical Mental Health, Therapeutic Communication | `alexclowe/awesome-claude-cowork-plugins/therapist` |
| [Nurse](./nurse) | `/nursing-note` `/shift-handoff` `/care-plan` `/patient-education` | Clinical Nursing, Patient Education | `alexclowe/awesome-claude-cowork-plugins/nurse` |
| [Speech-Language Pathologist](./speech-language-pathologist) | `/therapy-note` `/iep-goal` `/progress-report` `/therapy-material` | Speech-Language Pathology, Educational Documentation | `alexclowe/awesome-claude-cowork-plugins/speech-language-pathologist` |
| [Optometrist](./optometrist) | `/exam-note` `/referral-letter` `/patient-education` `/insurance-narrative` | Clinical Optometry, Patient Communication | `alexclowe/awesome-claude-cowork-plugins/optometrist` |

### Financial Services

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Insurance Agent](./insurance-agent) | `/policy-summary` `/renewal-letter` `/claims-doc` `/client-outreach` | Insurance Analysis, Client Retention | `alexclowe/awesome-claude-cowork-plugins/insurance-agent` |
| [Bookkeeper](./bookkeeper) | `/financial-summary` `/reconciliation-report` `/tax-prep` `/client-email` | Financial Reporting, Tax Communication | `alexclowe/awesome-claude-cowork-plugins/bookkeeper` |
| [Financial Advisor](./financial-advisor) | `/plan-summary` `/review-letter` `/meeting-notes` `/recommendation-memo` | Financial Planning, Advisory Communication | `alexclowe/awesome-claude-cowork-plugins/financial-advisor` |

### Business & Marketing

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Management Consultant](./management-consultant) | `/proposal` `/executive-summary` `/strategy-memo` `/meeting-followup` | Strategic Analysis, Client Deliverables | `alexclowe/awesome-claude-cowork-plugins/management-consultant` |
| [Social Media Manager](./social-media-manager) | `/caption` `/content-calendar` `/performance-report` `/strategy-doc` | Social Content Creation, Social Analytics | `alexclowe/awesome-claude-cowork-plugins/social-media-manager` |
| [Recruiter](./recruiter) | `/job-description` `/candidate-outreach` `/interview-scorecard` `/offer-letter` | Talent Acquisition, Employer Branding | `alexclowe/awesome-claude-cowork-plugins/recruiter` |
| [HR Manager](./hr-manager) | `/job-description` `/policy-draft` `/onboarding-doc` `/employee-email` | HR Operations, Talent Acquisition | `alexclowe/awesome-claude-cowork-plugins/hr-manager` |
| [Sales Representative](./sales-rep) | `/prospect-brief` `/follow-up` `/sales-proposal` `/call-prep` | Sales Strategy, Sales Communication | `alexclowe/awesome-claude-cowork-plugins/sales-rep` |

### Legal

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Paralegal](./paralegal) | `/legal-draft` `/research-memo` `/case-summary` `/client-letter` | Legal Writing, Legal Research | `alexclowe/awesome-claude-cowork-plugins/paralegal` |
| [Attorney](./attorney) | `/client-memo` `/demand-letter` `/contract-summary` `/billing-narrative` | Legal Practice, Client Communication | `alexclowe/awesome-claude-cowork-plugins/attorney` |

### Health & Wellness

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Personal Trainer](./personal-trainer) | `/workout-program` `/nutrition-plan` `/progress-report` `/fitness-content` | Exercise Science, Fitness Business | `alexclowe/awesome-claude-cowork-plugins/personal-trainer` |

### Design & Creative

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Interior Designer](./interior-designer) | `/project-proposal` `/spec-sheet` `/concept-narrative` `/client-update` | Interior Design, Design Client Management | `alexclowe/awesome-claude-cowork-plugins/interior-designer` |

### Education

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Teacher](./teacher) | `/lesson-plan` `/rubric` `/parent-email` `/worksheet` | Curriculum Design, Classroom Communication | `alexclowe/awesome-claude-cowork-plugins/teacher` |

### Real Estate

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Real Estate Agent](./real-estate) | `/listing-description` `/client-email` `/cma-narrative` `/market-update` `/offer-comparison` | Real Estate Marketing, Client Communication | `alexclowe/awesome-claude-cowork-plugins/real-estate` |
| [Property Manager](./property-manager) | `/tenant-notice` `/board-report` `/vendor-email` `/budget-narrative` | Property Management, Board Communication | `alexclowe/awesome-claude-cowork-plugins/property-manager` |

### Skilled Trades

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Tradesperson](./tradesperson) | `/estimate` `/inspection-report` `/scope-of-work` `/customer-email` | Trade Documentation, Customer Relations | `alexclowe/awesome-claude-cowork-plugins/tradesperson` |

### Events & Hospitality

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Event Planner](./event-planner) | `/event-proposal` `/vendor-outreach` `/event-timeline` `/client-update` | Event Design, Client Management | `alexclowe/awesome-claude-cowork-plugins/event-planner` |

## How it works

Each plugin contains:
- **Slash commands** — type `/command-name` to run a specific workflow (e.g., `/session-note`, `/demand-letter`)
- **Skills** — auto-activate when Claude detects you're working on profession-relevant tasks

Commands are markdown files with system prompts. Skills are knowledge files that give Claude domain expertise. No API keys or external services required.

## Free tools

Each profession also has free web-based AI tools at [theaicareerlab.com](https://theaicareerlab.com) — no Claude account needed.

## License

MIT — see [LICENSE](./LICENSE)

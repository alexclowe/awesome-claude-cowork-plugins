# AI Career Lab — Claude Cowork Plugins

42 profession-specific plugin suites for Claude Cowork and Claude Code. Each plugin gives Claude slash commands and auto-activating domain skills for a specific profession.

Research shows profession-specific skills boost AI accuracy by up to 52 percentage points compared to generic prompts.

## Install

In Claude Cowork or Claude Code (plugins need a paid Claude plan — Pro, Max, or Team), add the marketplace once, then install any plugin by name:

```bash
# 1. Add the marketplace (one time)
/plugin marketplace add alexclowe/awesome-claude-cowork-plugins

# 2. Install any plugin by name
/plugin install <profession>@awesome-claude-cowork-plugins

# Examples
/plugin install pharmacist@awesome-claude-cowork-plugins
/plugin install physical-therapist@awesome-claude-cowork-plugins
/plugin install dental-hygienist@awesome-claude-cowork-plugins
```

## Plugins

### Healthcare

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Chiropractor](./chiropractor) | `/soap-note` `/medical-necessity` `/pi-narrative` `/practice-marketing` | Chiropractic Clinical, Practice Growth | `/plugin install chiropractor@awesome-claude-cowork-plugins` |
| [Dental Hygienist](./dental-hygienist) | `/perio-narrative` `/insurance-narrative` `/patient-education` `/treatment-summary` | Clinical Dental Hygiene, Oral Health Education | `/plugin install dental-hygienist@awesome-claude-cowork-plugins` |
| [Healthcare Compliance Officer](./healthcare-compliance-officer) | `/validate-ai-device` `/manage-pccp` `/monitor-adverse-events` `/assess-data-quality` | FDA Classification Advisor, Clinical Evidence Mapper | `/plugin install healthcare-compliance-officer@awesome-claude-cowork-plugins` |
| [Nurse](./nurse) | `/nursing-note` `/shift-handoff` `/care-plan` `/patient-education` | Clinical Nursing, Patient Education | `/plugin install nurse@awesome-claude-cowork-plugins` |
| [Occupational Therapist](./occupational-therapist) | `/soap-note` `/treatment-plan` `/progress-report` `/home-program` | Occupational Therapy, Patient Education | `/plugin install occupational-therapist@awesome-claude-cowork-plugins` |
| [Optometrist](./optometrist) | `/exam-note` `/referral-letter` `/patient-education` `/insurance-narrative` | Clinical Optometry, Patient Communication | `/plugin install optometrist@awesome-claude-cowork-plugins` |
| [Pharmacist](./pharmacist) | `/drug-interaction` `/patient-counsel` `/prior-auth` `/mtm-note` | Clinical Pharmacy, Patient Communication | `/plugin install pharmacist@awesome-claude-cowork-plugins` |
| [Physical Therapist](./physical-therapist) | `/soap-note` `/exercise-program` `/insurance-appeal` `/progress-note` | Rehabilitation Medicine, Patient Exercise Instruction | `/plugin install physical-therapist@awesome-claude-cowork-plugins` |
| [Speech-Language Pathologist](./speech-language-pathologist) | `/therapy-note` `/iep-goal` `/progress-report` `/therapy-material` | Speech-Language Pathology, Educational Documentation | `/plugin install speech-language-pathologist@awesome-claude-cowork-plugins` |
| [Therapist](./therapist) | `/session-note` `/treatment-plan` `/pre-auth` `/client-letter` `/hipaa-check` `/measure-therapy-outcomes` `/treatment-plan-versioning` | Clinical Mental Health, Therapeutic Communication, Suicide Risk Assessment Protocol, Trauma-Informed Language Guardrails | `/plugin install therapist@awesome-claude-cowork-plugins` |
| [Veterinarian](./veterinarian) | `/soap-note` `/discharge-summary` `/referral-letter` `/client-email` | Veterinary Medicine, Pet Owner Communication | `/plugin install veterinarian@awesome-claude-cowork-plugins` |

### Legal

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Attorney](./attorney) | `/client-memo` `/demand-letter` `/contract-summary` `/billing-narrative` `/deposition-summary` `/case-timeline` `/motion-draft` `/assess-ai-risk-client-systems` | Legal Practice, Client Communication, Litigation Workflow, AI Regulatory Mapper | `/plugin install attorney@awesome-claude-cowork-plugins` |
| [Litigation Paralegal](./litigation-paralegal) | `/deposition-summary` `/case-timeline` `/motion-draft` `/discovery-hold` | Legal Research Cite Finder, Evidence Relevance Checker | `/plugin install litigation-paralegal@awesome-claude-cowork-plugins` |
| [Paralegal](./paralegal) | `/legal-draft` `/research-memo` `/case-summary` `/client-letter` | Legal Writing, Legal Research | `/plugin install paralegal@awesome-claude-cowork-plugins` |

### Financial Services

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Bookkeeper](./bookkeeper) | `/financial-summary` `/reconciliation-report` `/tax-prep` `/client-email` | Financial Reporting, Tax Communication | `/plugin install bookkeeper@awesome-claude-cowork-plugins` |
| [Financial Advisor](./financial-advisor) | `/plan-summary` `/review-letter` `/meeting-notes` `/recommendation-memo` `/tax-loss-harvest` `/screen-esg-portfolio` `/compliance-tracker` `/multi-jurisdiction-tax` | Financial Planning, Advisory Communication, Regulatory Change Monitor | `/plugin install financial-advisor@awesome-claude-cowork-plugins` |
| [Insurance Agent](./insurance-agent) | `/policy-summary` `/renewal-letter` `/claims-doc` `/client-outreach` | Insurance Analysis, Client Retention | `/plugin install insurance-agent@awesome-claude-cowork-plugins` |
| [Mortgage Broker](./mortgage-broker) | `/rate-comparison` `/pre-approval-letter` `/client-update` `/refinance-analysis` | Mortgage Lending, Client Communication | `/plugin install mortgage-broker@awesome-claude-cowork-plugins` |

### Real Estate

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Property Manager](./property-manager) | `/tenant-notice` `/board-report` `/vendor-email` `/budget-narrative` | Property Management, Board Communication | `/plugin install property-manager@awesome-claude-cowork-plugins` |
| [Real Estate Agent](./real-estate) | `/listing-description` `/client-email` `/cma-narrative` `/market-update` `/offer-comparison` | Real Estate Marketing, Client Communication | `/plugin install real-estate@awesome-claude-cowork-plugins` |

### Business & Marketing

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [AI Product Manager](./product-manager-ai) | `/draft-ai-spec` `/evaluate-ai-risk` `/plan-rollout` `/analyze-user-feedback` | AI Readiness Assessment, Competitive Benchmarking | `/plugin install product-manager-ai@awesome-claude-cowork-plugins` |
| [Community Manager](./community-manager) | `/moderate-community` `/onboard-member` `/analyze-sentiment` `/run-event-workflow` | Community Health Monitoring, Moderation Audit Trail | `/plugin install community-manager@awesome-claude-cowork-plugins` |
| [Executive Assistant](./executive-assistant) | `/inbox-triage` `/meeting-brief` `/follow-up-draft` `/daily-priorities` | Executive Operations, Communication & Coordination | `/plugin install executive-assistant@awesome-claude-cowork-plugins` |
| [HR Manager](./hr-manager) | `/job-description` `/policy-draft` `/onboarding-doc` `/employee-email` `/rto-comms` `/severance-negotiation` `/quiet-firing-detector` `/audit-hiring-for-bias` | HR Operations, Talent Acquisition, Reskilling Pathway Mapper | `/plugin install hr-manager@awesome-claude-cowork-plugins` |
| [Management Consultant](./management-consultant) | `/proposal` `/executive-summary` `/strategy-memo` `/meeting-followup` | Strategic Analysis, Client Deliverables | `/plugin install management-consultant@awesome-claude-cowork-plugins` |
| [Recruiter](./recruiter) | `/job-description` `/candidate-outreach` `/interview-scorecard` `/offer-letter` `/ghost-job-detect` `/ai-resume-flag` `/compensation-band-check` | Talent Acquisition, Employer Branding, Ghost Job Detection, AI-Resume Detector | `/plugin install recruiter@awesome-claude-cowork-plugins` |
| [Sales Representative](./sales-rep) | `/prospect-brief` `/follow-up` `/sales-proposal` `/call-prep` | Sales Strategy, Sales Communication | `/plugin install sales-rep@awesome-claude-cowork-plugins` |
| [Social Media Manager](./social-media-manager) | `/caption` `/content-calendar` `/performance-report` `/strategy-doc` `/visual-brief` `/video-script` `/cross-post` | Social Content Creation, Social Analytics, Visual Design Brief, Platform-Native Voice | `/plugin install social-media-manager@awesome-claude-cowork-plugins` |

### Tech & AI

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Data Scientist](./data-scientist) | `/design-experiment` `/analyze-dataset` `/build-model` `/eval-model` | Dataset Profiling, Model Card Generation | `/plugin install data-scientist@awesome-claude-cowork-plugins` |
| [Prompt Engineer](./prompt-engineer) | `/eval-rubric` `/test-batch` `/skill-version` `/skill-audit` | Prompt Optimization Loop, Skill Benchmarking | `/plugin install prompt-engineer@awesome-claude-cowork-plugins` |

### Compliance & Risk

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [AI Compliance Officer](./ai-compliance-officer) | `/audit-ai-system` `/track-regulatory-change` `/generate-documentation` `/eval-autonomous-agent` | High-Risk System Classification, Post-Market Monitoring Automation | `/plugin install ai-compliance-officer@awesome-claude-cowork-plugins` |
| [ESG Sustainability Analyst](./esg-sustainability-analyst) | `/extract-esg-data` `/assess-esg-risk` `/draft-esg-disclosure` `/track-esg-performance` | Regulatory Standard Mapping, Carbon Accounting Automation | `/plugin install esg-sustainability-analyst@awesome-claude-cowork-plugins` |

### Design & Creative

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Copywriter](./copywriter) | `/brief-intake` `/draft-batch` `/tone-check` `/approval-workflow` | Client Voice Mapping, Conversion Psychology | `/plugin install copywriter@awesome-claude-cowork-plugins` |
| [Designer](./designer) | `/design-system` `/design-critique` `/design-iterate` `/design-export` | Brand Voice Design, Accessibility Audit | `/plugin install designer@awesome-claude-cowork-plugins` |
| [Interior Designer](./interior-designer) | `/project-proposal` `/spec-sheet` `/concept-narrative` `/client-update` | Interior Design, Design Client Management | `/plugin install interior-designer@awesome-claude-cowork-plugins` |
| [Photographer](./photographer) | `/client-proposal` `/shot-list` `/album-description` `/marketing-email` | Photography Business, Visual Storytelling | `/plugin install photographer@awesome-claude-cowork-plugins` |

### Health & Wellness

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Dietitian](./dietitian) | `/nutrition-assessment` `/meal-plan` `/progress-note` `/client-education` | Clinical Nutrition, Dietary Communication | `/plugin install dietitian@awesome-claude-cowork-plugins` |
| [Personal Trainer](./personal-trainer) | `/workout-program` `/nutrition-plan` `/progress-report` `/fitness-content` | Exercise Science, Fitness Business | `/plugin install personal-trainer@awesome-claude-cowork-plugins` |

### Education

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Teacher](./teacher) | `/lesson-plan` `/rubric` `/parent-email` `/worksheet` `/student-data-audit` `/ai-ethics-brief` `/exam-integrity-check` | Curriculum Design, Classroom Communication, Classroom AI Ethics | `/plugin install teacher@awesome-claude-cowork-plugins` |

### Events & Hospitality

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Event Planner](./event-planner) | `/event-proposal` `/vendor-outreach` `/event-timeline` `/client-update` | Event Design, Client Management | `/plugin install event-planner@awesome-claude-cowork-plugins` |

### Skilled Trades

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Construction Project Manager](./construction-pm) | `/project-estimate` `/change-order` `/progress-report` `/rfi-response` | Construction Management, Stakeholder Communication | `/plugin install construction-pm@awesome-claude-cowork-plugins` |
| [Tradesperson](./tradesperson) | `/estimate` `/inspection-report` `/scope-of-work` `/customer-email` | Trade Documentation, Customer Relations | `/plugin install tradesperson@awesome-claude-cowork-plugins` |

## How it works

Each plugin ships a set of **slash commands** plus **auto-activating skills** (see the table above for each plugin's exact counts). Slash commands are explicit workflows you invoke; skills are background expertise that activate automatically when Claude detects you're working on that profession's tasks.

All commands produce **drafts for your review** — they do not replace professional judgment. Disclaimers in each plugin's README spell out the appropriate review process for that discipline.

## Built by The AI Career Lab

Free AI tools, plugins, and weekly digests for working professionals across 12 categories. Visit [theaicareerlab.com](https://theaicareerlab.com).

> Want to install a plugin without typing slash commands? Every plugin's profession also has free web tools at [theaicareerlab.com/professions](https://theaicareerlab.com/professions) — five runs per day on a free account, no credit card.

---

*This README is auto-generated from `lib/plugins-data.ts`. To update plugin metadata, edit that file (or the corresponding `/plugins/{slug}/` directory), then run `npm run generate:plugins-readme`. CI verifies this file is in sync on every PR.*

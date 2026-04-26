# AI Career Lab — Claude Code Plugins

42 profession-specific plugin suites for Claude Code. Each plugin gives Claude slash commands and auto-activating domain skills for a specific profession.

Research shows profession-specific skills boost AI accuracy by up to 52 percentage points compared to generic prompts.

## Install

```bash
# Install any plugin via Claude Code
claude plugin add alexclowe/awesome-claude-cowork-plugins/<profession>

# Examples
claude plugin add alexclowe/awesome-claude-cowork-plugins/pharmacist
claude plugin add alexclowe/awesome-claude-cowork-plugins/physical-therapist
claude plugin add alexclowe/awesome-claude-cowork-plugins/dental-hygienist
```

## Plugins

### Healthcare

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Chiropractor](./chiropractor) | `/soap-note` `/medical-necessity` `/pi-narrative` `/practice-marketing` | Chiropractic Clinical, Practice Growth | `alexclowe/awesome-claude-cowork-plugins/chiropractor` |
| [Dental Hygienist](./dental-hygienist) | `/perio-narrative` `/insurance-narrative` `/patient-education` `/treatment-summary` | Clinical Dental Hygiene, Oral Health Education | `alexclowe/awesome-claude-cowork-plugins/dental-hygienist` |
| [Healthcare Compliance Officer](./healthcare-compliance-officer) | `/validate-ai-device` `/manage-pccp` `/monitor-adverse-events` `/assess-data-quality` | FDA Classification Advisor, Clinical Evidence Mapper | `alexclowe/awesome-claude-cowork-plugins/healthcare-compliance-officer` |
| [Nurse](./nurse) | `/nursing-note` `/shift-handoff` `/care-plan` `/patient-education` | Clinical Nursing, Patient Education | `alexclowe/awesome-claude-cowork-plugins/nurse` |
| [Occupational Therapist](./occupational-therapist) | `/soap-note` `/treatment-plan` `/progress-report` `/home-program` | Occupational Therapy, Patient Education | `alexclowe/awesome-claude-cowork-plugins/occupational-therapist` |
| [Optometrist](./optometrist) | `/exam-note` `/referral-letter` `/patient-education` `/insurance-narrative` | Clinical Optometry, Patient Communication | `alexclowe/awesome-claude-cowork-plugins/optometrist` |
| [Pharmacist](./pharmacist) | `/drug-interaction` `/patient-counsel` `/prior-auth` `/mtm-note` | Clinical Pharmacy, Patient Communication | `alexclowe/awesome-claude-cowork-plugins/pharmacist` |
| [Physical Therapist](./physical-therapist) | `/soap-note` `/exercise-program` `/insurance-appeal` `/progress-note` | Rehabilitation Medicine, Patient Exercise Instruction | `alexclowe/awesome-claude-cowork-plugins/physical-therapist` |
| [Speech-Language Pathologist](./speech-language-pathologist) | `/therapy-note` `/iep-goal` `/progress-report` `/therapy-material` | Speech-Language Pathology, Educational Documentation | `alexclowe/awesome-claude-cowork-plugins/speech-language-pathologist` |
| [Therapist](./therapist) | `/session-note` `/treatment-plan` `/pre-auth` `/client-letter` `/hipaa-check` `/measure-therapy-outcomes` `/treatment-plan-versioning` | Clinical Mental Health, Therapeutic Communication, Suicide Risk Assessment Protocol, Trauma-Informed Language Guardrails | `alexclowe/awesome-claude-cowork-plugins/therapist` |
| [Veterinarian](./veterinarian) | `/soap-note` `/discharge-summary` `/referral-letter` `/client-email` | Veterinary Medicine, Pet Owner Communication | `alexclowe/awesome-claude-cowork-plugins/veterinarian` |

### Legal

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Attorney](./attorney) | `/client-memo` `/demand-letter` `/contract-summary` `/billing-narrative` `/deposition-summary` `/case-timeline` `/motion-draft` `/assess-ai-risk-client-systems` | Legal Practice, Client Communication, Litigation Workflow, AI Regulatory Mapper | `alexclowe/awesome-claude-cowork-plugins/attorney` |
| [Litigation Paralegal](./litigation-paralegal) | `/deposition-summary` `/case-timeline` `/motion-draft` `/discovery-hold` | Legal Research Cite Finder, Evidence Relevance Checker | `alexclowe/awesome-claude-cowork-plugins/litigation-paralegal` |
| [Paralegal](./paralegal) | `/legal-draft` `/research-memo` `/case-summary` `/client-letter` | Legal Writing, Legal Research | `alexclowe/awesome-claude-cowork-plugins/paralegal` |

### Financial Services

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Bookkeeper](./bookkeeper) | `/financial-summary` `/reconciliation-report` `/tax-prep` `/client-email` | Financial Reporting, Tax Communication | `alexclowe/awesome-claude-cowork-plugins/bookkeeper` |
| [Financial Advisor](./financial-advisor) | `/plan-summary` `/review-letter` `/meeting-notes` `/recommendation-memo` `/tax-loss-harvest` `/screen-esg-portfolio` `/compliance-tracker` `/multi-jurisdiction-tax` | Financial Planning, Advisory Communication, Regulatory Change Monitor | `alexclowe/awesome-claude-cowork-plugins/financial-advisor` |
| [Insurance Agent](./insurance-agent) | `/policy-summary` `/renewal-letter` `/claims-doc` `/client-outreach` | Insurance Analysis, Client Retention | `alexclowe/awesome-claude-cowork-plugins/insurance-agent` |
| [Mortgage Broker](./mortgage-broker) | `/rate-comparison` `/pre-approval-letter` `/client-update` `/refinance-analysis` | Mortgage Lending, Client Communication | `alexclowe/awesome-claude-cowork-plugins/mortgage-broker` |

### Real Estate

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Property Manager](./property-manager) | `/tenant-notice` `/board-report` `/vendor-email` `/budget-narrative` | Property Management, Board Communication | `alexclowe/awesome-claude-cowork-plugins/property-manager` |
| [Real Estate Agent](./real-estate) | `/listing-description` `/client-email` `/cma-narrative` `/market-update` `/offer-comparison` | Real Estate Marketing, Client Communication | `alexclowe/awesome-claude-cowork-plugins/real-estate` |

### Business & Marketing

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [AI Product Manager](./product-manager-ai) | `/draft-ai-spec` `/evaluate-ai-risk` `/plan-rollout` `/analyze-user-feedback` | AI Readiness Assessment, Competitive Benchmarking | `alexclowe/awesome-claude-cowork-plugins/product-manager-ai` |
| [Community Manager](./community-manager) | `/moderate-community` `/onboard-member` `/analyze-sentiment` `/run-event-workflow` | Community Health Monitoring, Moderation Audit Trail | `alexclowe/awesome-claude-cowork-plugins/community-manager` |
| [Executive Assistant](./executive-assistant) | `/inbox-triage` `/meeting-brief` `/follow-up-draft` `/daily-priorities` | Executive Operations, Communication & Coordination | `alexclowe/awesome-claude-cowork-plugins/executive-assistant` |
| [HR Manager](./hr-manager) | `/job-description` `/policy-draft` `/onboarding-doc` `/employee-email` `/rto-comms` `/severance-negotiation` `/quiet-firing-detector` `/audit-hiring-for-bias` | HR Operations, Talent Acquisition, Reskilling Pathway Mapper | `alexclowe/awesome-claude-cowork-plugins/hr-manager` |
| [Management Consultant](./management-consultant) | `/proposal` `/executive-summary` `/strategy-memo` `/meeting-followup` | Strategic Analysis, Client Deliverables | `alexclowe/awesome-claude-cowork-plugins/management-consultant` |
| [Recruiter](./recruiter) | `/job-description` `/candidate-outreach` `/interview-scorecard` `/offer-letter` `/ghost-job-detect` `/ai-resume-flag` `/compensation-band-check` | Talent Acquisition, Employer Branding, Ghost Job Detection, AI-Resume Detector | `alexclowe/awesome-claude-cowork-plugins/recruiter` |
| [Sales Representative](./sales-rep) | `/prospect-brief` `/follow-up` `/sales-proposal` `/call-prep` | Sales Strategy, Sales Communication | `alexclowe/awesome-claude-cowork-plugins/sales-rep` |
| [Social Media Manager](./social-media-manager) | `/caption` `/content-calendar` `/performance-report` `/strategy-doc` `/visual-brief` `/video-script` `/cross-post` | Social Content Creation, Social Analytics, Visual Design Brief, Platform-Native Voice | `alexclowe/awesome-claude-cowork-plugins/social-media-manager` |

### Tech & AI

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Data Scientist](./data-scientist) | `/design-experiment` `/analyze-dataset` `/build-model` `/eval-model` | Dataset Profiling, Model Card Generation | `alexclowe/awesome-claude-cowork-plugins/data-scientist` |
| [Prompt Engineer](./prompt-engineer) | `/eval-rubric` `/test-batch` `/skill-version` `/skill-audit` | Prompt Optimization Loop, Skill Benchmarking | `alexclowe/awesome-claude-cowork-plugins/prompt-engineer` |

### Compliance & Risk

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [AI Compliance Officer](./ai-compliance-officer) | `/audit-ai-system` `/track-regulatory-change` `/generate-documentation` `/eval-autonomous-agent` | High-Risk System Classification, Post-Market Monitoring Automation | `alexclowe/awesome-claude-cowork-plugins/ai-compliance-officer` |
| [ESG Sustainability Analyst](./esg-sustainability-analyst) | `/extract-esg-data` `/assess-esg-risk` `/draft-esg-disclosure` `/track-esg-performance` | Regulatory Standard Mapping, Carbon Accounting Automation | `alexclowe/awesome-claude-cowork-plugins/esg-sustainability-analyst` |

### Design & Creative

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Copywriter](./copywriter) | `/brief-intake` `/draft-batch` `/tone-check` `/approval-workflow` | Client Voice Mapping, Conversion Psychology | `alexclowe/awesome-claude-cowork-plugins/copywriter` |
| [Designer](./designer) | `/design-system` `/design-critique` `/design-iterate` `/design-export` | Brand Voice Design, Accessibility Audit | `alexclowe/awesome-claude-cowork-plugins/designer` |
| [Interior Designer](./interior-designer) | `/project-proposal` `/spec-sheet` `/concept-narrative` `/client-update` | Interior Design, Design Client Management | `alexclowe/awesome-claude-cowork-plugins/interior-designer` |
| [Photographer](./photographer) | `/client-proposal` `/shot-list` `/album-description` `/marketing-email` | Photography Business, Visual Storytelling | `alexclowe/awesome-claude-cowork-plugins/photographer` |

### Health & Wellness

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Dietitian](./dietitian) | `/nutrition-assessment` `/meal-plan` `/progress-note` `/client-education` | Clinical Nutrition, Dietary Communication | `alexclowe/awesome-claude-cowork-plugins/dietitian` |
| [Personal Trainer](./personal-trainer) | `/workout-program` `/nutrition-plan` `/progress-report` `/fitness-content` | Exercise Science, Fitness Business | `alexclowe/awesome-claude-cowork-plugins/personal-trainer` |

### Education

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Teacher](./teacher) | `/lesson-plan` `/rubric` `/parent-email` `/worksheet` `/student-data-audit` `/ai-ethics-brief` `/exam-integrity-check` | Curriculum Design, Classroom Communication, Classroom AI Ethics | `alexclowe/awesome-claude-cowork-plugins/teacher` |

### Events & Hospitality

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Event Planner](./event-planner) | `/event-proposal` `/vendor-outreach` `/event-timeline` `/client-update` | Event Design, Client Management | `alexclowe/awesome-claude-cowork-plugins/event-planner` |

### Skilled Trades

| Plugin | Commands | Skills | Install |
|--------|----------|--------|---------|
| [Construction Project Manager](./construction-pm) | `/project-estimate` `/change-order` `/progress-report` `/rfi-response` | Construction Management, Stakeholder Communication | `alexclowe/awesome-claude-cowork-plugins/construction-pm` |
| [Tradesperson](./tradesperson) | `/estimate` `/inspection-report` `/scope-of-work` `/customer-email` | Trade Documentation, Customer Relations | `alexclowe/awesome-claude-cowork-plugins/tradesperson` |

## How it works

Each plugin ships **four slash commands** plus **two auto-activating skills**. Slash commands are explicit workflows you invoke; skills are background expertise that activate automatically when Claude detects you're working on that profession's tasks.

All commands produce **drafts for your review** — they do not replace professional judgment. Disclaimers in each plugin's README spell out the appropriate review process for that discipline.

## Built by The AI Career Lab

Free AI tools, plugins, and weekly digests for working professionals across 12 categories. Visit [theaicareerlab.com](https://theaicareerlab.com).

> Want to install a plugin without typing slash commands? Every plugin's profession also has free web tools at [theaicareerlab.com/professions](https://theaicareerlab.com/professions) — five runs per day on a free account, no credit card.

---

*This README is auto-generated from `lib/plugins-data.ts`. To update plugin metadata, edit that file (or the corresponding `/plugins/{slug}/` directory), then run `npm run generate:plugins-readme`. CI verifies this file is in sync on every PR.*

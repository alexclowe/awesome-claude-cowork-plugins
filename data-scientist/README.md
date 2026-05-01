# Data Scientist Plugin for Claude

Design experiments, profile datasets, build models, and audit them for bias before shipping.

Built by [The AI Career Lab](https://theaicareerlab.com/professions/data-scientist) — AI tools, guides, and weekly digests designed specifically for data scientists.

## Commands

| Command | Description |
|---------|-------------|
| `/design-experiment` | Plan an A/B test or experiment with sample size, power analysis, and recommended duration |
| `/analyze-dataset` | Generate a data quality report from a dataset description, flag outliers and biases, suggest transforms |
| `/build-model` | Recommend model architecture, generate scikit-learn or XGBoost template, document assumptions |
| `/eval-model` | Compute cross-validation, generate confusion matrix, audit feature importance for bias |

## Skills

This plugin includes skills that activate automatically when you're working on data-science tasks:

- **Dataset Profiling** — Auto-scans for missing values, outliers, class imbalance, correlation issues, and schema drift
- **Model Card Generation** — Auto-generates Model Cards covering intended use, limitations, and training data provenance per the HuggingFace and Mitchell et al. standard

## Usage examples

```
/design-experiment
A/B test a new checkout flow. Primary metric: conversion rate (current 4.2%).
Minimum detectable effect: 10% relative lift. Two arms, 50/50 split. Compute
sample size, power, and recommended duration at our 12K daily-visitor traffic.
```

```
/analyze-dataset
Dataset: 240K rows, 38 columns, customer churn labels. Description: 14 numeric
features (revenue, tenure, usage), 22 categorical (plan, region, device), 2
text. Generate a data quality report — flag outliers, missing-value patterns,
class imbalance, and suggest preprocessing.
```

```
/build-model
Goal: predict 30-day customer churn (binary classification). Data: 240K rows,
~12% positive class, mixed numeric/categorical features. Recommend an architecture,
generate a scikit-learn pipeline template, and document all assumptions.
```

```
/eval-model
Model: XGBoost churn classifier. Compute 5-fold cross-validation (ROC-AUC, PR-AUC,
F1), generate confusion matrix at threshold 0.3, and audit feature importance for
bias against protected attributes (region, age band).
```

## Disclaimer

Statistical analyses, model recommendations, and bias audits produced by this plugin are drafts based on the data description and parameters you provide. Real-world performance depends on data quality, drift, and operational context. The data scientist is responsible for validating assumptions, manually reviewing flagged biases, and confirming model behavior on holdout data before deploying to production.

## More resources

- **Profession hub** — Free tools, guides, and the AI Career Lab pillar guide for data scientists: https://theaicareerlab.com/professions/data-scientist
- **Claude Cowork playbook** — How to set up Claude as your daily co-worker: https://theaicareerlab.com/resources/claude-cowork-data-scientist
- **Data Scientist Claude Vault — coming soon.** Want the done-for-you setup (prompts, templates, and a ready-to-use Claude Project)? Join the waitlist and we'll email you the moment it ships: https://theaicareerlab.com/waitlist/data-scientist
- **AI Readiness Audit** — 2-minute score for your practice: https://theaicareerlab.com/audit?profession=data-scientist
- **Weekly AI Digest** — Curated AI updates for data scientists: https://theaicareerlab.com/newsletter

> **Want a quick win without installing this plugin?** [The free web tools](https://theaicareerlab.com/professions/data-scientist) on AI Career Lab give you five runs a day on a free account — no credit card required.

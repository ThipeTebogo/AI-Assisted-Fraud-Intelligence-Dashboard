# 🤖 AI-Assisted-Fraud-Intelligence-Dashboard

> **A Power BI fraud analytics solution that demonstrates AI-assisted development using Claude (Power BI Modelling MCP server ), DAX, prompt engineering, and analytical validation.**

![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue?style=for-the-badge)
![Claude AI](https://img.shields.io/badge/Claude-AI_Assisted-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> ## Dashboard Preview
>
> <img width="1396" height="775" alt="AI-Assisted Fraud Intelligence Dashboard Screenshot" src="https://github.com/user-attachments/assets/45da7804-825e-4a56-89a9-877314195dd1" />


---

# AI-Assisted Fraud Intelligence Dashboard

## Why I Built This Project

Artificial Intelligence is transforming the way analysts build reports, write calculations, and solve business problems. While AI can significantly accelerate development, it cannot replace analytical thinking, business understanding, or technical validation.

I built this project to explore how AI can be integrated into a professional Business Intelligence workflow using **Claude (Power BI MCP Modelling)** as a collaborative development partner.

Rather than asking AI to build the dashboard from start to finish, I used Claude throughout the project to assist with:

- Designing analytical solutions
- Developing DAX measures
- Exploring alternative modelling approaches
- Debugging calculations
- Troubleshooting visual behaviour
- Improving business logic

Every AI-generated solution was reviewed, tested, validated, and refined before becoming part of the final dashboard.

This project demonstrates that the combination of **Power BI, DAX, critical thinking, and effective AI collaboration** produces far better results than relying on AI alone.

---

# Project Overview

The **AI-Assisted Fraud Intelligence Dashboard** analyses banking transaction data to identify fraud patterns, monitor operational risk, and generate business-focused recommendations.

The dashboard combines traditional Business Intelligence techniques with AI-assisted analytics to transform raw transaction data into actionable insights.

Unlike a traditional Power BI project, this repository documents not only the final dashboard but also the collaborative workflow between analyst and AI, highlighting the importance of validation, prompt engineering, and iterative problem-solving.

The completed solution includes:

- Executive KPI reporting
- Fraud trend analysis
- Risk score comparison
- Customer risk segmentation
- Fraud rate analysis by channel
- Dynamic fraud recommendations
- Top-N city risk analysis

---

# Repository Objectives

This project was created to demonstrate practical experience in:

- Power BI dashboard development
- DAX measure design
- AI-assisted analytics using Claude
- Prompt engineering
- Analytical validation
- Business problem solving
- Dashboard debugging
- Data storytelling
- Technical documentation
- Human validation of AI-generated solutions

  # Business Problem

Financial institutions process thousands of transactions every day, making it increasingly difficult to identify suspicious activity through manual review alone. Fraud analysts require timely, data-driven insights that highlight abnormal transaction patterns, emerging risks, and customer behaviours requiring further investigation.

The objective of this project was to design an interactive fraud intelligence dashboard capable of transforming raw transaction data into meaningful business insights. Rather than focusing solely on reporting historical metrics, the dashboard was designed to support risk monitoring by identifying high-risk customer segments, comparing fraud patterns across transaction channels, and automatically generating analytical recommendations based on the data.

A secondary objective was to explore how Artificial Intelligence could be integrated into a Business Intelligence workflow. Throughout the project, Claude (Power BI MCP Modelling) was used to assist with DAX development, analytical reasoning, and debugging, while all outputs were reviewed, validated, and refined before implementation.

The result is a dashboard that demonstrates not only Power BI reporting capabilities but also a practical workflow for combining AI-assisted development with analytical validation.

---

# Project Objectives

The primary objectives of this project were to:

- Design an executive fraud monitoring dashboard in Power BI.
- Build reusable DAX measures for fraud analysis and business reporting.
- Analyse fraud patterns across customer behaviour, transaction channels, and account tenure.
- Develop a dynamic recommendation engine that responds to report filters.
- Apply AI-assisted development using Claude (Power BI MCP Modelling) to accelerate dashboard development.
- Validate all AI-generated calculations through testing, debugging, and technical review.
- Strengthen practical skills in DAX, Power BI modelling, and prompt engineering.
- Demonstrate how AI can support analytical work without replacing technical understanding or critical thinking.

---

# Dataset Overview

The dashboard analyses a simulated banking transaction dataset stored in a single table named:

`fraud_detection`

The dataset contains transaction-level information used to evaluate fraud exposure, customer behaviour, and operational risk.

## Key Data Fields

| Category | Fields |
|-----------|--------|
| Customer Information | `customer_id`, `customer_home_city`, `account_tenure_days` |
| Transaction Details | `transaction_amount`, `transaction_type`, `channel`, `timestamp` |
| Fraud Indicators | `is_fraud`, `risk_score` |
| Behavioural Indicators | `is_new_beneficiary`, `is_foreign_transaction`, `login_attempts_before_transaction` |
| Location Information | `customer_home_city`, `transaction_city` |

The dataset was intentionally rich enough to support multiple analytical perspectives, allowing fraud to be explored across customer behaviour, transaction characteristics, geographical patterns, and operational risk indicators.

---

# Analytical Approach

Instead of building visuals first, I approached the project from a business analysis perspective.

The development process followed four stages:

## 1. Define Business Questions

The first step was identifying the questions the dashboard should answer.

Examples included:

- How many fraudulent transactions occurred?
- What financial value was exposed to fraud?
- Which customer segments present the highest fraud risk?
- Which transaction channels have the highest fraud rates?
- Which customer locations require additional investigation?
- Which fraud pattern should be prioritised by investigators?

These questions became the foundation for the dashboard's KPIs, measures, and visualisations.

---

## 2. Build Reusable Business Measures

Rather than creating calculations directly inside visuals, reusable DAX measures were developed for key business metrics.

This approach improves consistency, simplifies maintenance, and allows the same calculations to be reused across multiple report pages and visualisations.

Where appropriate, presentation measures (labels and narrative text) were separated from numeric measures to avoid breaking downstream calculations.

---

## 3. Validate Results

Every measure generated with AI assistance was validated before implementation.

Validation included:

- Reviewing DAX logic.
- Testing calculations against expected results.
- Comparing outputs across visuals.
- Investigating unexpected behaviour.
- Refining prompts when AI assumptions did not match business requirements.

This iterative process ensured that the dashboard remained analytically accurate rather than relying solely on AI-generated outputs.

---

## 4. Deliver Actionable Insights

The final stage focused on communicating findings through clear visualisations and dynamic recommendations rather than simply displaying raw metrics.

The completed dashboard enables users to:

- Monitor fraud exposure.
- Compare fraud performance across business dimensions.
- Identify emerging risk patterns.
- Prioritise high-risk customer segments.
- Support more informed fraud investigation and operational decision-making.

- # AI-Assisted Development

One of the primary goals of this project was to explore how Artificial Intelligence can enhance a modern analytics workflow while maintaining technical accuracy and analytical integrity.

Throughout the project, I used **Claude (Power BI MCP Modelling)** as a collaborative development partner rather than as a code generator.

Claude assisted with:

- Brainstorming dashboard layouts and analytical approaches.
- Developing and refining DAX measures.
- Explaining DAX concepts and filter context.
- Troubleshooting unexpected visual behaviour.
- Reviewing calculation logic.
- Exploring alternative modelling approaches.
- Improving the readability and maintainability of DAX.

However, every suggestion generated by AI was treated as a starting point rather than a final solution. All measures, visuals, and calculations were reviewed, tested, and validated before implementation.

This collaborative approach allowed me to develop the dashboard more efficiently while strengthening my understanding of both Power BI and DAX.

---

# AI Collaboration Workflow

The project followed an iterative workflow that combined AI-assisted development with human validation.

```text
Business Question
        │
        ▼
Define Analytical Objective
        │
        ▼
Prompt Claude
        │
        ▼
Generate DAX / Analytical Approach
        │
        ▼
Implement in Power BI
        │
        ▼
Validate Results
        │
        ▼
Investigate Unexpected Behaviour
        │
        ▼
Refine Prompt
        │
        ▼
Improve Solution
```

Rather than accepting the first AI-generated response, I continuously refined prompts, tested calculations against expected business outcomes, and investigated unexpected behaviour until the solution aligned with the analytical objective.

This iterative process became one of the most valuable learning experiences of the project.

---

# AI Collaboration Examples

The table below highlights examples of how AI supported different stages of development and how analytical validation influenced the final solution.

| Development Stage | AI Contribution | Validation & Outcome |
|-------------------|-----------------|----------------------|
| Dashboard Planning | Suggested KPIs and visual layouts for fraud monitoring. | Selected the visuals that best supported the business questions and simplified the dashboard where necessary. |
| DAX Development | Assisted with creating reusable measures for fraud KPIs, customer impact, rankings, and recommendations. | Tested every calculation against expected results before implementation. |
| Recommendation Engine | Helped develop a reusable DAX pattern for generating dynamic fraud recommendations. | Refined the logic to improve readability, reusability, and business relevance. |
| Dashboard Debugging | Suggested possible causes for unexpected visual behaviour. | Confirmed whether the issue originated from DAX, data modelling, or Power BI visual configuration before applying changes. |
| Data Exploration | Assisted in evaluating different fields for geographical analysis. | Determined that `customer_home_city` provided more meaningful insights than `transaction_city` due to better aggregation. |
| Measure Optimisation | Recommended improvements to calculation structure and formatting. | Reviewed each recommendation to ensure it aligned with the business requirement and maintained reusable DAX design patterns. |

---

# Prompt Engineering in Practice

An important outcome of this project was developing stronger prompt engineering skills.

I found that the quality of AI-generated responses depended heavily on the amount of context provided. Early prompts often focused on the technical problem alone, which sometimes produced solutions that were syntactically correct but did not fully address the business requirement.

As the project progressed, my prompts became more structured by including:

- The business objective.
- The relevant dataset and fields.
- Existing DAX measures.
- Expected behaviour.
- Actual behaviour observed in Power BI.
- Previous troubleshooting steps.

Providing this additional context consistently produced more accurate and relevant responses.

This experience reinforced that prompt engineering is an iterative analytical skill rather than simply asking AI to generate code.

---

# Human Validation of AI Outputs

A key lesson from this project was that AI-generated solutions should always be validated before implementation.

Throughout development, I regularly:

- Reviewed generated DAX for logical accuracy.
- Tested calculations against expected business outcomes.
- Investigated unexpected visual behaviour.
- Compared outputs across multiple visuals.
- Refined prompts when AI misunderstood the business requirement.
- Re-tested measures after each iteration.

This process demonstrated that successful AI-assisted analytics depends on combining technical knowledge with critical thinking and systematic validation.

Rather than replacing analytical expertise, AI became a productivity tool that accelerated development while still requiring human judgement to ensure reliable and meaningful results.

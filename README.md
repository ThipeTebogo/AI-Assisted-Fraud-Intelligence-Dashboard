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

# Dashboard Walkthrough

The dashboard was designed to provide an executive-level view of fraud activity while allowing users to quickly identify high-risk patterns and areas requiring further investigation.

Rather than overwhelming users with large volumes of data, each visual was selected to answer a specific business question.

---

## Executive KPI Summary

The KPI cards provide an immediate overview of the organisation's fraud exposure.

| KPI | Business Purpose |
|-----|-------------------|
| **Total Transactions** | Measures the overall transaction volume being monitored. |
| **Confirmed Fraud Cases** | Indicates the total number of confirmed fraudulent transactions. |
| **Value Exposed to Fraud** | Quantifies the total financial value associated with fraudulent transactions. |
| **Customers Affected** | Shows how many unique customers were impacted by fraud. |
| **Risk Score Comparison** | Compares the average fraud risk score of fraudulent transactions against legitimate transactions to highlight differences in customer risk profiles. |

These KPIs allow decision-makers to assess fraud activity at a glance before exploring the supporting visualisations.

---

## Fraud Rate by Account Tenure

**Visual:** Donut Chart

**Business Question**

> Are newer customer accounts more susceptible to fraudulent activity?

To answer this question, account age was grouped into business-friendly categories using a calculated **Tenor Bucket** column.

The chart highlights how fraud rates differ across customer lifecycle stages, allowing analysts to identify whether newly created accounts require additional monitoring.

---

## Monthly Transactions vs Fraud Rate

**Visual:** Line and Clustered Column Chart

**Business Question**

> How does fraud activity change over time relative to transaction volume?

This visual combines transaction counts with fraud rate percentages, enabling trends to be analysed over time.

Displaying both measures together helps distinguish between periods of increased transaction activity and periods where fraud rates increased independently of transaction volume.

---

## Fraud Rate by Channel

**Visual:** Horizontal Bar Chart

**Business Question**

> Which transaction channels present the highest fraud risk?

Transactions were analysed by channel to compare fraud rates across customer interaction methods.

This visual assists fraud teams in identifying channels that may require stronger authentication controls or additional monitoring.

---

## Highest-Risk Customer Locations

**Visual:** Funnel Chart

**Business Question**

> Which customer locations demonstrate the highest fraud rates?

Rather than displaying every location, a dynamic ranking measure was used to display only the highest-risk customer cities.

The visual automatically updates when report filters change, allowing analysts to focus on the locations requiring the greatest attention.

---

## Dynamic Fraud Recommendations

**Visual:** Narrative Recommendation Card

One of the most distinctive features of the dashboard is the dynamic recommendation engine.

Instead of displaying static recommendations, the dashboard continuously evaluates multiple fraud indicators and automatically presents the recommendation associated with the highest calculated risk.

This allows business users to quickly understand which fraud pattern should receive immediate attention based on the current report filters.

---

# Data Model

The project uses a single transaction table named:

`fraud_detection`

Although the underlying model is intentionally simple, significant business logic was introduced through calculated columns and reusable DAX measures.

The model was designed around three principles:

- Reusable calculations.
- Clear separation between business logic and presentation.
- Dynamic measures that respond to report filters.

---

## Calculated Column

### Tenor Bucket

The **Tenor Bucket** calculated column groups customer account age into meaningful business categories.

| Account Age | Bucket |
|-------------|---------|
| 0–30 Days | New Account |
| 31–90 Days | Developing |
| 91–365 Days | Established |
| 365+ Days | Long-Term |

Grouping continuous values into categories improves readability and enables meaningful comparison across customer maturity segments.

---

# DAX Measure Architecture

To improve maintainability, measures were organised into logical folders within the Power BI model.

This made navigation easier and encouraged reusable business calculations.

## Fraud KPI Measures

| Measure | Purpose |
|----------|---------|
| Total Transactions | Counts all transactions. |
| Confirmed Fraud Cases | Counts confirmed fraudulent transactions. |
| Fraud Rate % | Calculates the percentage of fraudulent transactions. |
| Value Exposed to Fraud | Calculates the total monetary value associated with fraud. |
| Unique Customers | Counts distinct customers. |
| Customers Affected | Counts customers involved in fraudulent transactions. |
| Customers Affected Rate | Calculates the percentage of customers affected by fraud. |
| Average Fraud Risk Score | Average fraud risk score for fraudulent transactions. |
| Average Legitimate Risk Score | Average risk score for legitimate transactions. |
| Risk Score Difference | Compares fraud and legitimate customer risk scores. |

---

## Recommendation Measures

Six reusable recommendation measures were created.

Each recommendation follows the same analytical pattern:

1. Calculate the fraud rate for a specific customer segment.
2. Calculate the overall fraud rate.
3. Compare the two values using `DIVIDE()`.
4. Calculate a risk multiplier.
5. Assign a priority using `SWITCH(TRUE())`.
6. Generate a business-friendly narrative recommendation.

The recommendation categories include:

- New Beneficiaries
- Foreign Transactions
- Three or More Failed Login Attempts
- Accounts Under 30 Days Old
- USSD Transactions
- Transfer Transactions

---

## Top Priority Recommendation

A dedicated measure evaluates all recommendation measures and dynamically returns the highest-priority recommendation.

This ensures that the recommendation displayed on the dashboard automatically changes as report filters are applied.

Instead of maintaining multiple recommendation cards, a single measure communicates the most important fraud insight at any given time.

---

## Dynamic City Ranking

To support location-based analysis, a ranking measure was developed using `RANKX()`.

Rather than hardcoding cities into the visual, the measure dynamically ranks customer locations according to fraud rate.

This approach allows the funnel chart to remain fully interactive while always highlighting the highest-risk locations.

---

# Design Decisions

Several design choices were made to improve usability and maintainability.

### Separation of Numeric and Presentation Measures

Numeric calculations were intentionally separated from formatted text measures.

For example:

- `Unique Customers`
- `Unique Customers Label`

This prevents formatted text from accidentally being reused inside calculations while improving model organisation.

---

### Reusable DAX

Business logic was written once and reused throughout the report wherever possible.

This reduced duplication, simplified maintenance, and ensured consistent calculations across all visuals.

---

### Business-First Dashboard Design

Every visual was selected to answer a specific business question rather than simply displaying available data.

This approach keeps the dashboard focused on supporting fraud investigation and decision-making instead of functioning solely as a reporting interface.

# Challenges, Debugging & Analytical Validation

Developing this dashboard involved more than writing DAX measures and designing visuals. Throughout the project, I encountered several technical and analytical challenges that required investigation, testing, and iterative refinement.

Working alongside Claude (Power BI Modelling MCP Server ) accelerated the problem-solving process, but every solution required validation to ensure it aligned with the business objective and produced reliable analytical results.

The following examples highlight some of the key challenges encountered during development and the lessons learned from resolving them.

---

# Challenge 1 – Presenting Dynamic Narrative Recommendations

## The Challenge

The recommendation measures generated business-friendly narrative text of approximately 150 characters.

While technically correct, standard Card visuals are designed for displaying short values rather than descriptive text, making the recommendations difficult to present cleanly.

## Investigation

Several presentation approaches were explored:

- Splitting recommendations into separate headline and detail measures.
- Shortening the DAX output.
- Evaluating visuals better suited for narrative content.

## Resolution

The recommendation logic was retained while the presentation was redesigned to improve readability without compromising the underlying business insight.

## Key Learning

Building analytical solutions requires balancing technical implementation with effective communication. A correct calculation still needs to be presented in a way that supports decision-making.

---

# Challenge 2 – Understanding Filter Context

## The Challenge

While grouping transactions by a calculated field, `COUNTROWS()` returned the total number of transactions for every category instead of the expected grouped values.

## Investigation

Rather than assuming the calculation itself was incorrect, I reviewed the evaluation context and worked through the generated DAX to understand how Power BI was interpreting the measure.

## Resolution

Applying `CALCULATE()` introduced the required context transition, allowing the calculation to respect the current filter context.

## Key Learning

This reinforced the importance of understanding DAX evaluation context when validating AI-generated measures. AI can generate syntactically correct expressions, but technical knowledge is required to confirm that they behave as intended.

---

# Challenge 3 – Selecting the Correct Business Attribute

## The Challenge

My initial plan was to analyse fraud by `transaction_city`.

However, investigation of the dataset showed that most transaction cities were unique simulated locations, making them unsuitable for meaningful aggregation.

## Investigation

I explored alternative location fields and compared their distributions before deciding which attribute best represented customer behaviour.

## Resolution

The analysis was rebuilt using `customer_home_city`, producing meaningful comparisons and actionable geographical insights.

## Key Learning

AI can suggest analytical approaches, but selecting the most appropriate business attribute still requires exploration of the underlying data and an understanding of the business context.

---

# Challenge 4 – Debugging the Funnel Chart

## The Challenge

The funnel chart initially displayed misleading results.

The ranking values appeared instead of fraud rates, and even after correcting this, the labels displayed percentages that did not represent the actual fraud rate.

## Investigation

The issue was investigated by reviewing:

- Visual field assignments.
- Data label configuration.
- Sorting behaviour.
- Measure selection.

## Resolution

Three separate issues were identified:

- The ranking measure belonged in the visual filter rather than the Values field.
- Data labels were displaying **Percent of First** instead of the actual value.
- The visual required explicit sorting by Fraud Rate rather than alphabetically.

Correcting each configuration produced the expected analytical result.

## Key Learning

Unexpected dashboard behaviour is not always caused by DAX. Understanding how Power BI visuals interpret measures is equally important when validating analytical outputs.

---

# Challenge 5 – Designing Reusable Measures

## The Challenge

Several measures were required both as numerical calculations and as formatted display values.

Using formatted text measures inside other calculations introduced the risk of breaking dependent DAX expressions.

## Investigation

I reviewed how measures were being reused throughout the model and identified opportunities to separate calculation logic from presentation logic.

## Resolution

Numeric measures and display measures were intentionally separated.

For example:

- `Unique Customers`
- `Unique Customers Label`

This allowed numerical calculations to remain reusable while presentation measures handled formatting independently.

## Key Learning

Separating business logic from presentation improves maintainability, reduces unintended side effects, and encourages reusable DAX design.

---

# Validation Process

Every significant change followed the same validation workflow.

```text
Identify Issue
        │
        ▼
Review DAX
        │
        ▼
Test Visual
        │
        ▼
Compare Against Expected Business Result
        │
        ▼
Discuss Alternative Approaches with Claude
        │
        ▼
Refine Prompt
        │
        ▼
Update Solution
        │
        ▼
Re-test
```

This iterative process ensured that every calculation, visual, and recommendation reflected the intended business logic before being included in the final dashboard.

---

# Analytical Validation

One of the strongest lessons from this project was recognising that AI-generated solutions should be treated as hypotheses rather than final answers.

Claude significantly accelerated development by generating calculations, suggesting alternative approaches, and explaining DAX concepts. However, each suggestion was subjected to technical review before implementation.

Validation included:

- Reviewing generated DAX measures.
- Testing calculations under different report filters.
- Comparing outputs across multiple visuals.
- Investigating unexpected behaviour.
- Verifying that calculations aligned with the business objective.
- Refining prompts whenever additional context was required.

This validation process helped ensure that the final dashboard was both technically accurate and analytically meaningful.

---

# Reflection on AI-Assisted Problem Solving

One of the biggest insights from this project was recognising that effective AI-assisted analytics is not about generating code as quickly as possible.

Instead, it is about combining AI with technical understanding, critical thinking, and business knowledge.

Claude acted as a collaborative analytical partner throughout the project by accelerating idea generation, explaining concepts, and supporting debugging. My role was to validate those suggestions, question unexpected results, improve prompts, and ensure that every solution aligned with the analytical objective.

This experience reinforced that AI delivers the greatest value when paired with human expertise rather than used as a replacement for it.

# Lessons Learned

This project was more than an opportunity to build a fraud intelligence dashboard—it was an opportunity to explore how Artificial Intelligence can be integrated into a modern analytics workflow while maintaining technical accuracy and analytical integrity.

Although Claude (Power BI MCP Modelling) significantly accelerated development, one of the biggest lessons I learned is that AI is most effective when paired with a solid understanding of the underlying technology.

## AI Accelerates Development, But Knowledge Builds Confidence

Throughout the project, Claude assisted with generating DAX measures, suggesting modelling approaches, explaining concepts, and troubleshooting problems.

However, there were several occasions where AI-generated solutions produced unexpected behaviour. Some issues were caused by filter context, others by visual configuration, and some resulted from prompts that lacked sufficient business context.

Understanding DAX allowed me to:

- Read and understand AI-generated measures.
- Identify logical issues before implementation.
- Recognise when a problem was related to filter context rather than incorrect syntax.
- Edit existing measures instead of recreating them.
- Ask more targeted follow-up questions that produced better AI responses.

This experience demonstrated that AI is most valuable when it enhances technical knowledge rather than replacing it.

---

## Prompt Engineering is an Analytical Skill

One of the most valuable skills I developed during this project was learning how to communicate effectively with AI.

Early in the project I often focused on describing the technical issue without fully explaining the business objective. Although the responses were technically correct, they did not always solve the underlying analytical problem.

As I improved my prompts by providing:

- business context,
- expected outcomes,
- existing DAX logic,
- observed behaviour,
- and previous troubleshooting steps,

the quality and relevance of Claude's responses improved significantly.

This project reinforced that effective prompt engineering is an iterative process that combines technical knowledge with clear communication.

---

## Validation is Essential

One of the strongest lessons from this project was that AI-generated outputs should never be accepted without validation.

Every measure, recommendation, and visual was reviewed against expected business outcomes before being included in the final dashboard.

This validation process included:

- Reviewing DAX logic.
- Testing calculations under different filters.
- Comparing results across multiple visuals.
- Investigating unexpected behaviour.
- Refining prompts and re-testing solutions.

This iterative approach ensured that the final dashboard remained both technically accurate and analytically meaningful.

---

## Technical Growth

From a Power BI perspective, this project strengthened my understanding of:

- DAX evaluation context.
- `CALCULATE()` and context transition.
- `DIVIDE()` for comparative analysis.
- `RANKX()` and dynamic Top-N reporting.
- Reusable measure design.
- Narrative DAX measures.
- Dashboard debugging.
- Data storytelling through visualisation.

More importantly, it strengthened my confidence in validating and refining AI-assisted solutions rather than relying on them unquestioningly.

---

# Business Value

The dashboard was designed to demonstrate how fraud analytics can support operational decision-making by transforming transaction data into meaningful business insights.

The completed solution enables users to:

- Monitor overall fraud exposure.
- Track fraud trends over time.
- Compare fraud performance across transaction channels.
- Identify higher-risk customer segments.
- Prioritise fraud investigations using dynamic recommendations.
- Focus attention on customer locations with elevated fraud rates.

By combining interactive reporting with AI-assisted development, the project demonstrates how analytical workflows can become more efficient while maintaining transparency and validation.

---

# Future Enhancements

Future versions of the project could include:

- Integration with a relational data model containing separate fact and dimension tables.
- Drill-through investigation pages for customer-level analysis.
- Geospatial mapping of fraud hotspots.
- Machine learning models for fraud prediction.
- Explainable AI insights for risk scoring.
- Real-time data integration using streaming datasets.
- Row-Level Security (RLS) for role-based access.
- Automated fraud alerts using Power Automate.

These enhancements would extend the dashboard from descriptive analytics towards predictive and operational fraud intelligence.

---

# Repository Structure

```
AI-Assisted-Fraud-Intelligence-Dashboard/
│
├── README.md
├── Fraud Intelligence Dashboard.pbix
├── LICENSE
│
├── docs/
│   ├── dashboard.png
│   ├── dashboard-annotated.png
│   └── ai-workflow.png
│
└── assets/
```

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| **Power BI Desktop** | Dashboard development and data visualisation |
| **DAX (Data Analysis Expressions)** | Business calculations, KPIs, rankings, and recommendation logic |
| **Power Query** | Data preparation and transformation |
| **Claude (Power BI MCP Modelling)** | AI-assisted DAX development, analytical reasoning, debugging, and solution exploration |
| **Prompt Engineering** | Structured communication with AI to improve solution quality and analytical outcomes |
| **Git & GitHub** | Version control, documentation, and portfolio presentation |

---

# About the Author

## Tebogo Nkadimeng

I am an aspiring Data Analyst with a background in digital publishing, reporting, and business intelligence. My interests lie in using data to solve business problems, communicate insights effectively, and improve decision-making through analytics.

As AI becomes an increasingly important part of the analytics profession, I am intentionally developing the skills required to work alongside modern AI tools while maintaining strong technical foundations in data analysis, Power BI, DAX, SQL, and business problem-solving.

This project represents an important step in that journey by combining Business Intelligence, analytical thinking, and AI-assisted development into a practical, end-to-end portfolio project.

---

# Final Reflection

When I started this project, I viewed AI primarily as a tool for generating DAX measures and accelerating dashboard development.

As the project progressed, my perspective changed.

I came to appreciate that the true value of AI is not in replacing analytical work, but in enhancing it. Claude helped me explore ideas, challenge assumptions, explain concepts, and accelerate development, but it was my responsibility to validate calculations, understand the business context, refine prompts, and ensure that every result was accurate.

Perhaps the most important lesson from this project is that effective AI-assisted analytics requires more than technical tools. It requires curiosity, critical thinking, communication, and a willingness to investigate unexpected results rather than accepting the first answer.

This project reflects not only my growing technical skills in Power BI and DAX, but also my commitment to becoming an analyst who can use AI responsibly, validate its outputs, and apply it to solve real business problems.

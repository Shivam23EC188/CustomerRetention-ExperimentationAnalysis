# CustomerRetention-ExperimentationAnalysis

# 🛒 E-Commerce Funnel & Experimentation Analytics Pipeline

An end-to-end analytical data pipeline bridging the gap between raw, static e-commerce transactions and behavioral clickstream analytics. This project extracts, cleans, and transforms relational e-commerce data, models user funnels and cohort retention in MySQL, and validates product interface changes through A/B testing and statistical hypothesis testing.

---

## 📌 Business Overview & Objective
Traditional transactional datasets (like historical order receipts) capture **what** customers bought, but miss **how** they navigated the platform or **why** they dropped off. 

To solve this diagnostic gap, this project:
1. **Engineers a Hybrid Data Pipeline:** Combines real historical transactional data (Olist E-Commerce Dataset) with simulated event-level behavioral logs (clickstream events and A/B experiment assignments).
2. **Identifies Funnel Friction:** Tracks key drops across customer journey stages: `Signup` $\rightarrow$ `Activation` $\rightarrow$ `Purchase`.
3. **Measures Cohort Retention:** Evaluates long-term customer engagement across monthly acquisition cohorts.
4. **Evaluates Product Changes:** Rigorously analyzes an A/B test on a modified onboarding flow to determine statistical lift in conversion rate.

---

## 🏗️ Architecture & Data Workflow
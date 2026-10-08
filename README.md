# Poojasri Medikonda

**Data Analyst**
SQL · Excel · Python · Power BI · Data Quality · Dashboard Reporting

I build reproducible analysis that turns messy operational and customer data into clear decisions. My case studies show the full path from data-quality checks and SQL analysis to a dashboard, recommendation, and documented limitations.

[LinkedIn](https://www.linkedin.com/in/poojasree23) · [Email](mailto:poojasrimedikonda@gmail.com) · [Portfolio](https://poojasri234.github.io/)

## Selected case studies

| Project | Business decision and evidence | Recommendation and value framing |
| --- | --- | --- |
| **[NYC 311 Service Operations Analysis](https://github.com/poojasri234/nyc-311-service-operations-analysis)**<br>[Live dashboard](https://poojasri234.github.io/nyc-311-service-operations-analysis/) | Profiled **13,811** public service requests from a one-day NYC Open Data snapshot. **HEAT/HOT WATER** was the slowest category among those with 1,000+ requests: **29.03 hours** median recorded resolution time. | Review routing and capacity for this high-volume category, then test changes against a holdout period. A 10% reduction in its **53,929.88 recorded elapsed hours** is sized at **~5,393 recorded elapsed hours**; this is an illustrative service scenario, not staff time saved or a forecast. |
| **[E-commerce Sales Analysis](https://github.com/poojasri234/ecommerce-sales-analysis)**<br>[Live dashboard](https://poojasri234.github.io/ecommerce-sales-analysis/) | Applied documented duplicate and cancellation rules to public retail transactions: **£10.64M** gross invoiced sales across **19,960** eligible invoices; **84.6%** of the historical base was UK. | Monitor UK and international mix separately, then add returns, margin, delivery cost, and repeat purchase before a commercial decision. A 1% movement in the historical UK gross-invoice base is about **£90K** of invoice volume; it is not net revenue, profit, or a forecast. |
| **[Customer Churn Analysis](https://github.com/poojasri234/customer-churn-analysis)**<br>[Live dashboard](https://poojasri234.github.io/customer-churn-analysis/) | In a public telecom sample, early-tenure, month-to-month customers had **51.35%** observed churn (**1,024 of 1,994**). | Test an onboarding and plan-review experience with a randomized holdout. Preventing 10% of observed churn events in the comparable cohort would mean **~102 fewer events** and roughly a **5.1-point** change in cohort churn; this is a scenario, not a causal result or forecast. |
| **[Customer Value & Repeat Buying Analysis](https://github.com/poojasri234/customer-segmentation-analysis)**<br>[Live dashboard](https://poojasri234.github.io/customer-segmentation-analysis/) | **83.51%** of eligible gross invoice value was connected to a customer ID; the top 20% of identified customers generated **74.68%** of known-customer gross invoice value. | Improve CustomerID capture before personalisation, then test a post-first-purchase journey with a holdout. A 5-point coverage increase would make about **£0.53M** more of comparable historical gross-invoice value traceable; it is better measurement, not new sales. |
| **[Credit Default Risk Analysis](https://github.com/poojasri234/credit-default-risk-analysis)**<br>[Live dashboard](https://poojasri234.github.io/credit-default-risk-analysis/) | In a public historical sample, the two-or-more-month-delay cohort had a **69.55%** observed next-month default rate versus **13.83%** for no reported delay. | Use the cohort as a descriptive monitoring signal, never as an automated credit decision. A 1-point reduction in a comparable future 3,130-client cohort equals **~31 fewer default-labelled accounts**; financial value requires exposure, loss, cost, fairness, and causal-effect data. |

## How I make analysis reviewable

- Start with the business question, then document definitions, inclusion/exclusion rules, and data-quality checks.
- Use **SQL** for validation and cohort/aggregation queries, with reproducible Python analysis and dashboard outputs.
- Write stakeholder-focused recommendations with assumptions, measurement plans, and limitations; scenarios are labelled as illustrations, never realised impact.

## Toolkit

**SQL / SQLite** · **Excel** source-data handling · **Python / pandas** · **Power BI** report specifications and DAX measures · interactive HTML dashboards · data dictionaries · KPI definitions · data-quality checks

Each repository includes source and scope notes, SQL, validation logic, aggregate outputs, a dashboard, and a decision-focused README. Public source data is linked rather than redistributed where appropriate.

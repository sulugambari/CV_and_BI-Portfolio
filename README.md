#  Abdulrahman Sulu-Gambari
## Business Intelligence & Data Analyst

[![Email](https://img.shields.io/badge/Email-asgambari%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:asgambari@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B49_1521_387_9989-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+4915213879989)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)

---

## ⭐ About Me
I am an accomplished **Business Intelligence and Data Analyst** with extensive experience driving strategic decisions through advanced data analytics and visualization. Throughout my career, I have specialized in turning complex, raw datasets into intuitive, high-impact dashboards using tools such as **Power BI, Tableau, and Looker Studio**.

My expertise lies in collaborating closely with cross-functional teams to gather business requirements, design custom data solutions, and deliver actionable insights that directly improve operational efficiency. This portfolio showcases my commitment to technical accuracy, process optimization, and creating creative visual experiences that empower stakeholders to make informed, data-driven choices.

---

## 🎯 Vision & Mission

### Vision
To transform complex, raw datasets into intuitive, high-impact visual stories that bridge the gap between technical data and strategic action. By collaborating closely with stakeholders to understand their core needs, I deliver creative dashboard solutions and optimized processes that empower organizations to make fast, informed, and data-driven decisions.

### Mission
To change how organizations interact with data by building a culture of seamless self-service business intelligence. I aim to design data solutions that are not only visually engaging but also highly functional and accurate, ensuring that stakeholders at every level have the clear insights they need to drive long-term operational excellence and growth.

---

## 🛠️ Professional Skills & Tools

### BI & Visualisation Tools

| Tool | Proficiency |
|------|-------------|
| Power BI | ████████████░ Advanced |
| Tableau | ███████████░░ Advanced |
| Google Looker Studio | ████████████░ Advanced |
| Metabase | ████████████░ Advanced  |
| Adobe Analytics | ████████░░░░░ Intermediate |
| Salesforce CRMA+ | ████████░░░░░ Intermediate |

### Soft Skills
* Communication & Stakeholder Engagement
* Leadership & Collaboration
* Problem Solving & Adaptability

---

## 🏆 Metrics shown samples

| | |
|---|---|
| **21 Dashboard samples** built across 3 BI tools | **4 Industries** covered — Insurance, Aviation, E-Commerce, Marketing |
| **15,883 devices** tracked in real-time | **€3.7M+** in revenue analysed |
| **19,177 policy renewals** monitored | **382M+ impressions** tracked across ad platforms |
| **5,870,230 flights** monitored for quality & reliability | **17,926 marketing leads** tracked from MQL to SQL |

---

## 📈 Portfolio Dashboards

---

## 🏥 Industry: Insurance & Claims

### 1. KPI Performance Overview
**Tool:** Power BI &nbsp; <br> **Problem solved:** Insurance operations teams were manually compiling claims data from multiple sources into static spreadsheets, making it impossible to monitor live KPIs. This dashboard unified all claims and policy data into a single real-time view, enabling faster decision-making on cost reserves and partner commissions.

![KPI Performance Overview](images/PowerBI_01_KPI_Performance_Overview.jpg)

<details>
<summary>📐 Key DAX Measures</summary>

```dax
-- Loss Ratio: measures claims cost paid as a % of earned premium
Loss Ratio (%) =
DIVIDE(
    SUM(Claims[ClaimCostPaid]),
    SUM(Policies[EarnedPremium]),
    0
) * 100

-- Earned Commission
Earned Commission =
SUMX(
    Partners,
    Partners[EarnedMargin] * Partners[CommissionRate]
)

-- Policy Performance Waterfall (MoM change)
Policy MoM Change =
VAR CurrentMonth = SUM(Policies[ActivePolicies])
VAR PriorMonth =
    CALCULATE(
        SUM(Policies[ActivePolicies]),
        DATEADD(Policies[Date], -1, MONTH)
    )
RETURN CurrentMonth - PriorMonth
```
</details>

---

### 2. Renewal Repricing Report
**Tool:** Tableau &nbsp;<br>**Problem solved:** Renewal teams had no visibility into which policies were at risk of lapsing after repricing. This report surfaced renewal trends by month and policy status, allowing underwriters to prioritise outreach before cancellation windows closed.

![Renewal Repricing Report](images/Tableau_01_Renewal_Repricing_Report.jpg)

---

### 3. BDX Status Report
**Tool:** Tableau &nbsp;<br>**Problem solved:** Partner data file ingestion (BDX files) was tracked manually via email chains, causing delays in identifying failed or missing submissions. This dashboard automated status monitoring across all partners and source types, reducing data ingestion delays significantly.

![BDX Status Report](images/Tableau_02_BDX_Status_Report.jpg)

---

### 4. Flagged BDX Files
**Tool:** Tableau &nbsp;|&nbsp; **Problem solved:** When BDX files were flagged for errors or overdue submissions, operations teams had no structured way to prioritise remediation. This dashboard ranked flagged files by days overdue and error type, enabling teams to resolve the most critical data issues first.

![Flagged BDX Files](images/Tableau_03_Flagged_BDX_Files.jpg)

---

## ✈️ Industry: Aviation

> 🔗 **[View Live Interactive Report on Tableau Public](https://public.tableau.com/views/AviationReport_17793133361700/Report?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

### 5. Financial Performance
**Tool:** Tableau &nbsp;<br> **Problem solved:** Aviation finance teams were comparing airline performance across disconnected spreadsheets with no standard metric definitions. This dashboard brought together revenue, operating margin, CASK, RASK, and load factor across 5 airlines into a single comparable view.

![Financial Performance](images/Tableau_04_Financial_Performance.jpg)

---

### 6. Sustainability & Efficiency
**Tool:** Tableau &nbsp;<br> **Problem solved:** With growing pressure on airlines to report emissions data, there was no centralised view linking fuel consumption, CO2 intensity, and SAF adoption by region. This dashboard gave sustainability teams a clear picture of where efficiency gains and SAF blending were having the most impact.

![Sustainability and Efficiency](images/Tableau_05_Sustainability_and_Efficiency.jpg)

---

### 7. Quality & Reliability
**Tool:** Tableau &nbsp;<br> **Problem solved:** Operations managers needed a consistent way to benchmark on-time performance, cancellation rates, and customer satisfaction across multiple airlines and quarters. This dashboard standardised KPI definitions and enabled direct peer comparison in one view.

![Quality and Reliability](images/Tableau_06_Quality_and_Reliability.jpg)

---

## 🛒 Industry: E-Commerce

### 8. Profitability
**Tool:** Looker Studio &nbsp;<br> **Problem solved:** E-commerce managers were spending hours each week pulling Shopify reports manually and cross-referencing them in Excel. This dashboard connected directly to Shopify data to automate profitability reporting, surfacing order value trends and traffic source ROI at a glance.

![Profitability](images/LookerStudio_01_Profitability.jpg)

---

### 9. Site and Behaviour
**Tool:** Looker Studio &nbsp;<br> **Problem solved:** The marketing team lacked a unified view of how different user cohorts were converting across devices and channels. By combining Google Analytics session data with revenue metrics, this dashboard helped identify underperforming acquisition channels and informed budget reallocation.

![Site and Behaviour](images/LookerStudio_02_Site_and_Behaviour.jpg)

<details>
<summary>📐 Key SQL Logic</summary>

```sql
-- New vs Returning user revenue contribution
SELECT
    user_type,
    COUNT(DISTINCT session_id)      AS sessions,
    SUM(transaction_revenue)        AS total_revenue,
    AVG(transaction_revenue)        AS avg_revenue_per_session,
    SUM(transactions)               AS total_transactions,
    ROUND(
        SUM(transactions) * 1.0 / NULLIF(COUNT(DISTINCT session_id), 0), 4
    )                               AS conversion_rate
FROM analytics_sessions
WHERE date BETWEEN '2023-03-01' AND '2023-04-30'
GROUP BY user_type
ORDER BY total_revenue DESC;

-- Top revenue-generating campaigns
SELECT
    campaign,
    SUM(revenue)        AS total_revenue,
    COUNT(sessions)     AS total_sessions,
    ROUND(SUM(revenue) / NULLIF(COUNT(sessions), 0), 2) AS revenue_per_session
FROM campaign_performance
WHERE date BETWEEN '2023-03-01' AND '2023-04-30'
  AND campaign IS NOT NULL
GROUP BY campaign
ORDER BY total_revenue DESC
LIMIT 10;
```
</details>

---

### 10. Acquisition and Advertising
**Tool:** Looker Studio &nbsp;|&nbsp; **Problem solved:** The paid media team was managing Google Ads, Meta Ads, and Amazon campaigns in separate platform dashboards, making cross-channel budget comparison nearly impossible. This dashboard consolidated all three into one view, enabling direct ROAS comparison and faster spend optimisation.

![Acquisition and Advertising](images/LookerStudio_03_Acquisition_and_Advertising.jpg)

---

## 📣 Industry: Marketing

### 11. Marketing Report (KUR & Channel Performance)
**Tool:** Power BI &nbsp;<br> **Problem solved:** Senior marketing leadership had no single report that showed cost efficiency (KUR), net revenue margin (NRM), and order volume across all channels simultaneously. This report replaced a weekly manual slide deck and enabled self-service access to live channel performance.

![Marketing Report](images/PowerBI_06_Marketing_Report.jpg)

<details>
<summary>📐 Key DAX Measures</summary>

```dax
-- KUR: Cost-to-Revenue ratio (Kosten-Umsatz-Relation)
KUR (%) =
DIVIDE(
    SUM(Marketing[Cost]),
    SUM(Marketing[NettoSales]),
    0
) * 100

-- NRM: Net Revenue Margin
NRM =
SUM(Marketing[NettoSales]) - SUM(Marketing[Cost])

-- CVR: Conversion Rate
CVR (%) =
DIVIDE(
    SUM(Marketing[Orders]),
    SUM(Marketing[Sessions]),
    0
) * 100

-- CPO: Cost per Order (Netto)
CPO Netto =
DIVIDE(
    SUM(Marketing[Cost]),
    SUM(Marketing[Orders]),
    0
)

-- CLV: Customer Lifetime Value
CLV =
DIVIDE(
    SUM(Marketing[NettoSales]),
    DISTINCTCOUNT(Marketing[CustomerID]),
    0
)
```
</details>

---

### 12. Performance Overview
**Tool:** Power BI &nbsp;<br> **Problem solved:** Cross-channel performance reviews required pulling data from multiple source reports and rebuilding charts each week. This dashboard automated the aggregation of sessions, impressions, and KUR KPIs by channel, cutting weekly reporting preparation time significantly.

![Performance Overview](images/PowerBI_07_Performance_Overview.jpg)

---

### 13. Organic Search & Brand Effects
**Tool:** Power BI &nbsp;<br> **Problem solved:** The SEO and brand team needed a reliable way to track whether brand search volume was growing in response to campaigns. This dashboard tracked Google Search Console impressions and CTR over time, broken down by device, to measure brand visibility gains.

![Organic Search and Brand Effects](images/PowerBI_08_Organic_Search_Brand_Effects.jpg)

---

### 14. Market Research (Segments)
**Tool:** Power BI &nbsp;<br> **Problem solved:** Brand health survey data was delivered as raw CSVs with no ongoing trend view. This dashboard visualised ad awareness and brand awareness across target and non-target groups over time, enabling brand managers to correlate campaign spend with awareness shifts.

![Market Research Segments](images/PowerBI_09_Market_Research_Segments.jpg)

---

### 15. Product Activity Revenue Report
**Tool:** Power BI &nbsp;<br> **Problem solved:** The product team lacked a clear view of how revenue from each product cohort evolved after the signup date. By combining month-over-month revenue with cohort analysis, this dashboard helped identify which acquisition periods produced the highest long-term revenue.

![Product Activity Revenue Report](images/PowerBI_10_Product_Activity_Revenue_Report.jpg)

<details>
<summary>📐 Key DAX Measures</summary>

```dax
-- MoM Revenue Growth
MoM Revenue % =
VAR CurrentMonthRev = SUM(Revenue[Amount])
VAR PriorMonthRev =
    CALCULATE(
        SUM(Revenue[Amount]),
        DATEADD(Revenue[PurchaseDate], -1, MONTH)
    )
RETURN
    DIVIDE(CurrentMonthRev - PriorMonthRev, PriorMonthRev, 0) * 100

-- Cohort Revenue: cumulative revenue by months since signup
Cohort Revenue =
CALCULATE(
    SUM(Revenue[Amount]),
    FILTER(
        Revenue,
        Revenue[MonthsSinceSignup] <= MAX(Revenue[MonthsSinceSignup])
    )
)

-- YoY Revenue Change
YoY Revenue % =
DIVIDE(
    SUM(Revenue[Amount]) -
    CALCULATE(SUM(Revenue[Amount]), SAMEPERIODLASTYEAR(Revenue[PurchaseDate])),
    CALCULATE(SUM(Revenue[Amount]), SAMEPERIODLASTYEAR(Revenue[PurchaseDate])),
    0
) * 100
```
</details>

---

### 16. Marketing Lead Source
**Tool:** Power BI &nbsp;<br> **Problem solved:** The demand generation team had no unified view of how leads progressed from creation through MQL to SQL stage. This dashboard connected CRM and marketing automation data to give leadership a live funnel view with historical trend analysis.

![Marketing Lead Source](images/PowerBI_11_Marketing_Lead_Source.jpg)

<details>
<summary>📐 Key DAX Measures</summary>

```dax
-- MQL Conversion Rate
MQL Conversion Rate =
DIVIDE(
    COUNTROWS(FILTER(Leads, Leads[Stage] = "MQL")),
    COUNTROWS(FILTER(Leads, Leads[Stage] = "Marketing Lead")),
    0
) * 100

-- SQL Conversion Rate (from MQL)
SQL Conversion Rate =
DIVIDE(
    COUNTROWS(FILTER(Leads, Leads[Stage] = "SQL")),
    COUNTROWS(FILTER(Leads, Leads[Stage] = "MQL")),
    0
) * 100

-- % Marketing Leads (share of total leads from marketing)
% Marketing Leads =
DIVIDE(
    COUNTROWS(FILTER(Leads, Leads[Source] = "Marketing")),
    COUNTROWS(Leads),
    0
) * 100
```
</details>

---

### 17. Plan vs. Actuals
**Tool:** Power BI &nbsp;<br> **Problem solved:** Budget vs. performance reporting was done quarterly in static slides with no drill-down capability. This dashboard replaced those slides with a live view comparing planned vs. actual cost and leads by country and channel, enabling in-quarter course corrections.

![Plan vs Actuals](images/PowerBI_12_Plan_vs_Actuals.jpg)

---

## 📡 Industry: IoT & Device Analytics

### 18. Device Overview Map
**Tool:** Power BI &nbsp;<br> **Problem solved:** Field operations teams had no geographic view of where devices were deployed or how they were performing. This dashboard mapped 15,883 devices across Europe with live SQF and EsNo metrics, enabling remote performance monitoring without manual field reports.

![Device Overview Map](images/PowerBI_02_Device_Overview_Map.jpg)

---

### 19. KPI Differences
**Tool:** Power BI &nbsp;<br> **Problem solved:** Quality engineers needed to quickly identify which devices had the largest deviation between two performance parameters (SQF and EsNo). This dashboard ranked all devices by differential and flagged outliers, replacing a manual spreadsheet review process.

![KPI Differences](images/PowerBI_03_KPI_Differences.jpg)

<details>
<summary>📐 Key DAX Measures</summary>

```dax
-- SQF Difference between system A and B
SQF Diff =
SUM(Devices[SQF_A]) - SUM(Devices[SQF_B])

-- EsNo Difference
EsNo Diff =
SUM(Devices[EsNo_A]) - SUM(Devices[EsNo_B])

-- Flag devices outside acceptable range
Out of Range Flag =
IF(
    ABS([SQF Diff]) > 10 || ABS([EsNo Diff]) > 5,
    "Out of Range",
    "Within Range"
)

-- Highest SQF Diff (for ranking table)
Highest SQF Diff =
RANKX(
    ALL(Devices[SerialNumber]),
    [SQF Diff],
    ,
    DESC,
    DENSE
)
```
</details>

---

### 20. SQF Intervals
**Tool:** Power BI &nbsp;<br> **Problem solved:** Engineers needed to understand the statistical distribution of device performance to set quality thresholds. The bell-curve visualisation of EsNo values confirmed whether device performance was normally distributed and identified how many devices fell outside the acceptable interval range.

![SQF Intervals](images/PowerBI_04_SQF_Intervals.jpg)

---

### 21. KPI Performances
**Tool:** Power BI &nbsp;<br> **Problem solved:** Tracking whether device quality was consistent across a large fleet required comparing two measurement parameters (A and B) simultaneously across thousands of serial numbers. This dashboard enabled engineers to spot systematic deviations at scale rather than reviewing individual device logs.

![KPI Performances](images/PowerBI_05_KPI_Performances.jpg)

---

## 🌐 Live Interactive Dashboard Sample

> This Aviation report is published live on Tableau Public — explore the full interactive version below.

**[🔗 Open in Tableau Public](https://public.tableau.com/views/AviationReport_17793133361700/Report?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

> **Note for GitHub viewers:** The Tableau embed is interactive when this README is viewed via a hosted site (e.g. GitHub Pages). On GitHub.com itself, use the direct link above to access the live report.

---

## 🫱🏽‍🫲🏿 Let's Work Together
Feel free to reach out if you are looking for a dedicated Data Analyst to bring actionable insights to your team!

* **Email:** [asgambari@gmail.com](mailto:asgambari@gmail.com)
* **Phone:** +49 1521 387 9989

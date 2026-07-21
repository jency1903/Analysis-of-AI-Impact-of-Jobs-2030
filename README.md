# Analysis of AI Impact on Jobs 2030 (Power BI)

A single-page Power BI dashboard that analyzes the projected impact of AI on jobs by 2030 — covering hiring trends, automation, AI tool usage, job satisfaction, replacement risk, performance, and future demand — across countries, industries, job titles, company sizes, and education levels, built on top of an `AI_Impact_on_Jobs_2030` dataset.

## 📄 File

- **`Analysis_of_AI_Impact_of_Jobs_2030.pbix`** — Power BI Desktop report file

## 📊 Data Model

The report is built on a single table:

| Table | Fields |
|---|---|
| `AI_Impact_on_Jobs_2030` | Country, Industry, Job_Title, Company_Size, Education_Level, Hiring_Trend_2026, Automation_Level, AI_Tool_Usage, Job_Satisfaction, AI_Replacement_Risk, Performance_Score, Future_Demand_Score, Job_Growth_2030 |

## 🖥️ Report Page — "Page 1" (4500 × 3200)

| Visual | Type | Details |
|---|---|---|
| **Hearing Trend of 2026 by Job Title** | Stacked Area Chart | Count of Hiring_Trend_2026 broken down by Job_Title |
| **Performance Score in each Countries** | Treemap | Sum of Performance_Score sized by Country |
| **Automation Level and AI Usage of Country** | Line & Stacked Column Combo Chart | Count of Automation_Level and Count of AI_Tool_Usage by Country |
| **Job Satisfaction By AI Tools In Industries** | Line & Stacked Column Combo Chart | Count of Job_Satisfaction and Count of AI_Tool_Usage by Industry |
| **AI Replacement Risk by Company Size** | Pie Chart | Sum of AI_Replacement_Risk broken down by Company_Size |
| **AI Replacement Risk Measure** | Gauge | Sum of AI_Replacement_Risk as the value, Sum of Future_Demand_Score as the target |
| **Max of AI Replacement** | Card | Max of AI_Replacement_Risk |
| **Sum of Performance Score** | Card | Sum of Performance_Score |
| **Future Demand Score** | Card | Sum of Future_Demand_Score |
| **Total Job Satisfastion** | Card | Count of Job_Satisfaction |
| **Average Job Growth in 2030** | Card | Average of Job_Growth_2030 |
| **Performance Score of AI Replacement Risk by Industry** | Scatter Chart | Sum of Performance_Score (X) vs. Sum of AI_Replacement_Risk (Y), categorized by Industry |
| **Slicer** | Slicer | Filter by Country |
| **Slicer** | Slicer | Filter by Job_Title |
| **Slicer** | Slicer | Filter by Industry |
| **Slicer** | Slicer | Filter by Company_Size |
| **Slicer** | Slicer | Filter by Education_Level |
| **Action Button** | Action Button | Navigation/bookmark button |
| **Background Shape** | Shape | Decorative layout element |

## 🖼️ Background Image

An AI/technology–human interaction image is registered as a report resource and used as a visual/background element on the page.

## 🎨 Theme

No custom theme file applied — the report uses Power BI's default theme.

## 🔍 Key Insights the Report Enables

- Track **AI replacement risk, performance score, future demand score, job satisfaction, and average job growth for 2030** at a glance via KPI cards
- Analyze **hiring trends for 2026 across job titles**
- Compare **performance scores across countries** using the treemap
- Examine **automation level and AI tool usage patterns by country**
- Explore **job satisfaction in relation to AI tool usage across industries**
- Assess **AI replacement risk distribution by company size**
- Monitor **AI replacement risk against future demand targets** using the gauge
- Study the **relationship between performance score and AI replacement risk by industry**
- Filter the entire report interactively by **Country, Job Title, Industry, Company Size, and Education Level**

## 🛠️ Requirements

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to open and edit `Analysis_of_AI_Impact_of_Jobs_2030.pbix`
- No external data source connections required beyond the embedded dataset

## 📂 Usage

1. Clone/download this repository
2. Open `Analysis_of_AI_Impact_of_Jobs_2030.pbix` in Power BI Desktop
3. Use the slicers (Country, Job Title, Industry, Company Size, Education Level) to filter the report
4. Use the action button to navigate between report views/bookmarks

# Excel Projects

Excel analysis and dashboard projects. Currently one project: **Social Buzz content analysis**.

## Social Buzz content analysis (Excel)

An Excel rebuild of the Accenture North America *Data Analytics and Visualization* job simulation on Forage.
The original simulation work, visualised in Tableau, is in
[Accenture-Simulation](https://github.com/SujanT21/Accenture-Simulation). This version focuses on doing the
whole job in Excel: cleaning, pivot tables, an interactive dashboard, and a client presentation.

### The brief

Social Buzz, a fictional social media platform with 100,000+ posts a day (about 36.5M a year), wanted to know
its **top 5 content categories by popularity** to shape its content strategy.

### What I did

| Step | Excel work |
|---|---|
| Cleaning | Text to Columns, Remove Duplicates, filters and conditional formatting to fix and flag bad rows |
| Joining | VLOOKUP to bring category and reaction score onto every reaction record |
| Analysis | Pivot tables with grouping and calculated fields to rank ~24,500 reactions across 16 categories |
| Dashboard | Interactive dashboard with slicers and a time-trend line chart (June 2020 to June 2021) |
| Presentation | 11-slide client deck with insights, recommendations and next steps |

### Key insights

| Rank | Category | Popularity score |
|---|---|---|
| 1 | Animals | ~74,965 |
| 2 | Science | ~71,168 |
| 3 | Healthy Eating | ~69,339 |
| 4 | Technology | ~68,738 |
| 5 | Food | ~66,676 |

- **Food-related categories engage strongly**, and Healthy Eating outranks Food: the audience looks health-conscious.
- **January was the most active month**, likely post-holiday social activity.
- **The top 5 are close together**, with Animals only slightly ahead; without balanced recommendations one
  category could crowd out the rest.

**Recommendations:** healthy-eating campaigns with brand partners, balanced content algorithms, and scaling
the sample dashboard into live analytics.

### Repository contents

| Path | What it is |
|---|---|
| `Brief/` | Client brief, data model, stakeholder chart and presentation guide |
| `Dataset/` | Raw CSVs: `Content`, `Reactions`, `ReactionTypes` |
| `Processed data, Pivot table & Dashboard/` | Excel workbook: cleaned data, pivot tables and the dashboard |
| `Insight Presentation/` | Client presentation (`.pptx`) |
| `The Data Analyst's role in Identifying Stakeholders.docx` | Short note on stakeholder mapping for the project |

### How to open

Open the workbook in `Processed data, Pivot table & Dashboard/` in Excel (2016 or later) and use the slicers on
the dashboard sheet. The deck is in `Insight Presentation/`.

### Skills

Excel data cleaning, VLOOKUP and IF logic, data validation, pivot tables and calculated fields, dashboards with
slicers, and presenting insights to stakeholders.

The brief, data and company are fictional and were provided by Accenture through Forage.

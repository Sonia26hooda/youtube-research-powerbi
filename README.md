📊 YouTube Research & Strategy Dashboard
Built with Power BI | Content Analytics | Engagement Optimization
> **Business Question:** What content strategy — title style, thumbnail type, and upload timing — maximizes views and engagement on YouTube in the finance and productivity niche?
---
🧩 Problem Statement
YouTube creators and digital marketers in the finance/productivity space struggle to identify what actually drives views beyond guesswork. This dashboard was built to answer:
Which thumbnail + title combinations consistently outperform the average?
When do viral outliers occur — and why?
Does a higher CTR always lead to more views, or are there exceptions?
Which content formats drive genuine engagement (likes + comments) vs passive views?
---
📸 Dashboard Preview
![YouTube Research Dashboard](./Youtube%20Data%20Analysis.png)
---
🔍 Key Insights from the Data
Finding	What the Data Shows
🏆 Best thumbnail combo	Face+Emotion thumbnails + Number-style titles averaged 2× more views than any other combination
📅 Viral seasonality	Outlier videos (>2× average views) clustered in April and June — likely tied to tax season and mid-year financial reviews
📈 CTR threshold	Videos with CTR > 6% had a disproportionately higher view count, suggesting a non-linear tipping point
💬 Engagement sweet spot	Problem-Solution format videos had the highest like-to-view ratio, indicating stronger audience trust even at lower view counts
📉 Diminishing returns	Subscriber growth did not correlate linearly with views — new uploads mattered more than total channel size
---
🛠️ Tools & Techniques
Power BI Desktop — data modelling, DAX measures, interactive visuals
DAX Measures used:
`Above_Avg_Ratio` — flags videos exceeding 2× average views
`CTR Outlier Flag` — identifies high-CTR low-view anomalies
`Engagement Rate` — (Likes + Comments) / Views
Visuals built: KPI Cards, Line Charts, Scatter Plot, Heatmap Matrix, Bar Charts
Dataset: Simulated YouTube video metrics across finance & productivity niche (`YouTube_RealStyle_Sample_PowerBI.csv`)
---
📂 Repository Structure
```
youtube-research-powerbi/
│
├── YouTube_RealStyle_Sample_PowerBI.csv   # Source dataset
├── YouTube Research and Analysis Dashboard.pbix  # Power BI file
├── YouTube Research and Analysis Dashboard.pdf   # Exported dashboard (viewable without Power BI)
├── Youtube Data Analysis.png              # Dashboard screenshot
└── README.md                             # Project documentation
```
---
🚀 How to Explore This Project
Option A — Just want to see the dashboard?
→ Open `YouTube Research and Analysis Dashboard.pdf` directly in your browser. No software needed.
Option B — Want to interact with it?
Install Power BI Desktop (free)
Download `YouTube Research and Analysis Dashboard.pbix`
Open in Power BI Desktop and explore the filters & visuals
Option C — Want to rebuild or extend it?
Use `YouTube_RealStyle_Sample_PowerBI.csv` as your data source
Connect it to Power BI and build your own measures on top
---
💡 What I Learned
How to use conditional formatting in matrix visuals to surface winning content patterns at a glance
Building outlier detection logic with DAX without using Python or R
The difference between vanity metrics (views) and signal metrics (engagement rate, CTR threshold effects)
Structuring a dashboard for a non-technical audience — where every visual answers one specific business question
---
🔗 Connect
Sonia Dalal — Finance & Data Analytics Professional
![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)
![Credly](https://img.shields.io/badge/Credly-FF6B00?style=flat&logo=credly&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
> 🎓 Google Data Analytics Professional Certificate | Open to Remote Data Analyst Roles

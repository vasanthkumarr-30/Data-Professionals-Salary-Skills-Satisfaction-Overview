# 📊 Data Professionals: Salary, Skills & Satisfaction Overview

> **An end-to-end Power BI analytics project** analyzing survey responses from **630 global data professionals** — uncovering compensation trends, programming language preferences, career entry barriers, and workplace satisfaction metrics.

---

## 🔍 Project Overview

This project delivers an interactive Power BI dashboard built on real-world survey data collected from data professionals worldwide. It answers critical questions hiring managers, HR leaders, and aspiring data professionals often ask:

- Which data roles command the highest salaries?
- How hard is it to break into the data field?
- What programming languages dominate the industry?
- How satisfied are data professionals with work/life balance and compensation?

The end result is a **clean, executive-ready dashboard** that transforms raw, messy survey data into actionable business intelligence.

---

## 📁 Repository Structure

data-professionals-survey/
│
├── 📂 Cleaned Dataset/
│   └── Cleaned_Data_Set.xlsx           # Cleaned & transformed dataset
│
├── 📂 Power BI Dashboard/
│   └── Data_Professional_Survey.pbix   # Power BI dashboard/report file
│
├── README.md                           # Project documentation
│

│├── 📂 Raw Dataset/
│   └── Row_Data_Set.xlsx               # Original raw survey dataset
│
└── 📂 Assets/
    └── data_professional_Survey.png    # Dashboard preview image
```

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Dashboard development & visualization |
| **Power Query (M Language)** | Data cleaning & transformation |
| **Microsoft Excel** | Raw data storage & initial inspection |
| **DAX (Data Analysis Expressions)** | Calculated measures & KPIs |

---

## 📊 Dashboard Highlights

### Key Metrics at a Glance
| Metric | Value |
|--------|-------|
| 👥 Total Survey Participants | **630** |
| 🎂 Average Age of Participants | **29.87 years** |
| ⚖️ Work/Life Balance Happiness | **5.74 / 10** |

### Visualizations Included

1. **Average Salary by Job Title** — Horizontal bar chart comparing salaries across Data Scientists, Data Engineers, Data Architects, Data Analysts, Database Developers, and Students
2. **Difficulty to Break into Data** — Distribution of perceived career entry barriers (Very Easy → Very Difficult)
3. **Favorite Programming Language** — Voter breakdown by role for Python, R, SQL, C/C++, JavaScript, and Java
4. **Country Filter Slicer** — Interactive filter for Canada, India, United Kingdom, United States, and Other
5. **Happiness with Work/Life Balance** — Gauge chart (scale 0–10)
6. **Average Salary by Gender** — Donut chart segmented by Male/Female
7. **Count of Participants KPI Card**
8. **Average Age KPI Card**

---

## 🔄 Data Transformation Process

The raw dataset required significant cleaning via **Power Query** before analysis:

- ✅ Parsed free-text salary ranges (e.g., "55k-65k") into numeric **Average Salary** values
- ✅ Standardized job titles by consolidating write-in responses into canonical categories
- ✅ Cleaned country names from free-text to enumerated categories
- ✅ Extracted programming language preferences from multi-select fields
- ✅ Removed duplicate entries and nulls from identifier columns
- ✅ Renamed columns for readability and BI compatibility

---

## 💡 Key Insights

- 🥇 **Data Scientists** earn the highest average salary, significantly outpacing other roles
- 🐍 **Python** is the overwhelmingly dominant programming language across all data roles
- 🚧 The majority of respondents found breaking into data **"Neither easy nor difficult"** (269 respondents), while nearly as many found it **"Difficult"** (156)
- ⚖️ Work/life balance satisfaction scores **5.74/10** — indicating moderate, improvable satisfaction
- 🌍 The survey captures professionals from **USA, UK, Canada, India**, and globally distributed respondents

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free download)
- Microsoft Excel (for viewing raw/cleaned data)

### Steps to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/vasanthkumarr-30/data-professionals-survey.git
   cd data-professionals-survey
   ```

2. **Open the dashboard**
   - Launch **Power BI Desktop**
   - File → Open → `dashboard/Data_Professional_Survey.pbix`

3. **Explore the data**
   - Open `data/Cleaned_Data_Set.xlsx` in Excel to inspect the cleaned dataset
   - Compare with `data/Row_Data_Set.xlsx` to understand the transformation

4. **Interact with the dashboard**
   - Use the **Country slicer** to filter all visuals by geography
   - Hover over charts for detailed tooltips
   - Click any bar/segment to cross-filter other visuals

---

## 📸 Dashboard Preview

![Data Professionals Dashboard](assets/data_professional_Survey.png)

---

## 📋 Dataset Description

| Column | Description |
|--------|-------------|
| `Unique ID` | Anonymous respondent identifier |
| `Q1 - Job Title` | Current data role |
| `Q2 - Career Switch` | Whether the respondent switched careers into data |
| `Q3 - Yearly Salary` | Salary range in USD |
| `Average Salary` | Midpoint calculated from salary range |
| `Q4 - Industry` | Industry of employment |
| `Q5 - Favorite Language` | Preferred programming language |
| `Q6 - Happiness Scores` | Satisfaction across 6 dimensions (1–10) |
| `Q7 - Break-in Difficulty` | Perceived difficulty entering the data field |
| `Q8 - Job Priority` | Most important factor in next job search |
| `Q9 - Gender` | Male / Female |
| `Q10 - Age` | Current age |
| `Q11 - Country` | Country of residence |
| `Q12 - Education` | Highest level of education |
| `Q13 - Ethnicity` | Self-reported ethnicity |

---

## 🎯 Skills Demonstrated

- **Data Wrangling** — Cleaning unstructured survey data with Power Query
- **DAX Calculations** — Building dynamic measures for KPIs and averages
- **Dashboard Design** — Crafting an executive-grade, intuitive BI layout
- **Storytelling with Data** — Translating 630 raw responses into clear, decision-ready insights
- **Cross-filtering & Interactivity** — Building a fully interactive, slicer-driven report

---

## 👤 Author

**[Your Name]**
- 💼 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- 📧 Email: your.email@gmail.com
- 🐙 GitHub: [github.com/yourusername](https://github.com/yourusername)

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, adapt, and share with attribution.

---

> ⭐ If you found this project helpful or insightful, please consider giving it a **star** — it helps others discover the work!

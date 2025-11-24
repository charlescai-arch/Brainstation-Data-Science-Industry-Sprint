# Brainstation-Data-Science-Industry-Sprint
As part of the Brainstation Data Science Bootcamp, we were partnered with data science professionals to work on a business challenge analyzing customer complaints to uncover pain points and guide product recommendations.

# 🏦 Wealthsimple Industry Sprint
## 📌 Executive Summary
A dataset from the US Consumer Financial Protection Bureau (CFPB) was used for this
analysis. To identify contemporary consumer issues with traditional financial institutions,
the dataset was limited to complaints against the top 30 US banks (by asset size)
between 2020 and 2025. Matplotlib, Seaborn, Tableau were used to generate visuals. Complaint narratives were investigated using LLM and basic NLP/Regex techniques.

Key findings include:
- Growth of Other transaction problems across domestic & international transfers
- Increase in deposit hold complaints, indicating slow or unpredictable clearing processes
- Customer narratives reveal frustration with unexplained failures, lack of transparency, and delayed availability of funds
- Customer service issues are underrepresented in the dataset, but narrative analysis shows they are the underlying driver of most transfer and deposit complaints.

| File                     | Description                               |
| ------------------------ | ----------------------------------------- |
| `executive_summary.pdf`  | 1-page summary of findings                |
| `presentation.pdf`       | Final stakeholder slide deck              |
| `notebook.ipynb`         | Jupyter notebook with analysis            |
| `tableau_dashboard.docx` | Tableau packaged workbook link            |
| `Cleaned_data.docx`      | Cleaned dataset download link             |

## 🔍 Data & Methods
Dataset: CFPB Consumer Complaints database
Tools Used: Python (Pandas, Scikit-learn, Matplotlib), Tableau
Core Methods:
- NLP keyword extraction
- Complaint narrative theme grouping
- Time-series analysis of complaint growth
- Product & issue categorization
- Visual storytelling via Tableau

## 📈 Key Insights
- Deposit & Withdrawal Issues Are Rapidly Growing
- “Other Transaction Problems” Are the Fastest-Growing Transfer Issue
- Customers Lack Transparency Into Transfer Failures and Timelines
- Customer Service Pain Points Are Underrepresented but Pervasive

## 💡 Recommendations
- Implement a risk-scoring model to reduce hold times based on deposit and account characteristics (e.g., long-tenured, low-risk accounts).
- Build a predictable, trackable money movement system
- Surface clear reasons for transfer failures
- Provide transparency around deposit timelines
- Proactively notify users when holds or delays occur
- Strengthen customer service touchpoints across the board

## 👥 Team
Charles Cai
Eric Robinson
George Daramola
Ryan Austin


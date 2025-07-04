# 📊 LinkedIn Job Posts Insights

This project analyzes and visualizes job posting data scraped from LinkedIn. The goal is to clean and process real-world job data to uncover trends related to job titles, industries, employment types, seniority levels, and geographic distribution.

---

## 📁 Dataset

- **Source**: `linkedin_job_posts_insights.xlsx`
- **Content**: Raw job postings including job title, company, location, industry, employment type, seniority level, and posting date.

---

## 🔧 Key Steps

### 1. **Data Cleaning**
- Removed irrelevant columns and handled missing values.
- Standardized column names and text formats.
- Cleaned `job_title` values (e.g., removed numbers, punctuation, and whitespace issues).
- Replaced nulls and inconsistent labels across categorical features.

### 2. **Data Transformation**
- Extracted month names from dates for trend analysis.
- Aggregated counts for key metrics like:
  - Top job titles
  - Common industries
  - Seniority distribution
  - Employment types
  - Posting locations

---

## 📊 Visualizations

| Chart | Description |
|-------|-------------|
| 📌 **Top Job Titles** | Bar chart of the top 10 job titles |
| 🧑‍💼 **Seniority Levels** | Seniority level distribution |
| 🏙️ **Top Cities** | Top cities with most job opportunities |
| 🏢 **Top Hiring Companies** | Top 10 companies posting jobs |
| 📈 **Monthly Trends** | Time-series trend of job postings per month |
| 🧩 **Employment Types** | Pie chart of full-time, part-time, internships, etc. |
| ☁️ **Job Title WordCloud** | Visual of most common words in job titles |
| 🔥 **Industry vs. Seniority** | Heatmap showing seniority levels across industries |

---

## 📁 Output Files

| File Name | Description |
|-----------|-------------|
| `final_cleaned_job_titles.xlsx` | Final, processed dataset ready for analysis |

---

## 🛠 Tools & Libraries

- **Python**
- **Pandas** – data processing
- **Seaborn & Matplotlib** – visualizations
- **WordCloud** – keyword cloud generation
- **scikit-learn** – preprocessing

---

## 📌 How to Run

1. Make sure you have Python 3.7+ installed.
2. Install required libraries:
   ```bash
   pip install pandas seaborn matplotlib wordcloud scikit-learn openpyxl

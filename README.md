# 💼 Indian Data Professionals Salary Analysis

This project explores salary trends across different job roles and cities in India using real-world data. It combines data wrangling, exploratory analysis, statistical testing, and a final interactive Tableau dashboard.

---


---

## 🛠 Tools & Technologies

- **Python (Pandas, Seaborn, Matplotlib)**
- **Statistical Tests (Scipy, Shapiro-Wilk, Kruskal-Wallis, Mann-Whitney U)**
- **Tableau** for final dashboard
- **Jupyter Notebook** for analysis and visualizations

---

## 🔍 Key Steps

### 1. Data Cleaning
- Removed nulls and duplicates
- Parsed salary strings (₹6,00,000/yr → 600000)
- Created new columns: `job_category`, `salary_in_inr`

### 2. Exploratory Data Analysis
- Top job roles and cities in dataset
- Salary distribution by role and city
- Outlier detection and skewness analysis

### 3. Statistical Testing
- ✅ Shapiro-Wilk: Checked for normality
- ✅ Levene’s test: Checked for equal variances
- ✅ Kruskal-Wallis: Salary difference across job roles
- ✅ Mann-Whitney U: Salary comparison between cities (e.g., Bangalore vs Pune)

### 4. Tableau Dashboard
Interactive salary dashboard built with Tableau Public.

> 🔗 [**View Live Dashboard**](https://public.tableau.com/app/profile/priyanka.malavade/viz/salary_trends/Dashboard1?publish=yes)

---

## 📊 Dashboard Preview

![Dashboard Screenshot](dashboard_preview.png) <!-- Replace this with your image name or screenshot -->

---

## 📈 Key Insights

- **Data Scientists** dominate the job market
- **Bangalore** leads in number of roles and salary levels
- Salaries **differ significantly** across roles and cities (based on statistical tests)
- The distribution of salaries is **right-skewed** (not normally distributed)

---

## 🚀 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/salary-analysis.git
   cd salary-analysis

# Create virtual environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate


## 📬 Contact

**Priyanka Malavade**  
*Aspiring Data Analyst*

- 📫 [LinkedIn](https://www.linkedin.com/in/priyanka-malavade-b34677298/)
- 📊 [Tableau Public Profile](https://public.tableau.com/app/profile/priyanka.malavade/viz/salary_trends/Dashboard1)

---

## ⭐ Project Status: Completed 

This project is complete and part of my Data Analyst portfolio.  
More dashboards and case studies coming soon!



AI Job Market & Salary Trends 2025

This project explores the **global state of the AI job market in 2025** using real-world data from Kaggle. Through Python-based data science techniques and economic interpretation, we analyze how factors like **job title**, **experience level**, **company location**, and **remote work** influence salaries in the AI sector.

---

Dataset

- **Source**: [Kaggle - Global AI Job Market and Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025)
- **File Used**: `ai_job_dataset.csv`

---

Key Analyses

### Exploratory Data Analysis (EDA)
- Missing value treatment
- Salary distribution overview
- Country-level and job title-level salary statistics

Economic Visualization
- Pairwise plots of salary vs remote ratio and experience
- Box plots comparing salaries across experience levels
- Violin plots illustrating remote work’s effect on salary distribution

Predictive Modeling
- Random Forest Regression model to predict salary using:
  - Job title
  - Company location
  - Remote work ratio
- Model evaluation using Mean Absolute Error (MAE)

---

Economic Insights

Human Capital Theory
> Salary tends to increase with experience, validating the classical economic theory that skill and productivity command higher wages.

Digital Labor Market Dynamics
> Remote roles often offer higher salaries, reflecting a global competition for AI talent. This supports theories around globalization and wage arbitrage in digital labor markets.

Geographic Arbitrage
> Workers in lower-income countries accessing remote jobs from higher-income economies enjoy above-local wages—indicating digital opportunity channels in the global South.

---

 Repository Contents

| File / Folder           | Description |
|-------------------------|-------------|
| `ai_job_analysis.ipynb` | Main notebook with all visualizations, code, and economic interpretations |
| `plots/` (optional)     | Folder containing exported images of key visualizations |
| `requirements.txt`      | Python packages used (optional) |
| `README.md`             | Project documentation (this file) |

---

Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- Git & GitHub
- Kaggle Dataset

---

Getting Started

1. Clone the Repository

```bash
git clone https://github.com/Abdlhafidhu/ai-job-analysis.git
cd ai-job-analysis

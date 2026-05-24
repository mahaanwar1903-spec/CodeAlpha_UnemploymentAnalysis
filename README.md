# CodeAlpha Data Science Internship — Task 1 & Task 2
> End-to-end Data Science projects completed as part of the **CodeAlpha Data Science Internship**.
> Built with Python, Scikit-learn, Pandas, Matplotlib and Seaborn.

---
## Repository Structure

```
CodeAlpha_UnemploymentAnalysis/
├── unemployment_analysis.ipynb
├── Unemployment_in_India.csv
└── Unemployment_Rate_upto_11_2020.csv
```
---
---

##  Task 2 — Unemployment Analysis with Python

### Objective
Analyze Indian unemployment data, investigate the **impact of Covid-19 and the 2020 national lockdown**, identify regional/seasonal patterns, and present policy-relevant insights.

### Datasets Used
| File | Period | Rows | Special Features |
|---|---|---|---|
| `Unemployment_in_India.csv` | May 2019 – Jun 2020 | 768 | Rural / Urban split |
| `Unemployment_Rate_upto_11_2020.csv` | Jan – Oct 2020 | 267 | Geo-coordinates, North/South/East/West/NE regions |

Both datasets are merged to cover the **full 18-month timeline** (May 2019 – Oct 2020).

### Analysis Sections

**1. Data Cleaning & Preprocessing**
- Stripped whitespace, parsed dates, dropped separator rows
- Smart dataset merge by timeline cutoff (no duplicate months)

**2. Exploratory Data Analysis**
- Statistical summary of all numeric columns
- National unemployment trend over full timeline
- Top 10 highest & lowest unemployment states
- Geographic region comparison (5 regions)

**3. Covid-19 Impact Analysis**
- Pre-Covid vs. Lockdown vs. Recovery period bar chart
- State-wise unemployment spike ranking
- Monthly heatmap (State × Month) showing the lockdown shock clearly

**4. Rural vs. Urban Unemployment**
- Separate trend lines for Rural and Urban areas
- Urban areas hit significantly harder during lockdown
- Rural areas cushioned by agriculture

**5. Seasonal & Labour Participation Trends**
- Monthly seasonal baseline pattern (pre-Covid only)
- Dual-axis chart: Unemployment Rate vs Labour Participation Rate

**6. Policy Insights & Recommendations**
- 5 data-backed recommendations for economic and social policy

### Key Findings
| Metric | Value |
|---|---|
| Pre-Covid average unemployment | ~7–8% |
| Peak unemployment (Apr–May 2020) | ~23–24% |
| Lockdown spike | +~16 percentage points — nearly **3× the baseline** |
| Recovery by Oct 2020 | ~8–10% (still above pre-Covid levels) |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, merging |
| `numpy` | Numerical operations |
| `matplotlib` | Charts and visualizations |
| `seaborn` | Statistical plots and heatmaps |
| `scikit-learn` | ML models, pipelines, evaluation |

---
##  How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/CodeAlpha_IrisClassification.git
# or
git clone https://github.com/YOUR_USERNAME/CodeAlpha_UnemploymentAnalysis.git
```

### 2. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open and run the notebook
- For Task 1: just run all cells (dataset loads automatically from sklearn)
- For Task 2: make sure both CSV files are in the **same folder** as the notebook, then run all cells

---

##  Project Highlights

- End-to-end ML pipeline with cross-validation and automatic best model selection
- Covid-19 economic shock quantified with real government data
- Rural vs. Urban breakdown reveals structural differences in unemployment vulnerability
- Policy recommendations grounded in data evidence
- Clean, well-commented code with markdown explanations in every section

---

## Author

Maha Anwar
LinkedIn: [www.linkedin.com/in/maha-anwar-063b27395]
GitHub: [https://github.com/mahaanwar1903-spec]

---

*Completed as part of the CodeAlpha Data Science Internship Program*
*[codealpha.tech](https://www.codealpha.tech)*

# Fortune-500-companies-in-India---Data-Analysis-EDA-


# 🏆 Fortune 500 Companies in India — Data Analysis

This repository contains an exploratory data analysis (EDA) of the **Fortune 500 Companies in India** dataset.  
The project aims to uncover insights about India's largest companies — including their revenue, profit, debt, sectoral trends, and efficiency metrics — using **Python, Pandas, and Matplotlib/Seaborn**.

---

## 📊 Project Overview

- **Goal:** To analyze the financial and operational performance of the top 500 Indian companies listed by *Fortune India*.
- **Dataset Size:** 500 rows × ~18 columns
- **Tools Used:** Jupyter Notebook,Web Scrapping(BeautifulSoup), Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Notebook:** `Data Analysis.ipynb`

---

## 🧠 Key Insights

### 1. Top Companies by Revenue
| Rank | Company | Total Income |
|------|----------|--------------|
| 1 | Reliance Industries | 922,391 |
| 2 | Life Insurance Corporation (LIC) | 860,795 |
| 3 | Indian Oil Corporation | 780,509 |
| 4 | ONGC | 610,642 |
| 5 | State Bank of India | 594,575 |

> **Note:** Values likely in INR crores (as per Fortune India source).

### 2. Sector Highlights
- **Energy & Oil & Gas** — Dominates total income and assets.
- **Banking & Financial Services** — Strong profit margins and large asset base.
- **IT & Services** — High revenue per employee (efficiency leaders).
- **Automotive & Manufacturing** — Moderate margins but large employment share.

### 3. Ownership Patterns
- Mix of **Public Sector Undertakings (PSUs)** and **Private Conglomerates**.
- Government-owned firms dominate top revenue slots.
- Private firms often outperform on profit margins and efficiency.

### 4. Derived Metrics
- **Profit Margin (%)** — Indicates profitability variation across sectors.
- **Debt-to-Assets Ratio** — Highlights financial leverage and risk.
- **Revenue per Employee** — Proxy for operational efficiency.

---

## 📈 Visualizations

The notebook includes:
- **Correlation Matrix** of key financial metrics  
- **Sector-wise Revenue and Profit Comparisons**  
- **Ownership-based Profit Margin Distribution**  
- **Scatter Plots** for Revenue vs Employees  
- **Top 10 Lists** for Revenue, Profit, and Efficiency  

---

## 🧰 Technologies & Libraries

| Library | Purpose |
|----------|----------|
| **Pandas** | Data cleaning, aggregation, and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib / Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📁 Repository Structure

```
📂 Fortune500_India_Analysis
│
├── 📘 Data Analysis.ipynb         # Main analysis notebook
├── 📄 README.md                   # Project documentation
├── 📊 fortune500_india.csv        # Dataset (not included here)
└── 📈 outputs/                    # Plots and figures (optional)
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/Fortune500-India-Analysis.git
cd Fortune500-India-Analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

*(Create a `requirements.txt` file if not present — you can include: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`)*

### 3. Run the Jupyter Notebook
```bash
jupyter notebook "Data Analysis.ipynb"
```

---

## 📊 Future Work

- Add **interactive dashboards** using Plotly or Power BI.
- Extend analysis to **multi-year Fortune India data** for trend study.
- Build **group-level rollups** for conglomerates (e.g., Tata Group, Adani Group).
- Perform **risk analysis** using additional financial ratios.

---

## 👨‍💻 Author

**Vignesh Kalla**  
Data Analyst | Python Developer | AI & Computer Vision Enthusiast  
📧 Contact: [vigneshkalla@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/vignesh-kalla-586213329/) | [GitHub](https://github.com/VigneshKalla)

---

> **Disclaimer:**  
> This analysis is based on publicly available Fortune India 500 data.  
> Figures are interpreted for educational and analytical purposes only.
````


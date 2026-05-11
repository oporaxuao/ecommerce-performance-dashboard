# 📊 E-commerce Performance Dashboard

Full data analyst cycle: from raw data processing in Python to an interactive Business Intelligence dashboard in Looker Studio — designed for executive decision-making support.

![E-commerce Performance Dashboard](images/dashboard_final.png)

---

## 🎯 Business Objective

Analyze the sales performance of a global e-commerce operation, identifying consumption patterns by product category, gender, and geography, while monitoring critical profitability metrics. The goal is to turn raw transactional data into actionable intelligence that business teams can use without technical assistance.

---

## 🗂️ Methodology

### 1. Data Processing & Cleaning (Python)
All ETL work was performed in the Jupyter notebook:
- Date and currency type conversions
- Renaming technical fields to business-friendly labels (e.g., `state_name` → State)
- Pre-calculating metrics like Average Ticket for dashboard validation
- Null value treatment and data type standardization

### 2. BI Dashboard (Looker Studio)
The final report was designed with a focus on **UI/UX in Dark Mode** to maximize readability and highlight key indicators:

**KPIs (top-line metrics):**
- Total Revenue
- Average Ticket
- Customer Volume

**Geographic Intelligence:**
- Interactive global map with billing density heatmap using Google Maps API

**Performance Analysis:**
- Bar chart of top revenue-generating categories
- Gender segmentation with percentage breakdown

**Advanced Conditional Formatting:**
- Color gradient scale on the sales table to automatically highlight high-value transactions

**Interactivity:**
- Dynamic filters by category that update all charts in real time

---

## 📊 Results

| Metric | Value |
|---|---|
| Total Revenue Analyzed | R$ 22,025.02 |
| Average Ticket | R$ 74.41 |
| Top Categories | Beauty, Industrial, Music |

---

## 📁 Repository Structure

```
├── notebook/     # Jupyter notebook with full ETL and EDA
├── data/         # Source dataset (CSV/Excel)
├── images/       # Dashboard screenshots
└── README.md
```

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization (EDA) | Matplotlib, Seaborn |
| BI Dashboard | Looker Studio (Google) |
| Geospatial | Google Maps API |
| Environment | Jupyter Notebook |

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/oporaxuao/ecommerce-performance-dashboard.git
cd ecommerce-performance-dashboard

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook notebook/
```

---

## 👤 Author

**João Alfredo de Sousa Siqueira**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-oporaxuao-blue)](https://linkedin.com/in/oporaxuao)
[![GitHub](https://img.shields.io/badge/GitHub-oporaxuao-black)](https://github.com/oporaxuao)

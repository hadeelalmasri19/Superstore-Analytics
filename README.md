# Superstore Analytics — Graduation Project

> End-to-end Business Intelligence, forecasting, and machine-learning study of the **Superstore** retail dataset.
> University of Petra · Faculty of Information Technology · Department of Business Intelligence and Data Analysis · 2026.

![Status](https://img.shields.io/badge/status-completed-success)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)

---

## 📌 Overview

This project converts four years of raw Superstore transactions into actionable insight using a five-phase analytical pipeline:

1. **Data Cleaning** – Python / pandas (deduplication, date parsing, currency fix, label standardization, missing-value handling, outlier removal).
2. **Exploratory Data Analysis (EDA)** – Matplotlib / Seaborn bar, pie, line, scatter, correlation charts.
3. **Predictive Analytics** – Prophet 12-month sales forecast and RFM customer segmentation.
4. **Classification** – Random Forest model predicting whether each order line will be profitable.
5. **Visualization** – Power BI interactive dashboard and RapidMiner no-code workflow.

The dataset (Kaggle "Superstore") covers 9,994 raw transactions across four U.S. regions; after cleaning it contains **8,708 validated rows** and 793 unique customers.

---

## 🎯 Key Results

| Metric | Value |
|---|---|
| Records analysed | 8,708 |
| Unique customers | 793 |
| Champions identified (RFM) | 207 |
| Lost customers (RFM) | 60 |
| Best-performing category (profit) | Technology |
| Loss-making sub-categories | Tables, Bookcases, Supplies |
| Random Forest accuracy | **94.4 %** |
| Random Forest ROC-AUC | **0.984** |
| Top predictor of profitability | Discount |

---

## 🚀 How to Reproduce

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Superstore-Analytics.git
cd Superstore-Analytics
```

### 2. Create a virtual environment and install dependencies

**Windows (PowerShell)**

```powershell
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

**macOS / Linux**

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3. Launch Jupyter and run the notebooks

```bash
jupyter notebook
```

Open the notebooks in `notebooks/` and run them in numerical order (`01_` → `05_`). Each notebook is self-contained: it loads the relevant CSV, performs the analysis, and saves charts to `charts/` with meaningful filenames.

### 4. Open the Power BI dashboard

Open `dashboard/Superstore_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).

### 5. Open the RapidMiner workflow

Open the `.rmp` files in `rapidminer/` with **RapidMiner Studio**.

---

## 📊 Tools and Technologies

| Layer | Tools |
|---|---|
| Language | Python 3.10+ |
| Data wrangling | pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Forecasting | Prophet |
| Machine learning | scikit-learn (Random Forest) |
| Dashboard | Microsoft Power BI |
| No-code analytics | RapidMiner Studio |
| Notebooks | Jupyter |

---

## 📖 Read the Report

The complete graduation report is available here:

- 📄 [`Report/Superstore_Analytics_Defense_Deck.pptx`](Report/Superstore_Analytics_Defense_Deck.pptx) — preview directly in the browser.
- 📝 [`Report/Superstore_Analytics_Graduation_Report(2).docx`](Report/Superstore_Analytics_Graduation_Report(2).docx) — Word document (download to view).

The end-to-end workflow is illustrated in **Figure 3.1** of the report.

---

## 👥 Authors

- **Hamzeh Alhindawi**
- **Hadeel Almasri**

## 🎓 Supervisor

- **Dr. Ayman Mansour** — Department of Business Intelligence and Data Analysis, University of Petra.

---

## 🙏 Acknowledgments

We thank Dr. Ayman Mansour for his guidance throughout the project, the academic staff of the Department of Business Intelligence and Data Analysis, and the lab technicians who supported every stage of the work.

---

# 📊 Berlin Airbnb Market Health Report (Sept 2025)

### 🏢 Project Overview
This project provides a comprehensive analysis of the Berlin short-term rental market using data finalized on **September 23, 2025**. It simulates a professional consultancy report for a real estate investment firm planning a market entry for the 2026 season.

The analysis addresses complex German market dynamics, specifically the **"Utility Gap"** (Kaltmiete vs. Warmmiete) and district-level ROI potential.

Data Source: https://insideairbnb.com/get-the-data/ (September 2025)

---

### 🛠️ Tech Stack & Methodology
* **Data Engineering:** Python, Pandas, NumPy
* **Database Architecture:** SQL (SQLite), CTEs, Window Functions
* **Data Visualization:** Matplotlib, Seaborn
* **Version Control:** Git/GitHub

---

### 📁 Repository Structure
* `/data`: Raw `listings.csv` source data.
* `/notebooks`: [Berlin Airbnb Analysis](./berlin-airbnb-analysis-sept-2025.ipynb) - Full Python/SQL cleaning and EDA.
* `/database`: `berlin_market.db` - The compiled SQLite database for external querying.
* `/scripts`: Automated reporting functions for stakeholder insights.

---

### 🚀 Key Project Phases

#### **Phase 1: Data Preprocessing & Feature Engineering**
* **Currency Normalization:** Used RegEx to convert price strings (e.g., "$120.00") into floats for mathematical modeling.
* **The Utility Gap:** Engineered `kaltmiete` (Base Rent) and `utilities` columns (simulated at 20% overhead) to reflect the true cost of living in the current energy climate.

#### **Phase 2: SQL Data Modeling**
* Migrated the cleaned dataset into a **SQLite backend**.
* Implemented **Window Functions (`RANK() OVER`)** to create a "District Power Ranking" comparing price vs. annual availability.
* Utilized **CTEs (Common Table Expressions)** to maintain clean, readable, and performant SQL queries.

#### **Phase 3: Automation & Reporting**
* Developed a Python reporting engine (`generate_market_report`) to extract live insights from the database.
* Visualized neighborhood price distributions to identify premium investment zones.



---

### 📈 Major Findings (Sept 2025)
1.  **Supply Crunch:** Tourist hubs like **Mitte** and **Friedrichshain-Kreuzberg** show stabilizing supply post-summer, suggesting a premium on mid-term corporate stays.
2.  **Price Inflation:** Average "Warm" prices have shifted significantly, driven by the utility overhead modeled in this report.
3.  **Investment Recommendation:** Identified **Neukölln** as a high-growth zone with a significant demand-to-price ratio for Q1 2026.

---

### 📋 How to Run
1.  **Clone the repository:** `git clone https://github.com/Stanitaa/Berlin-Airbnb-Market-Analysis.git`
2.  **Install dependencies:** `pip install pandas seaborn sqlite3 matplotlib`
3.  **Run the Analysis:** Open `notebooks/berlin-airbnb-analysis-sept-2025.ipynb` in Jupyter or Kaggle.

---

### 📁 Main Analysis
View the full interactive analysis here: [Berlin Airbnb Notebook](https://github.com/Stanitaa/Berlin-Airbnb-Market-Analysis/blob/main/berlin-airbnb-analysis-sept-2025.ipynb)

---

### 👨‍💻 Author
**Stanitaa** *Data Analysis | SQL | Python Portfolio 2025* 

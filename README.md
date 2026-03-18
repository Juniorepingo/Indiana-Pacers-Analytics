# 🏀 Indiana Pacers Analytics Pipeline & Shot Probability Model

End-to-end NBA analytics pipeline using play-by-play data, shot logs, lineup models, and machine learning.  
**Seasons Analyzed:** 2023–24 & 2024–25

---

## 📊 Overview
This multi-season analytics project evaluates the Indiana Pacers across their two deepest playoff runs of the last decade.  
The pipeline covers:

- Lineup performance analysis  
- Rotation optimization  
- Shot probability modeling (Logistic Regression + Gradient Boosting)  
- Expected FG% (xFG%) estimation  
- Opponent scouting reports  
- Cross-season comparison (2023–24 vs 2024–25)

**Tools Used:** Python, nba_api, pandas, SQL, scikit-learn, Tableau, Jupyter Notebook

---

## 🏗️ Folder Structure

| Folder | Purpose |
|--------|---------|
| **data/** | Raw, interim, and processed datasets for 2023–24 & 2024–25 |
| **src/** | Ingestion, cleaning, feature engineering, and model scripts |
| **notebooks/** | EDA, modeling, visualization, and cross-season notebooks |
| **dashboards/** | Tableau dashboards (shots, lineups, scouting) |
| **sql/** | SQL schemas and analytical queries |
| **docs/** | Reports, summaries, and documentation |

---

## 📥 Data Sources

- **nba_api** — official NBA stats endpoints  

---

## 🚀 Getting Started

### Install Dependencies
```bash
pip install -r requirements.txt

# ⚽ International Football Match Analysis (1872–2024)

This data analytics project explores trends and patterns in international football match results from **1872 to 2024**, including FIFA World Cups and friendly matches. Using **Python and pandas**, we answer five key questions about team performance, scoring patterns, and tournament impact.

---

## 📊 Dataset Overview

- **Source**: [Kaggle – International Football Results](https://www.kaggle.com/)
- **Entries**: 45,000+ matches
- **Features**:
  - Date, Home/Away Teams, Home/Away Scores, Tournament Type
  - City, Country, Neutral Ground Indicator

---

## 🎯 Objectives Answered

1. **What is the average number of goals scored by the home team?**  
   → `1.74` goals per match

2. **What is the average number of goals scored by the away team?**  
   → `1.18` goals per match

3. **Which country recorded the highest overall home goals?**  
   → 🇺🇸 **United States**

4. **What are the top 3 most frequent tournament types?**  
   → Friendly, FIFA World Cup Qualification, UEFA Euro Qualification

5. **Which country scored the most total goals in FIFA World Cups?**  
   → 🇧🇷 **Brazil**

---

## 🧠 Methods Used

- **pandas** for data loading, filtering, grouping, and aggregation
- `groupby`, `mean()`, `value_counts()`, `idxmax()` for analysis
- Creation of derived metrics (e.g., total score for World Cup matches)

---

## 📁 Project Structure

- `results.csv` – Raw dataset
- `Football_Analysis.ipynb` – Main notebook with all code and answers
- `README.md` – Project summary and context

---

## 🚀 How to Run

1. Clone this repo or download the notebook
2. Make sure you have Python + pandas installed:
   ```bash
   pip install pandas

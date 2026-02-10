# ⚽ EURO 2024 Shot Analysis — From Match-Level Insights to Tournament Trends

## 📌 Project Overview

This project explores shooting patterns and attacking performance during **UEFA EURO 2024** using open event data from StatsBomb.
The analysis progresses from **single-match spatial analysis** to **tournament-level trend evaluation**, combining data science techniques with football analytics methodology.

The goal of this project is to demonstrate how data analysis, visualization, and feature engineering can be applied to sports analytics — particularly in evaluating shot quality, attacking structure, and team performance profiles.

---

## 🎯 Objectives

* Analyze shot locations and expected goals (xG) using real event data
* Build spatial visualizations commonly used in football analytics
* Compare attacking performance between teams
* Identify tournament-wide attacking trends
* Translate analytical outputs into interpretable football insights

---

## 📊 Dataset

* Source: **StatsBomb Open Data**
* Competition: UEFA EURO 2024
* Data Type: Event-level match data
* Key Variables Used:

  * Shot location (x, y coordinates)
  * Shot outcome
  * Expected Goals (xG)
  * Team and player metadata

---

## 🧰 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* StatsBombPy
* Google Colab

---

# 🔵 Match-Level Shot Analysis

### Data Preparation

* Extracted shot events from match event data
* Engineered spatial features:

  * x, y coordinates
  * goal indicator (is_goal)

### Visualization

Created a **Shot Map** showing:

* Shot location
* Shot quality (marker size based on xG)
* Goal vs non-goal outcomes

### Insight

This step reveals attacking structure, preferred shooting zones, and finishing efficiency in a single match context.

---

# 🟣 Match Comparison Analysis

### Method

To compare both teams in one visual space:

* Mirrored shot coordinates for the opposing team
* Displayed both teams’ shots on a single pitch

### Why It Matters

This approach allows:

* Direct visual comparison of attacking volume
* Understanding territorial dominance
* Evaluating shot quality differences

### Analytical Value

This mirrors real workflows used in scouting and tactical analysis.

---

# 🟢 Tournament Trends Analysis (EURO 2024)

### Objective

Move from match-level insights to **competition-level patterns**.

### Data Processing

* Aggregated shots from all matches
* Built team-level summary metrics:

  * Total Shots
  * Total xG
  * Goals
  * Average xG per Shot (Shot Quality)

### Key Visualization

Combined bar and line chart showing:

* Total xG (attacking volume)
* Average xG (chance quality)

### Key Insights

* Some teams generated high attacking volume but lower shot quality.
* Others produced fewer shots but with higher expected goal value.
* Different attacking philosophies emerge when comparing volume vs efficiency.

---

## 📈 Analytical Framework

This project demonstrates a structured workflow:

```
Match Analysis → Comparative Analysis → Tournament Trends
```

This layered approach reflects real-world sports analytics pipelines where analysts begin with micro-level analysis before scaling toward macro insights.

---

## 🧠 Key Takeaways

* Expected goals (xG) can quantify both attacking productivity and decision-making quality.
* Spatial visualization enhances interpretability of event data.
* Combining aggregate statistics with visual analysis provides deeper tactical insight.

---

## 🚀 Future Extensions (Planned)

* Player-level shooting profiles
* Shot density heatmaps
* Team attacking style clustering
* Cross-competition comparison

---

## 👤 Author

Rizno Fadhil
* Statistics & Data Science Graduate — IPB University
* Focus Areas: Data Science, Performance Analytics, Sports Analytics

* Portfolio: [https://bit.ly/RiznoFadhil_DataPortfolio](https://bit.ly/RiznoFadhil_DataPortfolio)
* LinkedIn: [http://www.linkedin.com/in/rizno-fadhil](http://www.linkedin.com/in/rizno-fadhil)

# ⚽ EURO 2024 Shot Analysis — From Match-Level Insights to Tournament Trends

## 📌 Project Overview

This project analyzes attacking behaviour and shot quality during **UEFA EURO 2024** using open event data from StatsBomb.

The workflow progresses from **single-match spatial analysis** — focusing on the Spain vs Germany Quarterfinal — toward **tournament-level attacking trends**, demonstrating how data science methods can be applied within a football analytics context.

Rather than only counting shots or goals, this project evaluates:

* spatial shot distribution
* expected goals (xG)
* attacking efficiency
* team tactical profiles

The objective is to translate raw event data into **interpretable football insights**, similar to real analyst workflows used in performance analysis and scouting environments.

---

## 🎯 Objectives

* Analyze shot locations and expected goals (xG)
* Build football-style spatial visualizations
* Compare attacking structures between teams
* Evaluate tournament-wide attacking philosophies
* Demonstrate an end-to-end sports analytics workflow

---

## 📊 Dataset

**Source:** StatsBomb Open Data
**Competition:** UEFA EURO 2024
**Data Type:** Event-level match data

Key variables used:

* Shot coordinates (x, y)
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

# 🔵 Match-Level Analysis — Spain Shot Map

## Method

* Extracted shot events from match data
* Engineered spatial features:

  * pitch coordinates (x, y)
  * goal indicator (`is_goal`)
* Built custom StatsBomb pitch visualization

Circle size represents shot quality (xG).

## Analytical Insight

The shot map highlights how Spain structured their attacking phases:

* High concentration of shots inside the penalty area
* Preference for central attacking zones
* Efficient chance creation despite lower shot volume

Spatial visualization reveals attacking intent that traditional statistics alone cannot capture.

---

# 🟣 Comparative Match Analysis — Spain vs Germany (Quarterfinal)

## Method

To compare both teams in a single visual frame:

* Germany’s coordinates were mirrored
* Both teams plotted on the same pitch
* Summary metrics calculated:

  * total shots
  * goals
  * total xG

## Insight

Although Germany produced **more total shots**, Spain generated more dangerous opportunities:

* Spain’s attempts were concentrated near goal
* Germany relied more on long-distance shots
* Spain scored **2 goals from 1.53 xG**, while Germany scored **1 from 1.63 xG**

👉 What this means:

Spain demonstrated a **high-value attacking structure**, prioritizing shot quality over volume — a pattern that later appears in tournament-level trends.

---

# 🟢 Tournament Trends Analysis — EURO 2024

## Analytical Pipeline

1. Collected event data from all matches
2. Filtered shot events
3. Built team-level aggregates:

* Total Shots (Volume)
* Goals
* Total xG (Production)
* Average xG per Shot (Shot Quality)

---

## 📈 Key Visualizations

* Top Teams by Total Shots
![Total shots](insight_images/top_total_shots.png)
* Top Teams by Total xG
![Total xG](insight_images/top_total_xG.png)
* Shot Quality Ranking (Avg xG)
![Average xG](insight_images/top_avg_xG.png)
* Combined Chart: Total xG vs Average xG
![Total vs average xG](insight_images/total_vs_avg_xG.png)

These visualizations allow comparison between **attacking volume** and **chance quality**.

---

# 🧠 Some Interesting Interpretation

## 🇪🇸 Spain — High-Volume, Low-Efficiency Attack

Spain recorded:

* **123 total shots** (highest in tournament)
* **10.57 total xG**
* **0.086 average xG per shot**

Despite sustained attacking pressure, Spain generated relatively lower-quality chances compared to elite teams.

👉 Tactical interpretation:

Spain relied on **continuous possession and repeated attempts**, rather than elite shot selection.

---

## Portugal — Elite Balanced Attack

Portugal stands out as the tournament outlier:

* **14.71 total xG** (highest)
* **0.154 average xG** (highest)
* Top 5 in total shots

Portugal combined:

* high attacking volume
* elite shot quality

This indicates optimal shot selection and efficient attacking structure.

---

## France vs Germany — Similar Volume, Different Quality

* France: 101 shots → 12.11 xG
* Germany: 95 shots → 8.72 xG

Although volume is similar, France generated significantly more high-value chances.

👉 Suggests stronger positional play or shot selection efficiency.

---

## Netherlands & Turkey — Volume Without Elite Output

Both teams produced high shot counts:

* Netherlands: 83 shots
* Turkey: 72 shots

However, lower average xG indicates many attempts came from sub-optimal shooting locations.

---

## Switzerland — Low Volume, High Efficiency

Switzerland produced only:

* 62 shots
  but achieved:

* 8.48 total xG

* 0.137 average xG (Top 4)

Compared to Spain:

* Spain generated twice as many shots
* Switzerland produced higher-quality opportunities

👉 Indicates a **selective attacking approach**, focusing on elite chances.

---

# 📈 Analytical Framework

This project follows a layered analyst workflow:

```
Match-Level Spatial Analysis
        ↓
Team Comparison
        ↓
Tournament Trend Evaluation
```

The structure reflects real-world sports analytics pipelines where micro-level observations inform macro-level conclusions.

---

# 🧠 Key Takeaways

* Attacking strength is not defined by volume alone.
* xG helps separate **shot quantity** from **shot quality**.
* Spatial analysis provides tactical context beyond raw statistics.
* Different attacking identities emerge across teams:

  * Volume-driven (Spain)
  * Elite-balanced (Portugal)
  * Selective efficiency (Switzerland)

---

# 🚀 Future Extensions

Planned research expansions:

* Player-level shooting profiles
* Shot density heatmaps
* Team attacking style clustering
* Cross-competition comparison
* Basketball analytics adaptation (future project)

---

# 👤 Author

**Rizno Fadhil**
Statistics & Data Science Graduate — IPB University

Focus Areas:

* Data Science
* Sports Analytics
* Performance Analytics

Portfolio: [https://bit.ly/RiznoFadhil_DataPortfolio](https://bit.ly/RiznoFadhil_DataPortfolio)
LinkedIn: [http://www.linkedin.com/in/rizno-fadhil](http://www.linkedin.com/in/rizno-fadhil)

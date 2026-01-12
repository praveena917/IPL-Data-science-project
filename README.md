# 🏏 IPL Data Analysis (Exploratory Data Analysis)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on **Indian Premier League (IPL)** data to uncover insights related to **batting performance, strike rates, stadium-wise high-scoring matches, player consistency across seasons, and match outcomes**.

The analysis uses visualizations to highlight trends in player dominance, venue impact, and overall match competitiveness in the IPL.

---

## 🎯 Objectives

* Identify **stadiums with the highest number of high-scoring matches**
* Analyze the **Top 20 highest run-scoring batters** in IPL history
* Study the **Top 10 players with the highest strike rates**
* Compare **season-wise average runs per match** of MS Dhoni and Virat Kohli
* Understand **win vs loss probability distribution**

---

## 📂 Dataset Information

* **Source:** IPL match-by-match and ball-by-ball datasets
* **Format:** CSV files
* **Scope:** Multiple IPL seasons

### Key Columns Used

* `batter` – Name of the batter
* `runs` – Runs scored
* `strike_rate` – Batting strike rate
* `venue` – Match stadium
* `season` – IPL season
* `match_result` – Win/Loss outcome

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Jupyter Notebook**

### Libraries

* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Imported IPL datasets
* Inspected data structure and columns

### 2️⃣ Data Cleaning

* Handled missing and inconsistent values
* Converted numerical columns to appropriate data types
* Filtered relevant seasons and players

### 3️⃣ Exploratory Data Analysis (EDA)

* Stadium-wise analysis of high-scoring matches
* Batter-wise total runs analysis
* Strike rate comparison of explosive batters
* Season-wise performance comparison
* Match result probability analysis

### 4️⃣ Data Visualization

* Bar charts for batter and strike rate analysis
* Line plots for season-wise trends
* Pie chart for win vs loss probability
* Waffle chart for stadium analysis

---

## 📊 Key Insights

### 1️⃣ Top 20 Batters by Total Runs
<img width="2970" height="1465" alt="Top 20 batters" src="https://github.com/user-attachments/assets/9cbe7d64-4fec-4748-8d02-a76613f0db9e" />


**Insight:**

* **Virat Kohli** leads the chart, highlighting his consistency and longevity in the IPL.
* Players like **Shikhar Dhawan, Rohit Sharma, David Warner,SK Raina and MS Dhoni** consistently rank high, proving their long-term impact on the tournament.

---

### 2️⃣ Top 10 Players by Strike Rate
<img width="2970" height="1466" alt="Top 10 strike rate of players" src="https://github.com/user-attachments/assets/3371de8c-930b-4b3e-b3dc-5ed2c8b1370e" />

**Insight:**

* **Andre Russell** tops the list, showcasing his explosive batting style.
* Power-hitters like **Sunil Narine, Glenn Maxwell, Virender Sehwag, and AB de Villiers** dominate this list, emphasizing impact over volume of runs.

---

### 3️⃣ Win vs Loss Probability Distribution
<img width="1713" height="1278" alt="probability_win vs probability_loss" src="https://github.com/user-attachments/assets/773247cc-5e65-443a-a269-c8237f1cbd99" />

**Insight:**
The probability distribution shows an almost balanced outcome:

* **Win Probability:** ~51%
* **Loss Probability:** ~49%

This highlights the **highly competitive nature of the IPL**, where outcomes are often decided by small margins.

---

### 4️⃣ Season-wise Average Runs per Match: MS Dhoni vs Virat Kohli
<img width="3570" height="1766" alt="Season-wise Average Runs per Match: MS Dhoni vs Virat Kohli" src="https://github.com/user-attachments/assets/0adc619a-662c-4547-b55d-f326c694c3df" />

**Insight:**

* **Virat Kohli** shows higher peaks, especially around 2016 and recent seasons, reflecting his dominance as a top-order batter.
* **MS Dhoni** demonstrates remarkable consistency across seasons, with steady contributions despite batting lower in the order in later years.

---

### 5️⃣ Top 20 High-Scoring Matches by Stadium (Waffle Chart)
<img width="2669" height="1161" alt="Top 20 High-Scoring Matches by Stadium" src="https://github.com/user-attachments/assets/dc3eb927-2b93-4c25-8eb0-5eb547f39505" />

**Insight:**
The waffle chart visualization highlights stadium-wise distribution of high-scoring matches. Venues such as **M Chinnaswamy Stadium** and **Eden Gardens** appear multiple times, indicating batting-friendly conditions, shorter boundaries, and pitches that often favor high totals.

---

## ✅ Conclusion

This IPL EDA project highlights how **player consistency, strike rate, venue characteristics, and season trends** shape match outcomes.

The insights can be useful for:

* Team strategy and player selection
* Match prediction models
* Cricket analysts and fans seeking deeper understanding of IPL dynamics

---

## 🚀 Future Enhancements

* Team-wise performance analysis
* Toss impact on match results
* Player performance against specific teams
* Predictive modeling using machine learning

---

📌 *This project demonstrates how data analysis and visualization can turn raw cricket data into meaningful insights.*

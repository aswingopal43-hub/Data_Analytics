# FIFA World Cup 2022 – Tournament & Team-Level Analysis

## Overview
This project presents an **Exploratory Data Analysis (EDA)** of the FIFA World Cup 2022, focusing on how teams performed in terms of attacking output, defensive efficiency, and discipline. The analysis transforms raw player and team data into clear, easy-to-understand insights using Python and data visualization.

The main goal is to explain **what influenced team performance** during the tournament in a structured and data-driven way.

---

## Dataset Description
The dataset contains player-level and team-level statistics from the FIFA World Cup 2022, including:
- Goals and assists  
- Minutes played and matches played  
- Shots on target and Goals_aganist  
- Defensive actions and clean sheets  
- Yellow and red cards  

Data cleaning and preprocessing were carried out to ensure accuracy and consistency before analysis.

---

## Project Structure

### 1. Data Loading & Preprocessing
- Dataset inspection (rows, columns, data types)  
- Missing value checks  
- Creation of derived metrics:
  - Goal contributions  
  - Goal conversion rate  
  - Defensive efficiency indicators  

---

### 2. Exploratory Data Analysis (EDA)

#### Tournament-Level Analysis
This section provides a high-level overview of the tournament:
- Player age distribution and squad composition  
- Position-wise player distribution  
- Playing time and workload patterns  
- Overall attacking, defensive, and disciplinary trends  
- Correlation analysis between key performance metrics  

This analysis sets the overall context before moving to team-level comparisons.

---

#### Team-Level Analysis
This section evaluates team performance by aggregating player data:
- Top-performing teams based on goal contributions  
- Offensive efficiency (goals vs shots on target)  
- Defensive efficiency (defensive actions vs clean sheets)  
- Team discipline using total, yellow, and red cards  

These insights highlight differences in playing style, efficiency, and tactical balance across teams.

---

## Key Findings
- Tournament success depended on **balance**, not dominance in a single metric  
- Efficient finishing often mattered more than high shot volume  
- Defensive organization was more important than defensive workload  
- High defensive activity did not always result in clean sheets  
- Yellow cards reflected aggressive tactics, while red cards were rare  
- Teams combining efficiency, structure, and discipline performed most consistently  

---

## Limitations
- Advanced metrics such as expected goals (xG) were limited or inaccurate  
- Team-level aggregation may hide match-specific context  
- Tactical decisions and in-game situations are not fully captured by statistics  

---

## Overall Conclusion
The analysis shows that successful teams combined:
- **Efficient attacking**
- **Organized defending**
- **Controlled physical play**

Teams that converted chances well, defended with structure rather than volume, and managed discipline effectively were best positioned to achieve consistent results throughout the tournament.

---

## Tools Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Plotly  
- Jupyter Notebook  

---

## Purpose of the Project
This project is designed for **learning, football analytics exploration, and portfolio demonstration**.  
It shows how Python and data visualization can be used to analyze real-world football data and present insights in a clear and simple way.

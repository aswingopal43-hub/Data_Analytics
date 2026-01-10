# FIFA World Cup 2022 – Tournament & Team-Level Analysis

## Project Overview
The FIFA World Cup 2022 is one of the biggest international football tournaments, featuring the world’s top national teams and players.  
This project uses **Exploratory Data Analysis (EDA)** to understand overall tournament trends and compare team-level performances using real match data.

The aim is to explain **how teams performed**, what patterns emerged across the tournament, and what factors were linked with success — all in a clear and easy-to-understand way.

---

## Dataset Information
- **Source:** FBref (football statistics platform)
- **Records:** 679 players  
- **Features:** ~18 columns  

The dataset includes:
- Player details (age, position, team)
- Playing time (matches played, minutes)
- Attacking stats (goals, assists, shots, shots on target)
- Defensive stats (tackles, interceptions, blocks)
- Discipline (yellow and red cards)
- Goalkeeping stats (goals conceded, saves, clean sheets)

---

## Project Objectives

### Tournament-Level Analysis
- Provide a high-level view of the tournament
- Analyze squad composition, age distribution, positions, and playing time
- Identify overall attacking, defensive, and discipline trends
- Highlight standout performers

### Team-Level Analysis
- Evaluate team attacking output and efficiency
- Assess defensive effort and defensive success
- Compare discipline and physical playing styles
- Identify top-performing and well-balanced teams

---

## Project Structure

### 1. Data Loading & Initial Overview
- Checked dataset size and structure
- Reviewed data types and missing values
- Examined summary statistics
- Viewed sample rows for familiarity

---

### 2. Data Preprocessing
To ensure clean and reliable analysis:
- Removed duplicates and handled missing values
- Standardized column names
- Cleaned categorical data (player names, positions, team names)
- Created derived metrics such as:
  - Shot accuracy
  - Goal conversion rate
  - Goal contribution
  - Defensive actions
- Applied safeguards to avoid division-by-zero errors

---

### 3. Team-Level Aggregation
Player-level data was aggregated to create team-level metrics, including:
- Total goals, assists, and goal contributions
- Shots and shots on target
- Defensive actions and goals conceded
- Total cards
- Goalkeeping stats (saves and clean sheets from goalkeepers only)

This provides a complete view of each team’s overall performance.

---

## Exploratory Data Analysis (EDA)

### Tournament Overview
- Player age and position distribution
- Playing time and workload patterns
- Overall attacking, defensive, and disciplinary trends
- Correlation heatmap between key metrics (goals, assists, minutes, clean sheets, cards, etc.)

### Team-Level Analysis
- Top teams by attacking output
- Offensive efficiency (goals vs shots on target)
- Defensive efficiency (defensive actions vs clean sheets)
- Discipline analysis using yellow and red cards

---

## Key Insights
- Success was driven by **balance**, not just high activity
- Efficient finishing mattered more than taking many shots
- Defensive organization was more important than defensive workload
- Teams with fewer defensive actions could still keep clean sheets
- Yellow cards often reflected aggressive tactics, not poor discipline
- Red cards were rare across the tournament
- Teams like **France, Argentina, England, and Morocco** showed strong overall balance

---

## Limitations
- Team-level aggregation can hide match-by-match details
- Match context (opponent strength, game situation) is not included
- Defensive actions and cards measure activity, not quality
- **Expected Goals (xG) was not used** due to inconsistent data
- The analysis is descriptive, not predictive

---

## Conclusion
This project shows that World Cup success depends on:
- **Efficient attacking**
- **Organized defending**
- **Controlled physical play**

Teams that converted chances well, defended with structure rather than volume, and maintained discipline performed more consistently.  
The analysis provides a clear, data-driven view of how the FIFA World Cup 2022 unfolded and offers a strong foundation for future football analytics work.

---

## Tools Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Plotly  
- Jupyter Notebook  

---

## Purpose
This project is created for **learning, football analytics exploration, and portfolio demonstration**.  
It shows how Python and data visualization can be used to analyze real football data and present insights in a simple and meaningful way.

# FIFA World Cup Data Analysis & Match Outcome Predictions

## Project Title
**Predicting Match Outcomes for the Next FIFA World Cup Using Historical Data and Machine Learning**

---

## Overview
This project analyzes historical FIFA World Cup tournaments and team performance data to predict the outcomes of matches for the upcoming World Cup. It combines **data engineering, exploratory analysis, feature engineering, machine learning, and tournament simulation** to predict the next World Cup champion.

The project is implemented in **Python** using **Jupyter Notebook** and demonstrates the complete **data science workflow**: from raw datasets to predictive modeling and visualizations.

---


---

## Data Sources
- **Historical World Cup Matches**: Kaggle dataset (`world_cup_matches.csv`)  
- **FIFA Rankings**: Official FIFA rankings CSV/API (`fifa_rankings.csv`)  
- **World Cup Winners**: Kaggle historical winners dataset (`world_cup_winners.csv`)  


---

## Key Techniques

### 1. Data Engineering
- Merge multiple datasets:
  - Match results
  - FIFA team rankings
  - Player stats (optional)
- Clean and transform columns (dates, scores, xG values)
- Generate dynamic team statistics (last 5 match results, xG differences)

### 2. Exploratory Data Analysis (EDA)
- Analyze factors affecting match outcomes:
  - Team form trends
  - Home vs away performance
  - Average player age, goals, and xG
- Visualize historical winners and top scorers

### 3. Feature Engineering
- **Team Strength**: Based on FIFA ranking points
- **Recent Performance**: Last 5 match wins
- **Goal Metrics**: Average expected goals (xG) difference
- **Dynamic Features**: Updated from historical matches for realistic simulations

### 4. Predictive Modeling
- **Problem Type**: Classification (Win vs Loss/Draw)  
- **Algorithms Used**:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - CatBoost
  - Neural Networks
- **Feature Scaling** applied to numerical variables
- **Training** on historical match data and evaluation using accuracy metrics

### 5. Tournament Simulation
- **Group Stage**:
  - Simulates all matches in round-robin format
  - Determines top 2 teams per group
- **Knockout Stage**:
  - Round of 16 → Quarterfinals → Semifinals → Final
  - Predicts winners using dynamic last-5 match form and xG differences
- **Predicted Champion**: Outputs the most likely winner

### 6. Visualizations
- Heatmaps of team strengths
- Knockout bracket visualization
- Dynamic node highlighting for predicted champion
- Feature importance charts for model interpretation

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/stephen0111/FIFAWCgit




# NBA Trends Analysis: Knicks vs Nets (2010 & 2014)
This project explores NBA game data to compare the performance of the `New York Knicks` and the `Brooklyn Nets` in the `2010` and `2014` seasons.
The analysis includes data exploration, visualization, statistical testing, and correlation analysis.

---

## 📊 Dataset
The dataset contains NBA game-level data with the following key variables:
- `game_id`: Unique identifier for each game
- `year_id`: Season year
- `fran_id`: Franchise name (e.g., Knicks, Nets)
- `opp_fran`: Opponent franchise name
- `game_location`: Home (H) or Away (A)
- `is_playoffs`: Indicator for playoff games
- `pts`: Team points scored
- `opp_pts`: Opponent points scored
- `game_result`: Win (W) or Loss (L)
- `forecast`: Win probability forecasted by FiveThirtyEight
- `point_diff`: Point difference (team points – opponent points)

---

## 🔎 Exploratory Data Analysis
Example visualization:  

<img src="images/bmi_vs_charges.png" alt="Scatterplot BMI vs Charges" width="600"/>

- **Knicks vs Nets (2010 vs 2014):** Histograms and boxplots compare scoring distributions across seasons.
- **Home vs Away:** A chi-square test was used to check if game results are independent of location.
- **Forecast vs Outcome:** Scatterplots and correlations were used to evaluate how well FiveThirtyEight’s forecasts aligned with actual point differences.

---

## 📈 Statistical Analysis
- **Chi-Square Test:** Tested independence between `game_result` and `game_location`.
- **Correlation:** Pearson correlation between `forecast` and `point_diff` shows forecasts are positively correlated with actual results.
- **Covariance Matrix:** Quantified joint variability of forecasts and point differences.

---

## 🛠 Tools & Libraries
- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`)
- Jupyter Notebook

---

## 📌 Key Learnings
- How to explore categorical and numerical relationships in sports data.
- Using contingency tables and the chi-square test to analyze categorical variables.
- Evaluating predictive accuracy with correlation analysis.
- Building clear, visual comparisons across seasons and teams.

---

## 🚀 Next Steps
- Extend analysis to other teams and seasons.
- Explore playoff vs regular season differences.
- Build an interactive dashboard (e.g., Streamlit) for dynamic comparisons.

---


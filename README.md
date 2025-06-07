# IPL Analysis Dashboard (Power BI)

This repository contains an **IPL Analysis Dashboard** built using **Power BI**, providing interactive insights into the **Indian Premier League (IPL)** for the selected season. The dashboard visually represents team performances, player statistics, match results, and other crucial IPL metrics.

##  Features

- ** Title Winner**: Displays the champion team of the season.
- ** Orange Cap**: Highlights the highest run scorer.
- ** Purple Cap**: Showcases the leading wicket-taker.
- ** Tournament Statistics**:
  - Total **6's** and **4's** hit across all matches.
- ** Batting Statistics**:
  - Select a batsman to view **total runs, sixes, fours, and strike rate**.
- ** Bowling Statistics**:
  - Select a bowler to check **wickets, economy, average, and bowling strike rate**.
- ** Matches Analysis**:
  - **Matches Win by Venue**: Venue-wise win breakdown based on match results.
  - **Total Wins by a Team**: Total number of wins per team in the season.
  - **Matches Win Based on Toss Decision**: Visualizes the impact of winning the toss on match outcomes.
  - **Matches Win by Result Type**: Analyzes wins by **wickets, runs, or Super Over**.

## Key Questions Answered by the Dashboard

### General Team Performance
1. Which team won the IPL in the selected season?
2. How many matches did each team win?
3. Which venues had the most wins by wickets, runs, or Super Over?

### Player Performance
4. Who won the **Orange Cap** (most runs in the season)?
5. Who won the **Purple Cap** (most wickets in the season)?
6. What are the total runs, sixes, fours, and strike rate of a selected batsman?
7. What are the wickets, economy rate, average, and bowling strike rate of a selected bowler?

### Match Insights
8. How many total **6's** and **4's** were hit in the tournament?
9. What was the effect of **toss decisions** on match outcomes?
10. How did teams win their matches (by wickets, runs, or Super Over)?

### Data Modeling
11) Relationship between all tables
![Table_Model_View](https://github.com/muniasamyk/Data-Analysis-Dashboard-IPL-/blob/main/Model_View)

## Screenshot

![IPL Analysis Dashboard](https://github.com/muniasamyk/Data-Analysis-Dashboard-IPL-/blob/main/Screenshot%202025-02-25%20152939.png)

## Technology Used

- **Power BI** (for data visualization and interactive reports)
- **Excel / SQL** (for data storage and preprocessing)

## How to Use

1. **Download the Power BI file (`.pbix`).**
2. **Open it in Power BI Desktop.**
3. **Navigate through the interactive dashboard to analyze IPL insights.**
4. **Filter by season, players, teams, and venues to explore different statistics.**

## Future Enhancements

- **Real-time IPL data integration** for live updates.
- **Player comparison charts** for deeper analysis.
- **Predictive analytics** to forecast match results.

  # IPL Analytics & Prediction 

This repository provides robust analytics and machine learning-based prediction tools for IPL (Indian Premier League) cricket matches. It includes code and data for:
- Season-wise Orange Cap (most runs) and Purple Cap (most wickets) predictions
- Match and cup winner predictions using historical data and machine learning models
- Comprehensive data handling for match-level and ball-by-ball datasets

## Features

- **Data Integration:** Seamlessly merges match-level and ball-by-ball data for deep analysis.
- **Award Predictions:** Calculates likely Orange Cap and Purple Cap winners for any season.
- **Match/Cup Winner Predictions:** Predicts outcomes for upcoming matches and identifies the team most likely to win the IPL cup.
- **Fully Extensible:** Designed to be easily integrated into dashboards or web apps (e.g., Streamlit, Flask).
- **Scikit-learn Powered:** Uses Random Forest and other scikit-learn models for classification and regression.

## Project 

https://github.com/muniasamyk/Data_Analysis_IPL_Project/blob/main/IPL_Data_Prediction.ipynb

## Getting Started

1. **Prepare Data Files**  
   - Place your `ipl_matches.csv` and `ipl_players.csv` files in the root directory.
   - Ensure `ipl_matches.csv` has columns like `id`, `season`, `team1`, `team2`, `winning_team`, etc.
   - Ensure `ipl_players.csv` has columns like `id` (match id), `batter`, `bowler`, `batsman_run`, `iswicket_delivery`, `player_out`, etc.

## Example Outputs

- Likely Orange Cap (most runs, latest season): _Player Name_ (_Runs_)
- Likely Purple Cap (most wickets, latest season): _Player Name_ (_Wickets_)
- Predicted winner for MI vs CSK: _Team Name_
- Likely IPL Cup Winner: _Team Name_ (Total Projected Wins: _N_)

## Customization

- Add more features to the ML model by engineering new columns (e.g., player form, head-to-head stats).
- Integrate with web dashboards using Streamlit or Flask.
- Update `upcoming_match_details` in the script to predict new matches.

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements or bug fixes.

## License

This project is licensed under the MIT License.

---

> **Disclaimer:** This tool is for educational and analytical purposes. Predictions are based on historical data and machine learning models; actual match results may differ.




👨‍💻 Developed by **Muniasamy K**

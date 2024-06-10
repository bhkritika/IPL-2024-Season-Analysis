# IPL 2024 Season Analysis

This project analyzes the IPL 2024 season using data on batting, bowling, match details, and summaries. The goal is to provide insights into player performance and match outcomes using Python and Tableau.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Processing](#data-processing)
- [Analysis and Visualizations](#analysis-and-visualizations)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Project Overview
This project focuses on the IPL 2024 season and includes:
- Performance analysis of batsmen and bowlers.
- Match outcome analysis.
- Visualization of key statistics using Tableau.

## Data Sources
The analysis is based on four CSV files:
1. `season_batting_card.csv`
2. `season_bowling_card.csv`
3. `season_details.csv`
4. `season_summary.csv`

### Columns in Each File
- **season_batting_card.csv**:
  - season, match_id, match_name, home_team, away_team, venue, city, country, current_innings, innings_id, name, fullName, runs, ballsFaced, minutes, fours, sixes, strikeRate, captain, isNotOut, runningScore, runningOver, shortText

- **season_bowling_card.csv**:
  - season, match_id, match_name, home_team, away_team, bowling_team, venue, city, country, innings_id, name, fullName, overs, maidens, conceded, wickets, economyRate, dots, foursConceded, sixesConceded, wides, noballs, captain

- **season_details.csv**:
  - season, match_id, match_name, home_team, away_team, current_innings, innings_id, over, ball, runs, shortText, isBoundary, isWide, isNoball, batsman1_id, batsman1_name, batsman1_runs, batsman1_balls, bowler1_id, bowler1_name, bowler1_overs, bowler1_maidens, bowler1_runs, bowler1_wkts, batsman2_id, batsman2_name, batsman2_runs, batsman2_balls, bowler2_id, bowler2_name, bowler2_overs, bowler2_maidens, bowler2_runs, bowler2_wkts, wicket_id, wkt_batsman_name, wkt_bowler_name, wkt_batsman_runs, wkt_batsman_balls, wkt_text, isRetiredHurt

- **season_summary.csv**:
  - season, id, name, short_name, description, home_team, away_team, toss_won, decision, 1st_inning_score, 2nd_inning_score, home_score, away_score, winner, result, start_date, end_date, venue_id, venue_name, home_captain, away_captain, pom, points, super_over, home_overs, home_runs, home_wickets, home_boundaries, away_overs, away_runs, away_wickets, away_boundaries, highlights, home_key_batsman, home_key_bowler, home_playx1, away_playx1, away_key_batsman, away_key_bowler, match_days, umpire1, umpire2, tv_umpire, referee, reserve_umpire

## Data Processing
The data was processed using Python, with key steps including:
- Loading and cleaning the data.
- Calculating performance metrics for batsmen and bowlers.
- Aggregating match outcomes and statistics.

### Key Python Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## Analysis and Visualizations
The analysis includes:
- **Batting Performance Metrics**: Runs, Strike Rate, Fours, Sixes
- **Bowling Performance Metrics**: Wickets, Economy Rate, Dot Balls, Overs in Power Play, Middle Overs, and Death Overs

### Example Visualizations
- Top Performers in Batting and Bowling
![bat](https://github.com/bhkritika/IPL-2024-Season-Analysis/assets/141895513/158bdcce-a98d-4dae-a8ed-e36389a1cd9c)
![bowl](https://github.com/bhkritika/IPL-2024-Season-Analysis/assets/141895513/80651c9c-74e0-43da-9ea7-650b7e56a705)

- Boundary Analysis Over Time
![boundaries](https://github.com/bhkritika/IPL-2024-Season-Analysis/assets/141895513/779138f3-a150-4ba4-bbc1-246f7a355a87)

## Results

The results of the analysis include detailed performance metrics for each player and match, along with visualizations that provide insights into the IPL 2024 season.
![bat](https://github.com/bhkritika/IPL-2024-Season-Analysis/assets/141895513/8ff0fa98-4a8a-49bf-923a-81eae4952991)
![perf](https://github.com/bhkritika/IPL-2024-Season-Analysis/assets/141895513/5150f750-e914-4d3b-90a2-5ce314456af0)


## Acknowledgements

1. Thanks to the IPL for providing the data.
2. Thanks to the developers of pandas, matplotlib, seaborn, and other libraries used in this project.

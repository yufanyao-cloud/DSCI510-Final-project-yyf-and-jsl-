# DSCI510-Final-project-yyf-and-jsl-
this is a final project group work created by Yufan Yao and Shanglin Jiang


# Project Name: Top 15 Playoff Scorers per 48 Minutes (2024 NBA Playoffs)

## Project Overview
This project analyzes scoring efficiency in the 2024 NBA Playoffs using points per 48 minutes as a standardized metric. 
By adjusting scoring output for playing time, the project compares players with different roles and minute allocations and highlights differences between efficiency-based and volume-based scoring.

## Data
The data were collected from Basketball-Reference and include per-game player statistics from the 2024 NBA Playoffs.  
For reproducibility, both the original scraped data and the cleaned datasets are stored locally.

- `data/raw/`: original scraped data  
- `data/processed/`: cleaned and structured data used for analysis and visualization  

## Project Structure
project/
├── README.md
|── requirements.txt
├── data/
│   ├── raw/
│   │   |──nba_playoffs_per_game_2019.csv
│   │   |──nba_playoffs_per_game_2020.csv
│   │   |──nba_playoffs_per_game_2021.csv
│   │   |──nba_playoffs_per_game_2022.csv
│   │   |──nba_playoffs_per_game_2023.csv
│   │   |──nba_playoffs_per_game_2024.csv
│   └── processed/
│       |── nba_playoffs_clean_2019.csv
|       ├── nba_playoffs_clean_2020.csv
|       ├── nba_playoffs_clean_2021.csv
|       ├── nba_playoffs_clean_2022.csv
|       ├── nba_playoffs_clean_2023.csv
|       ├── nba_playoffs_clean_2024.csv
|       └── nba_playoffs_clean_all_seasons.csv
├── final_project.ipynb
├── Project_proposal.pdf
├── results/
|       └──final_report.pdf
|── src/
|     ├── clean_data.py
|     ├── get_data.py
|     ├── run_analysis.py
|     ├── utils/
|     └── visualize_results.py


## How to Run
1. Install the required dependencies:
   pip install -r requirements.txt
2. Open and run `final_project.ipynb` using Jupyter Notebook.

## Dependencies
All external libraries required to run the project are listed in `requirements.txt`.

# NBA MVP Predictor
*Created June 2025*

Analysis of NBA mvp voting results, player statistics, and team performace data to predict MVP winners using Python and machine learning.

## Overview
Built a Random Forest classifier that analyzes NBA player, team, and mvp voting data from 1991-2024 to predict MVP voting rankings. This project was based on tutorials from Dataquest. 

## Data
- Player statistics and performance metrics
- Team performance data
- Historical MVP voting results

## Files
- `mvp.ipynb` - Web scrape data from BasketballReference
- `data_cleaning.ipynb` - Data preprocessing and cleaning
- `model.ipynb` - Machine learning model development
- `mvps.csv` - MVP voting dataset
- `players.csv` - Player stats dataset
- `teams.csv` - Team performance dataset
- `total_stats.csv` - Combined dataset for modeling
- `players/` - folder containing HTML files of player data
- `data/` - folder containing HTML files of MVP voting data 
- `team/` - folder containing HTML files of team performance data

## Usage
1. Clone the repository
2. Install libraries listed below
3. Run the Jupyter notebooks in order

## Results
The random forest model achieved a mean average precision score of 75.5% after running an expanding-window backtest from 1996-2024.

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Selenium
- Pandas
- Scikit-Learn
- Matplotlib
- Jupyter Notebooks

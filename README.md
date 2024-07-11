# T20 World Cup Data Analysis

## Description
This technical documentation outlines the process and methodology for analyzing the T20 World Cup statistics to determine the best "Playing 11" squad from all participating countries. The aim is to leverage historical data to identify the top-performing players and create an optimal team composition based on various performance metrics.


## Data Collection
### Data Sources
- **Official T20 World Cup Website**: Match scores, player statistics, and team performance.
- **ESPN Website**: Detailed player statistics including batting averages, strike rates, bowling economy rates, and fielding records

### Data Acquisition Methods
- Web Scraping: Automated scripts to extract data from websites.

## Data Preparation
### Data Cleaning
- Removing Duplicates: Ensuring no redundant entries for players or matches.
- Handling Missing Values: Imputing missing data points or excluding incomplete records.
- Formatted String: String containing unusual characters were replaced by empty string

### Data Transforming
- Added Columns that added more value and meaning to the Table / Data.
- Created Relationship (Many to one) between certain columns
- Ensuring consistency in data formats (e.g., date formats, numerical precision).
- Added Key Measures and Calculated Columns

## Data Analysis - Visualization using PowerBI
### Parameter to look after each Field
- **Openers** : Batting Average, Batting Position, Boundary%, Strike Rate, Total Innings Batted, Total Runs
- **Middle Order** : Batting Average, Batting Position, Boundary%, Strike Rate, Total Innings Batted, Total Runs
- **Lower Order**: Average Balls Faced, Batting Average, Batting Position, Total Innings Batted, Wickets
- **Lower Middle Order**: Batting Average, Batting Position, Bowling Striking Rate, Economy, Total Innings Batted, Total Innings Bowled
- **Specialist Fast Bowler**: Bowling Average, Bowling Strike Rate, Bowling Style, Dot Ball%, Economy, Total Innings Bowled

 ### Creating Dashboard
 #### Openers 
 ![Openers Dasboard]()
 #### Middle Order
 ![Openers Dasboard]()
 #### Lower Order
 ![Middle Order Dasboard]()
 #### Lower Middle Order
 ![Lower Middle Order Dasboard]()
 #### Specialist Fast Bowler
 ![Specialist Fast Bowler Dasboard]()

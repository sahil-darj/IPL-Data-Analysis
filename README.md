# IPL Data Analysis Dashboard using Power BI

## Project Overview
This project is an **interactive IPL (Indian Premier League) data analysis dashboard** built using **Microsoft Power BI Desktop**.  
It provides insights into IPL matches, teams, players, and trends from 2008–2023 using `matches.csv` and `deliveries.csv` datasets.

---

## Project Objectives
- Analyze IPL match data efficiently.  
- Provide interactive **KPI metrics**, charts, and slicers for quick insights.  
- Enable users to explore:  
  - Total matches, runs, and sixes  
  - Matches won by each team  
  - Top run scorers  
  - Runs per season  
  - Toss decision preferences  

---

## Data Source
- `matches.csv` – contains match-level information (season, teams, winner, toss, venue, player of the match, etc.)  
- `deliveries.csv` – ball-by-ball data (batsman, bowler, runs, dismissals, etc.)  
- Source: [Kaggle IPL Datasets](https://www.kaggle.com/datasets)  

---

## Features / Visualizations
- **KPI Cards:** Total Matches, Total Runs, Total Sixes  
- **Charts:**  
  - Matches Won by Team (Clustered Bar)  
  - Top Run Scorers (Clustered Bar)  
  - Runs per IPL Season (Column Chart)  
  - Toss Decision Analysis (Pie Chart)  
- **Slicers:** Season, Team, Venue for interactivity  
- **Insights Section:** 8 key IPL insights derived from data  

---

## System Approach
1. **Data Loading:** Import CSV files into Power BI  
2. **Data Cleaning:** Remove nulls, fix datatypes, transform season column  
3. **Data Modeling:** Create relationships between tables (`matches.id → deliveries.match_id`)  
4. **Visualization:** Create cards, charts, and pie chart  
5. **Interactivity:** Add slicers for season, team, and venue  
6. **Insights:** Analyze trends and present findings  

---

## Deployment
- **Offline:** Power BI Desktop file (`IPL_Analysis.pbix`)  
- **Optional Online Deployment:** Microsoft Power BI Service (requires Microsoft account)  

---

## Installation / Usage
1. Clone the repository:  
```bash
git clone https://github.com/YourUsername/IPL-PowerBI-Dashboard.git
```
Open IPL_Analysis.pbix in Power BI Desktop

Use slicers to interact with data and explore insight

# IPL_Analysis_SQL-POWER-BI
This project is a comprehensive **Power BI Dashboard** analyzing IPL statistics from 2008 to 2024. Using SQL queries and datasets of matches and ball-by-ball deliveries, the dashboard gives visual insights into top-performing teams, players, and venues.

![IPL Dashboard Screenshot](IPL%20DASHBOARD.png)


## 📊 Dashboard Features
- Total Runs, Wickets, Fours, Sixes, Super Overs
- Top 5 Teams by Wins, Sixes, Fours
- Top Batsmen & Bowlers
- Player of the Match analysis
- Venue-based insights
- Most dot balls, extras, runs conceded, etc.

## 📁 Files Included
- `IPL Dashboard.pbix`: Power BI dashboard file
- `matches.csv`: IPL match-level data
- `deliveries.csv`: Ball-by-ball data
- `IPL Queries.docx`: SQL queries used for analysis
- `Screenshot.png`: Dashboard snapshot

## 🛠 Tools Used
- **Power BI** for data visualization
- **SQL** for data transformation & aggregation
- **MS Excel/CSV** for raw data
- **GitHub** for version control & portfolio

## 📌 SQL Query Examples
```sql
-- Total number of unique IPL seasons
SELECT COUNT(DISTINCT season) FROM matches;

-- Top 5 batsmen by total runs
SELECT TOP 5 batter, SUM(batsman_runs) 
FROM deliveries 
GROUP BY batter 
ORDER BY SUM(batsman_runs) DESC;
```

## 📊 Data Sources
- Kaggle IPL dataset (matches and deliveries)
- Custom queries from IPL data (2008–2024)

## 👤 Author
**Your Name**  
📧 pittaakshay045@gmail.com  
🔗 https://www.linkedin.com/in/pittaakshay0264/

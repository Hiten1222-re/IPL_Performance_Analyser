🏏 IPL Match Performance Analyzer
<img width="916" height="738" alt="image" src="https://github.com/user-attachments/assets/a9ce8d06-2326-436f-8021-c2520101751d" />
<img width="872" height="753" alt="image" src="https://github.com/user-attachments/assets/bd21c7be-a2da-4226-a3fd-0b556066d12a" />
<img width="1373" height="643" alt="image" src="https://github.com/user-attachments/assets/3cd070ee-275d-4ed5-9e4d-2bea9fc317ba" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7f4b4da9-9f95-47f6-aaeb-1effcbbf4719" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9b052dc4-8119-4970-86ff-4c5f4b41c9a7" />

A comprehensive data analysis project exploring 260,920 IPL ball-by-ball deliveries across 1,095 matches from 2008 to 2024. Uncovers batting patterns, bowling dominance, and team performance trends through Python analysis and interactive Tableau dashboards.

📊 Key Findings

V Kohli is the all-time top run-scorer with 8,014 runs, performing 28.4% better in middle overs compared to powerplay
YS Chahal leads all-time wicket-takers with 213 wickets across all phases
Mumbai Indians leads all franchises in total runs scored across 16 seasons
Top 3 run-scoring teams analyzed: CSK, KKR, Mumbai Indians with their top individual contributors


🔍 Analysis Performed
Python (Pandas + Matplotlib)

Phase-wise batting analysis — Powerplay (0–6), Middle (7–16), Death (17–20) run scoring patterns
Top run-scorers by team — identified best batsmen per franchise
Virat Kohli deep-dive — season-wise average and phase-wise performance comparison
Bowler phase analysis — wickets taken per bowler split across innings phases
RCB season trend — line plot of average scores across all seasons
Best team improvement — tracked Mumbai Indians' season-by-season scoring evolution

Tableau Dashboard (3 Sheets)

Sheet 1 — Top 15 Run-Scorers Teamwise: Bar chart of top 15 batsmen colored by team, filtered by batting_team
Sheet 2 — Top 3 Teams & Their Top Batsmen: Nested bar showing top run-scorers within CSK, KKR, and Mumbai Indians using calculated field
Sheet 3 — Top 10 Bowlers by Phase: Stacked bar of top 10 wicket-takers split by Powerplay / Middle / Death overs


🛠 Tech Stack
ToolPurposePython 3.xData loading, cleaning, analysisPandas + NumPyData manipulation and aggregationMatplotlibLine plots, bar charts, visualizationsTableauInteractive dashboards and filtersExcel (.xlsx)Source dataset

📁 Project Structure
ipl-analysis/
├── Data_Analytics_IPL.ipynb   # Main analysis notebook
├── Book1.twb                  # Tableau workbook (3 dashboards)
├── deliveries.xlsx            # Ball-by-ball IPL dataset (2008–2024)
└── README.md

🚀 Getting Started

Clone the repo

bash   git clone https://github.com/Hiten1222-re/ipl-analysis

Install dependencies

bash   pip install pandas numpy matplotlib openpyxl

Open the notebook

bash   jupyter notebook Data_Analytics_IPL.ipynb

For Tableau dashboard — open Book1.twb in Tableau Desktop and connect to deliveries.xlsx


📸 Screenshots

Add screenshots of your Tableau dashboards and key matplotlib charts here


📌 Dataset

Source: Kaggle — IPL Ball-by-Ball Data (2008–2024)
Size: 260,920 deliveries across 1,095 matches
Columns: match_id, inning, batting_team, bowling_team, over, ball, batter, bowler, batsman_runs, total_runs, is_wicket, dismissal_kind, fielder, extras_type, extra_runs


👤 Author
Hiten Dariyanani

LinkedIn: linkedin.com/in/hiten-dariyanani901a75332
GitHub: github.com/Hiten1222-re

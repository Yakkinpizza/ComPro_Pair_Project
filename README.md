⚽ FIFA 26 Player Data Analysis
📄 Overview

This project is a simple Exploratory Data Analysis (EDA) using the FIFA 26 Player Dataset from Kaggle.
The goal is to discover interesting patterns in player data — such as top players, best countries, and skill differences by position.
All code was written in Google Colab (Python) using Pandas and Seaborn for visualization.

📊 Dataset Information

Source: Kaggle – FC 26 Player Data

File: FC26_20250921.csv
Total Players: 18,405
Total Columns: 110

Main Columns Used:

Player Info: short_name, age, nationality_name, club_name, overall, potential

Skills: pace, shooting, passing, dribbling, defending, physic

🧠 Steps of Analysis

Load Data

Used kagglehub to download the dataset directly from Kaggle.

Loaded data into a Pandas DataFrame.

Explore Data

Counted number of players, countries, and clubs.

Explored age and overall rating distributions.

Find Top Players & Nations

Listed top 10 players by overall rating.

Found top 10 nations with the highest average rating (countries with ≥30 players).

Analyze Player Positions

Added a column for each player’s main position.

Focused on six key skills for field players.

Computed average skill per position.

Visualize Data

Plotted histograms and bar charts to visualize:

Age and rating distributions

Top players and nations

Skill comparison across positions

📈 Main Visualizations

Age Distribution: Most players are between 18–30 years old.

Overall Rating Distribution: Most ratings fall between 60–80.

Top 10 Players: Includes Mbappé, Haaland, Messi, and others.

Top 10 Nations: France, Spain, and Brazil lead in average player ratings.

Skill Comparison by Position:

Attackers → high pace & shooting

Midfielders → strong passing & dribbling

Defenders → solid defending & physic

Goalkeepers excluded (different skill attributes)

💡 Insights

Player skills align naturally with their positions.

Attacking players focus on speed and finishing, while defenders prioritize strength and tackling.

Nations like France and Brazil have deeper, high-quality talent pools.

✅ Conclusion

This project provides a concise, visual overview of FIFA 26 player data.
It highlights which countries and positions stand out and how player skills differ.
The notebook is simple, reproducible, and can easily be extended for future football data analyses.

🧩 Tools Used

Python

Google Colab

Pandas

NumPy

Matplotlib / Seaborn

KaggleHub

🏏 IPL Data Analysis (2008–2024)

This project presents a complete exploratory data analysis (EDA) of the Indian Premier League (IPL) from 2008 to 2024. Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the notebook examines match-level and ball-by-ball data to uncover patterns, trends, and insights related to team performance, players, dismissal types, winning strategies, and season-wise variations. The project runs entirely on Jupyter Notebook and is built for data analytics learning, visualization, and cricket insights.

📌 Dataset Description

The project uses two primary datasets:

matches.csv – Contains match-level details, including teams, toss decision, winner, venue, scores, and season.

deliveries.csv – contains ball-by-ball information including batsman runs, bowler deliveries, wickets, dismissal type, extras, and match innings details.

These datasets can be downloaded from Kaggle.

🛠️ Technologies Used

This analysis is developed using:
Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

📘 Notebook Structure (With Steps Followed)

The entire notebook is organized into clean, easy-to-follow steps:

1. Importing Libraries

The notebook begins by importing all necessary libraries such as Pandas, NumPy, Matplotlib, and Seaborn, along with some helper functions for visualization.

2. Loading the Dataset

Both matches.csv and deliveries.csv are loaded into Pandas DataFrames.
Basic checks like shape, info, and headers are performed here.

3. Data Cleaning and Preprocessing

This step covers:

Handling missing values

Converting data types

Standardizing team names

Fixing inconsistencies

Removing unnecessary columns

4. Exploratory Data Analysis (EDA)

A detailed descriptive analysis is performed on both datasets.
Key patterns explored include:

Most successful teams

Toss impact on winning

Venue-wise performance

Dismissal type distribution

Season-wise title winners

Top batsmen (total runs)

Top bowlers (total wickets)

Boundary analysis (4s & 6s)

5. Data Visualization

The notebook contains multiple visualizations, such as:

Bar plots

Count plots

Pie charts

Line graphs

Heatmaps

Each visualization is color-optimized using a custom random color palette.

6. Insights & Conclusions

This final section interprets the charts and highlights patterns such as:

Which teams dominate across seasons

Which batsmen and bowlers consistently perform

How dismissal types vary

How venues influence match outcomes

📊 Summary of Key Insights

This project identifies the top players, winning consistency, popular dismissal methods, batting trends, and seasonal variations across all 17 IPL seasons. The visuals provide a clear understanding of how the league evolved and which teams or players had the biggest impact.

🚀 How to Run This Project

To run this analysis on your system:

Clone or download the repository.

Install the required libraries using' pip install pandas numpy matplotlib seaborn'.

Open the .ipynb notebook in Jupyter Notebook.

Place matches.csv and deliveries.csv inside the project folder.

Run the notebook cells in order to see results and visualizations.

NBA Team Performance Analysis and Predictions
Overview
This project analyzes NBA team performance data from the 2014-2023 regular seasons and 2015-2022 playoff seasons. It aims to answer specific questions and make predictions using statistical models and data visualizations. The analysis focuses on various game statistics to uncover patterns and insights that influence game outcomes and playoff success.

Table of Contents
Features
Installation
Usage
Project Structure
Results
Contributing
Features
Data Cleaning and Preparation:

Filtered and cleaned large datasets to focus on relevant seasons and game statistics.
Integrated data from multiple sources to ensure comprehensive analysis.
Statistical Analysis:

Calculated offensive and defensive effective field goal percentages (eFG%) for teams.
Analyzed the correlation between eFG% and game outcomes, finding that teams with higher eFG% won 81.6% of the time.
Determined that teams with more offensive rebounds won 46.21% of the time, explaining that shooting efficiency has a greater impact on game outcomes than offensive rebounds.
Predictive Modeling:

Developed a model to predict playoff series outcomes based on various team statistics, such as eFG%, net rating, and wins.
Applied the model to predict the outcomes of the 2024 NBA playoffs, including the probability of each team advancing to each round.
Key Findings:

Teams with a +5.0 net rating in the regular season had an 87.9% chance of making it to the second round of the playoffs the following year.
Among those teams, 27.88% of their top 5 minutes-played players participated in the second round series.
Installation
To run this project locally, follow these steps:


Navigate to the project directory:

cd Basketballl

Install the required packages:
Ensure you have R installed, then run:

install.packages(c("tidyverse", "ggplot2"))

Download the datasets:
Place the datasets (player_game_data.csv, team_game_data.csv) in the data/ directory.

Usage
To replicate the analysis, follow these steps:

Run the RMarkdown file:
Open NBA_R_project_A_Acuna.Rmd in RStudio or your preferred R environment and knit the document to generate the HTML output.

View outputs:
Check the generated NBA_R_project_A_Acuna.html file for the analysis results, visualizations, and model predictions.

Project Structure
nba-performance-analysis/
│
├── NBA_R_project_A_Acuna.Rmd
│
├── NBA_R_project_A_Acuna.html
│
├── player_game_data.csv
│
└── team_game_data.csv
Results
The project provides insights into the factors influencing NBA game outcomes and playoff success. Key findings include:

Higher eFG% correlates with winning 81.6% of the time.
Offensive rebounds are less impactful than shooting efficiency, with a 46.21% correlation to winning.
Teams with a +5.0 net rating in the regular season have an 87.9% chance of making the second round of the playoffs the following year.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

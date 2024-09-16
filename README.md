# nba_draft_simulator

NBA Draft 2023 Data Analysis
Table of Contents
Introduction
Project Structure
Dataset
Installation
Usage
Results
Contributing
License
Introduction
This project provides an in-depth analysis of the 2023 NBA Draft prospects and their predicted performance based on various statistics. By analyzing player stats from the previous season and evaluating the draft odds, this project aims to forecast player outcomes, rank future prospects, and provide insights for sports analysts, enthusiasts, and teams.

The project utilizes Python and Jupyter notebooks for the data analysis process, including data cleaning, feature engineering, and machine learning modeling.

Project Structure
The project consists of the following components:

yaml
Copy code
NBA-Draft-2023/
│
├── NBA_Draft-2023.ipynb       # Jupyter notebook containing the analysis and predictions
├── Draft Odds 2023.csv        # CSV file with NBA draft odds for each player in 2023
├── Player Stats 2023.csv      # CSV file with player performance data for the 2023 season
├── README.md                  # Project documentation
└── requirements.txt           # Dependencies required to run the project
Key Files:
NBA_Draft-2023.ipynb: Contains the data exploration, analysis, and prediction models.
Draft Odds 2023.csv: Contains data on draft odds, which include player names, odds, and team assignments.
Player Stats 2023.csv: Includes detailed player statistics such as points, rebounds, assists, and other advanced metrics for the 2023 season.
Dataset
Draft Odds
Source: NBA 2023 Draft Prediction markets
Columns:
Player Name
Draft Odds
Projected Pick
Player Stats
Source: NBA Player statistics for the 2023 season
Columns:
Player Name
Team
Position
Points Per Game (PPG)
Rebounds Per Game (RPG)
Assists Per Game (APG)
Field Goal Percentage (FG%)
Three-Point Percentage (3P%)
Free Throw Percentage (FT%)
Advanced metrics (PER, WS, BPM, etc.)
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/NBA-Draft-2023.git
cd NBA-Draft-2023
Install required dependencies:

Ensure you have Python 3.x installed, then run:

bash
Copy code
pip install -r requirements.txt
Launch Jupyter Notebook:

Once the environment is set up, launch Jupyter Notebook:

bash
Copy code
jupyter notebook
Open the NBA_Draft-2023.ipynb file from the Jupyter interface to view the analysis and models.

Usage
The project is structured as a Jupyter notebook, making it interactive and easy to follow. The notebook walks through the following steps:

Data Import: Loading the Draft Odds 2023.csv and Player Stats 2023.csv files into dataframes.
Data Cleaning: Handling missing values, data type conversions, and any required data transformation.
Exploratory Data Analysis (EDA): Visualizing player statistics, trends, and correlations between draft odds and performance metrics.
Feature Engineering: Creating new features from the existing data to improve model performance.
Modeling: Training machine learning models to predict the draft position of each player.
Evaluation: Assessing the model's accuracy and providing insights into the key metrics.
Running the Project:
After launching the notebook, you can execute each cell to see the step-by-step process of data analysis, including visualizations and predictions.

Results
Key findings from this project include:

Top Draft Prospects: Predicted top picks based on performance metrics and draft odds.
Player Performance: Insights into which player statistics most influence their draft position.
Model Accuracy: The model's accuracy in predicting draft outcomes, along with feature importance.
Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new feature branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Create a new pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
 

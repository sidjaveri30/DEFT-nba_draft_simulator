# nba_draft_simulator

# NBA Draft 2022 &2023 Data Analysis

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Results](#results)


## Introduction

This project provides an in-depth analysis of the 2022 and 2023 NBA Draft prospects and their predicted performance based on various statistics. By analyzing player stats from the 2022 and 2023 season and evaluating draft odds, this project aims to forecast player outcomes, rank future prospects, and provide valuable insights for sports analysts, enthusiasts, and NBA teams.

The analysis is conducted using Python and Jupyter notebooks, covering data cleaning, exploratory analysis, and machine learning modeling to predict NBA draft positions.

## Project Structure

The project consists of the following components:

### Key Files:
- **NBA_Draft-2023.ipynb**: Contains the entire analysis process, from data exploration to predictions.
- **Draft Odds 2023.csv**: Holds data on draft odds for each NBA team
- **Player Stats 2023.csv**: Includes detailed player statistics such as points, rebounds, assists, field goal percentage, and advanced metrics.
- **NBA_Teams_Final.csv**: Contains decimal values for each team corresponding to team needs such as star potential, three point shooting, offense, etc.

## Dataset

### Draft Odds 
- **Columns**:
  - Team Name
  - Seed
  - Chances
  - Percentage Points for Draft Picks 1-30

### Player Stats 
- **Columns**:
  - Player Name
  - Team
  - Position
  - Points Per Game (PPG)
  - Rebounds Per Game (RPG)
  - Assists Per Game (APG)
  - Field Goal Percentage (FG%)
  - Three-Point Percentage (3P%)
  - Free Throw Percentage (FT%)
  - Advanced metrics (PER, WS, BPM, etc.)

 ### NBA Teams Final
 - **Columns**:
   - Team
   - Star Potential Need
   - Shooting Need
   - Offense Need
   - Defense Need
   - Rebounding Need
   - Playmaking Need
 

## **Results**
The model was successful in emulating similar results to the actual 2022 and 2023 NBA drafts. The first 30 selections of the draft were included in the simulation. The results of the draft were slightly different with each iteration of the simulation. The earlier picks in the simulation were very similar to the real draft, whcih was expected because the caliber of players who are selected earlier in the draft is more solidified. There was more variation in the draft picks in the latter part of the simulation because the players' skillsets were much more comparable, leading to different results in comparison to the actual 2022 and 2023 drafts.




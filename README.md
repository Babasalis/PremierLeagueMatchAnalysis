# ⚽ Premier League Match Analysis with Python

## Overview

This project explores premier league match data using Python to uncover patterns in team performance, match outcomes, and key performance statistics. The analysis includes data cleaning, exploratory data analysis (EDA), visualizations, and statistical analysis to answer several football analytics questions.

## Objectives

The project investigates the following questions:
1. Which teams consistently outperform their Expected Goals (xG), and what does this suggest about their finishing ability?
2. How does possession percentage differ between wins, draws, and losses? Is possession associated with match success?
3. Does home-field advantage exist, and how does team performance differ between home and away matches?
4. Which match statistics are most strongly associated with winning a game?

## Dataset

The dataset contains soccer match statistics across multiple seasons, including team performance metrics such as:
- Goals For (GF)
- Goals Against (GA)
- Expected Goals (xG)
- Expected Goals Against (xGA)
- Possession Percentage
- Shots
- Shots on Target
- Match Results
- Home/Away Information
- Team Formations

## Data Cleaning

Before performing the analysis, the dataset was cleaned by:
- Identifying and handling missing values
- Imputing missing data using team and season averages
- Removing duplicate records based on certain columns
- Verifying data consistency across seasons
- Preparing variables for analysis

## Exploratory Data Analysis

The project includes exploratory analysis to better understand the data by examining:
- Distribution of match statistics
- Team performance trends
- Goal-scoring patterns
- Possession statistics
- Correlation between numerical variables

## Key Findings

### Expected Goals vs Actual Goals
- Compared actual goals scored to Expected Goals (xG).
- Identified teams that consistently exceeded their expected goal totals, suggesting above-average finishing efficiency.

### Possession and Match Results
- Converted match results into a points system (Win = 3, Draw = 1, Loss = 0).
- Compared average possession across different match outcomes.
- Explored whether higher possession is associated with winning.

### Home-Field Advantage
- Compared home and away performance.
- Analyzed differences in match results and team statistics to evaluate home-field advantage.

### Match Statistics Associated with Winning
- Calculated correlations between match statistics and match outcomes.
- Found that Goals For (GF) had the strongest positive relationship with winning, while Goals Against (GA) had the strongest negative relationship.
- Other statistics, including possession, showed weaker relationships with match outcomes.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Feature Engineering
- Statistical Interpretation
- Sports Analytics
- Python Programming

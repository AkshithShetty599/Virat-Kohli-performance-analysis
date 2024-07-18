# Virat Kohli Performance Analysis

This project performs an exploratory data analysis (EDA) on the performance of Virat Kohli. The analysis includes various visualizations and insights to understand different aspects such as runs scored, batting order, innings, and performance against different opponents.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Analysis and Visualizations](#analysis-and-visualizations)
  - [Runs Scored Over the Years](#runs-scored-over-the-years)
  - [Distribution of Matches Played as Per Batting Order](#distribution-of-matches-played-as-per-batting-order)
  - [Runs Scored at Different Batting Orders](#runs-scored-at-different-batting-orders)
  - [Comparison of Runs Based on Innings](#comparison-of-runs-based-on-innings)
  - [Comparison of Runs Scored Against Countries](#comparison-of-runs-scored-against-countries)
  - [Exploring Relationship of 4s and 6s with Runs](#exploring-relationship-of-4s-and-6s-with-runs)
  - [Strike Rate Trends Over the Years](#strike-rate-trends-over-the-years)
- [Conclusion](#conclusion)

## Introduction

This project aims to analyze Virat Kohli's performance over the years. The analysis covers aspects such as runs scored, batting order, innings, and performance against different opponents.

## Installation

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn

## You can install the required libraries using pip:

pip install pandas numpy matplotlib seaborn

# Data Overview

The dataset contains information about Virat Kohli's cricket performance. The data includes the following columns:

* Runs: Runs scored by Kohli
* BF: Balls faced by Kohli
* 4s: Number of fours hit by Kohli
* 6s: Number of sixes hit by Kohli
* SR: Strike rate of Kohli
* Pos: Batting position of Kohli
* Dismissal: How Kohli got out
* Inns: Innings number
* Opposition: Opponent team
* Start Date: Date of the match

# Data Preprocessing

The data types of some columns were converted to smaller data types to reduce memory usage. The Start Date column was converted to datetime format for easier time-based analysis.

# Analysis and Visualizations

## Runs Scored Over the Years
A line plot showing the total runs scored by Kohli each year from 2008 to 2017.

### Conclusion
* Kohli scored the maximum runs in the year 2012.

## Distribution of Matches Played as Per Batting Order
A pie chart showing the distribution of matches played by Kohli at different batting positions.

### Conclusion
* Kohli played most of his matches at number 3.

## Runs Scored at Different Batting Orders
A bar plot showing the total runs scored by Kohli at different batting positions.

### Conclusion
* Kohli scored more than 4000 runs at number 3.

## Comparison of Runs Based on Innings
A box plot comparing the distribution of runs scored by Kohli in the 1st and 2nd innings.

### Conclusion
* Kohli has a better average in the 2nd innings.

## Comparison of Runs Scored Against Countries
A horizontal bar plot showing the total runs scored by Kohli against different opponents.

### Conclusion
* Kohli has scored the most runs against Sri Lanka.

## Exploring Relationship of 4s and 6s with Runs
Two scatter plots with regression lines showing the relationship between the number of runs scored and the number of fours and sixes hit by Kohli.

### Conclusion
* There is a linear relationship between fours and runs but no strong linear relationship in the case of sixes. It means that Virat Kohli likes playing fours. The more runs he scores in an innings, the more fours he plays.

## Strike Rate Trends Over the Years
A line plot showing the average strike rate of Kohli each year.

### Conclusion
* There is a significant rise in strike rate after 2012.

# Conclusion
* Kohli scored the maximum runs in the year 2012.
* Kohli played most of his matches at number 3.
* Kohli scored more than 4000 runs at number 3.
* Kohli has a better average in the 2nd innings.
* Kohli has scored the most runs against Sri Lanka.
* There is a linear relationship between fours and runs but no strong linear relationship in the case of sixes. Kohli likes playing fours.
* There is a significant rise in strike rate after 2012.
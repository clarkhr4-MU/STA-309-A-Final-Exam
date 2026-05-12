# STA-309-A-Final-Exam
Analyzing the TidyTuesday Coffee Ratings Dataset to Explore Factors Related to Coffee Quality
Overview

Analyzed the TidyTuesday Coffee Ratings dataset to explore factors related to coff ee quality. The goal was to find out what coffee characteristics best predict overall coffee ratings.

Dataset

coffee_ratings.csv
Source: TidyTuesday Coffee Ratings Dataset
Dataset Link: https://github.com/rfordatascience/tidytuesday/tree/main/data/2020/2020-07-07
The dataset includes both numeric and categorical variables related to coffee quality.

Response Variable: "total_cup_points" = Overall Coffee Quality Score
Main Predictors: aroma, flavor, aftertaste, altitude_mean_meters, processing_method, continent, species

Code Files:
STA 309 - Final Exam (Clark).R 
- Main R script containing all analysis code
STA 309 - Final Exam (Clark.rmd).Rmd
- R Markdown Version
STA-309---Final-Exam--Clark.rmd-.html
- HTML Output

Exploratory Data Analysis & Visualization

Dashboard
- Coffee Ratings Dashboard.pdf

Individual Plots
- Plot #1 (Aroma vs. Total Cup Points).pdf
- Plot #2 (Flavor vs. Coffee Rating).pdf
- Plot #3 (Coffee Rating by Processing Method).pdf
- Plot #4 (Altitude vs. Coffee Rating).pdf
- Plot #5 (Coffee Ratings by Continent).pdf
The visualizations help to see the relationships between coffee quality and different predictors.

Model Comparison

- Model Performance Comparison.pdf
- Visualization comparing predictive model RMSE values
The following predictive models were trained using 5-fold cross-validation:
1. Linear Regression (Small Predictor Set)
2. Linear Regression (All Predictors)
3. Regression Tree
4. Random Forest
5. Neural Network

Main Findings

1. Higher Aroma and Flavor scores usually led to higher coffee ratings.
2. Washed/Wet coffees had higher ratings.
3. Altitude had little/no effect on coffee quality.
4. African coffees had slightly higher ratings.
5. The Random Forest Model gave the most accurate predictions.

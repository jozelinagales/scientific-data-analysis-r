# Student Performance Analysis in R

This project examines whether **weekly study hours** and **nightly sleep duration** predict students' total academic scores.

It began as collaborative university coursework by **Alaa Moussa and Jozelina Gales** and is presented here as a cleaned portfolio version.

## Research question

Do study hours per week and sleep hours per night predict student performance, measured by total academic score?

## Analysis workflow

The R Markdown analysis includes:
- dataset inspection and missing-value checks
- descriptive statistics
- grouping of study/sleep variables
- ANOVA
- Pearson correlation
- multiple linear regression
- regression diagnostic plots
- boxplots and histograms using ggplot2

## Main interpretation

In the analysed dataset, study hours and sleep duration showed very weak relationships with total score, and neither variable was a significant predictor in the fitted multiple linear regression model.

## Reproducibility note

The original dataset is not redistributed in this repository. To run the analysis, place the dataset at:

`data/Students_Grading_Dataset.csv`

The public R Markdown file uses a relative path rather than the original local university-workflow path.

## Tools

R, RStudio, readr, psych, table1, ggplot2, tidyr, patchwork

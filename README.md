# The Effects of Government Policies on Covid-19 in Different Countries

This project analyzes how government policies impacted the spread of COVID-19 across different countries using datasets from Our World in Data and ACAPS. The analysis focuses on daily case numbers, policy interventions, and the timing of government actions in 11 selected countries.

# Overview
The study explores:

The relationship between government interventions (e.g., border closures, school closures, lockdowns) and daily COVID-19 cases.

Differences in outcomes between developed and underdeveloped countries.

Patterns in first and second waves of COVID-19 infections.

Interactive graphs are created for each country to show trends in daily cases alongside major government measures.

# Datasets
Our World in Data COVID-19 dataset (daily cases by country):

Link: https://ourworldindata.org/policy-responses-covid

ACAPS COVID-19 Government Measures dataset (policy measures by country and date):

Link: https://www.acaps.org/covid-19-government-measures-dataset

The analysis uses data up to 31st December 2020.

# Countries Analyzed
The selected countries represent different continents and development levels:

Brazil

China

Colombia

Israel

Italy

New Zealand

Nigeria

Norway

Russia

Turkey

United States

# Tools & Libraries
This project is implemented in R using the following libraries:

tidyverse – data wrangling

readxl – reading Excel datasets

ggplot2 – data visualization

plotly – interactive graphs

# Project Structure
RMarkdown File: The main analysis is in an .Rmd file.

Data Folder: Contains the downloaded datasets (owid-covid-data.csv and acaps_covid19_government_measures_dataset_0.xlsx).

Generated Output: Interactive HTML document with country-wise analysis.

# Key Insights
Closing borders early significantly reduced case numbers; reopening borders often triggered new waves.

Developed countries generally had better success controlling spread due to stronger healthcare systems and enforcement.

Underdeveloped countries (e.g., Nigeria, Brazil) faced challenges due to poverty, political instability, or data reliability.

Most countries experienced two clear waves, with the second often after the summer of 2020.

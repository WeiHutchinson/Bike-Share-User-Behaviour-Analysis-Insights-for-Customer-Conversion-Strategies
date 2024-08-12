# Bike-Share User Behaviour Analysis: Insights for Customer Conversion Strategies

## Table of Contents
- [Introduction/Overview](#introductionoverview)
- [Objective](#objective)
- [Methodology/Approach](#methodologyapproach)
- [Installation/Requirements](#installationrequirements)
- [File Descriptions](#file-descriptions)
- [Data Collection and Sources](#data-collection-and-sources)
- [Results/Conclusions](#resultsconclusions)
- [License](#license)

## Introduction/Overview
For this project, I explore the bike-sharing data provided by a fictional company, Cyclistic, to analyse and understand the differences in usage patterns between casual riders and annual members. The aim is to provide these insights to potentially increase the conversion of casual riders into annual members.

## Objective
To conduct a thorough analysis of the bike-sharing usage data to identify behavioural and usage differences between casual riders and annual members, which could help Cyclistic develop targeted strategies to increase its annual membership subscriptions.

## Methodology/Approach
The analysis involves several key steps:
- Data Cleaning: Preparing the data for analysis by handling inconsistencies and missing values.
- Descriptive Statistics: Summarising the data to find common patterns and trends.
- Data Visualisation: Using graphs to visually represent the data, making it easier to identify patterns between different user types.
- Hypothesis Testing: Testing assumptions related to user behaviours.
- Predictive Analytics: Using logistic regression to predict user behavior based on the available data.

Tools used include Python libraries such as Pandas, Matplotlib, and Seaborn. Detailed steps are documented in the Jupyter Notebook included in this repository.

## Installation/Requirements
To run this project, ensure you have the following libraries installed:
- Pandas
- Matplotlib
- Seaborn

The code is compatible with Python version 3.*.

## File Descriptions
This repository contains:
- `Bike_share script.ipynb`: Jupyter notebook containing all the code and detailed analysis.
- `README.md`: Provides an overview of the project and setup instructions.


## Data Collection and Sources
The data for this project was sourced from Motivate International Inc., under a public domain license as part of the Google Data Analytics Capstone Project. The dataset includes:
- User types (casual or member)
- Trip duration
- Start and end times of the rides
- Bike types
- Other relevant user interaction data
To download this dataset, please click here : https://divvy-tripdata.s3.amazonaws.com/index.html
The `combined_bike_data.csv` file used in this project aggregates bike-sharing data spanning from May 2023 to April 2024. Due to the extensive size of this dataset, it is not included directly in this repository. Please download the individual monthly files from the provided link above and combine them locally on your computer to recreate the dataset used for this analysis.
## Results/Conclusions
The analysis indicates several notable differences in how different user types interact with the bike-sharing service. Insights drawn from the data can help Cyclistic tailor its marketing strategies to convert more casual riders into annual members. Detailed findings and visualizations are provided in the `Bike_Analysis.ipynb` notebook.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

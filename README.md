
# Electability - Election Winner Prediction

This repository contains the code and analysis for the Electability project, which focuses on predicting the winners of Lok Sabha elections in India based on various factors.

## Project Overview

In this project, we aim to develop a centralized repository for data on Members of Lok Sabha in India and analyze it for win prediction. The project covers data cleaning, visualization, and machine learning model development to predict election outcomes.

## Data

The dataset used in this project contains information about Members of Lok Sabha, including attributes such as name, state, constituency, winner status, party symbol, gender, criminal cases, age, category, education, assets, liabilities, and total electors in the constituency.

### Data Cleaning

We handled missing values, formatted data, and ensured data consistency to prepare it for analysis.

## Data Analysis and Visualization

We conducted various analyses and created visualizations to gain insights into the dataset:

- Analysis of seats contested and won by each political party.
- Gender-wise election outcomes.
- Educational qualifications of candidates.
- Age group distribution of candidates.
- Politician category analysis (General, Scheduled Caste, and Scheduled Tribe).
- Assets vs. Liabilities analysis.
- Criminal cases analysis by party.
- State-wise criminal background analysis.
- Voting percentage analysis state-wise.
- Winners with and without criminal cases.

## Machine Learning Models

We developed machine learning models, including Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Decision Tree, to predict election winners. The Random Forest classifier achieved an accuracy of 89.66%.

## Repository Structure

- `data/`: Contains the dataset used in the project.
- `notebooks/`: Jupyter notebooks for data cleaning, analysis, and modeling.
- `scripts/`: Python scripts for specific tasks.
- `visualizations/`: Images and plots generated during data analysis.

## How to Use

1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Explore the Jupyter notebooks in the `notebooks/` directory for detailed analysis and modeling steps.

## Contributors

- [Jitendra Kumar]: Project Lead and Data Analyst,Data Cleaning and Preprocessing

- [Siddharth Chouskey]: Machine Learning Model Development,Data Visualization and Interpretation


## Acknowledgments

- Inspiration and guidance from [https://www.bits-pilani.ac.in/hyderabad/dipanjan-chakraborty/].


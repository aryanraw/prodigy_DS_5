
# Prodigy Data Science Internship Task 5

This repository contains the code and data for Task 5 completed as part of the Prodigy InfoTech Data Science Internship.

## Task Description

"Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors."

## Dataset

The dataset used for analysis is the "RTA Dataset.csv" file located in the `/data set` directory. This dataset contains information about various aspects of road traffic accidents.

## Code Overview

- **Data Loading and Exploration**: The dataset is loaded using pandas, and basic exploration is performed to understand its structure and characteristics.
- **Data Cleaning**: Missing values are handled, and unnecessary columns are dropped to prepare the data for analysis.
- **Exploratory Data Analysis (EDA)**: EDA techniques such as histograms, count plots, and heatmaps are used to visualize relationships between variables and identify patterns.
- **Feature Engineering**: Categorical variables are encoded using label encoding and one-hot encoding techniques.
- **Feature Selection**: Chi-squared tests are used to select significant features for predicting accident severity.
- **Model Preparation**: The dataset is split into input features (X) and target variable (y) for model training and evaluation.
- **Visualization**: The distribution of accident severity is visualized using a count plot.

## Repository Structure

- **/data set**: Contains the dataset used for analysis.
- **/code**: Contains the Jupyter Notebook or Python script with the code for Task 5.
- **README.md**: This file providing an overview of the repository.

## Usage

To replicate the analysis:

1. Clone this repository to your local machine.
2. Navigate to the `/code` directory.
3. Run the Jupyter Notebook or Python script.

## Dependencies

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

## Contributors

- [aryanraw](https://github.com/aryanraw)

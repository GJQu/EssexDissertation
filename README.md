# Health Types and Labour Market Outcomes: An Economic Analysis

## Overview

This repository contains the code and analysis for an MSc Economics dissertation that explores the relationship between chronic illness and labour market outcomes. Using unsupervised machine learning techniques on the UK Household Longitudinal Study (UKHLS) data, this project identifies distinct health types and examines their impact on employment, earnings, and education.

## Key Features

- Identification of three distinct health types using K-means clustering
- Analysis of frailty trajectories across different health types
- Examination of employment dynamics and earnings across health types
- Investigation of the predictive power of health types for frailty and labour market outcomes

## Technologies Used

- Python
- Scikit-learn (for K-means clustering)
- Pandas (for data manipulation)
- Matplotlib and Seaborn (for data visualization)
- StatsModels (for regression analysis)

## Data Source

The primary data source for this project is the Understanding Society: UK Household Longitudinal Study (UKHLS).

## Setup and Installation

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Download the UKHLS dataset (not included in this repository due to size and licensing)
4. Update the data path in the configuration file

## Usage

1. Run the data preprocessing notebook:
   ```
   code frailty_main.ipynb
   ```
2. Execute the clustering analysis:
   ```
   code k_means.ipynb
   ```

## Results

The analysis reveals three distinct health types:
1. "Resilient Health Type" (Type I)
2. "Early Onset Frailty Type" (Type II)
3. "Accelerated Decline Type" (Type III)

These health types show significant associations with employment rates, earnings, and educational attainment.

## Future Work

- Incorporate biomarkers and genetic data for deeper analysis
- Explore longitudinal transitions between health types
- Investigate the interplay between occupation types and health trajectories

## Author

Gavin J. Qu

## Acknowledgments

Special thanks to Dr. David Zentler-Munro for guidance and advice throughout this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

# Time Series Analysis for Home Ownership Rate Prediction

## Overview

The Time Series Analysis component focuses on understanding homeownership trends across various states in the United States. The primary goals were to train a sophisticated time series prediction model and detect outlier states displaying significant deviations from the national homeownership rate.

## Project Details

### Data Collection and Preparation
The project initiated with extensive data collection efforts. We acquired datasets from various sources, mainly in tabular format, spanning the years 1985 to 2021. Using tools such as Excel and the Pandas library, the data underwent thorough preprocessing, including data cleaning, format standardization, and removal of missing values. The datasets were transformed to align with the requirements of the Prophet time series prediction model.

### Time Series Modeling with Prophet
The time series prediction model, Prophet, was employed due to its ability to account for seasonality, making it suitable for predicting changes in homeownership rates influenced by various factors, including economic policies and presidential cycles.

The project primarily focused on plotting homeownership rates of different states against the national rate and detecting states with notable deviations from the overall trend. The analysis uncovered intriguing trends in various regions, such as the West Coast, Midwest, Southern States, and the East Coast. Additionally, confidence intervals were generated, aiding in plotting future projections.

## Contents

This repository includes:
- Jupyter Notebooks and Python scripts used for data preprocessing, cleaning, and modeling.
- Charts and visualizations showcasing homeownership rates across different states and their comparisons.
- Detailed documentation providing insights and findings from the analysis.

## Key Findings

The analysis revealed significant variations in homeownership rates across states, showcasing diverse trends. Notable observations include:
- West Coast states demonstrating close proximity to the national rate with exceptions such as Idaho and California.
- Trends indicating higher homeownership in the Midwest compared to other regions.
- Clear divides in homeownership trends among Southern states.

## Impact on the Project

The Time Series Analysis segment contributes significantly to the broader Home Ownership Constraints Project by providing comprehensive insights into the trends and patterns of homeownership rates. The findings set the stage for anomaly detection and further analysis, while the structured pipeline allows for efficient chart generation at various levels.

## Result Charts

### 1. West Cost
![1](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/c8b97899-821a-4c83-ad60-38fbc3e52e29)

### 2. Mid-West
![2](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/988fbdd0-eb28-4c12-84a5-c15cfc210ae2)


### 3. Southern States
![3](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/66e86c37-d64b-48fc-877a-7283b672034a)


### 4. East Coast
![4](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/19df7d62-00ce-466d-a61f-2be5c9653223)


### 5. Lowest Homeownership rate state vs neighbors
![5](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/f6b3aefb-2a2a-4939-a820-41348715dabc)


### 6. Highest Homeownership rate state vs neighbors
![6](https://github.com/ajinkya98/Home-Ownership-Rate-Prediction/assets/32778343/54ad5772-d8c5-4e40-bf90-a9f45e35c053)


## Conclusion

The Time Series Analysis effort has provided valuable insights into the complexities of homeownership trends across the United States. Through a robust predictive modeling approach and detailed visualization, the project has laid a strong foundation for policymakers, real estate investors, and researchers to make informed decisions related to the housing market.

This repository serves as a valuable resource for understanding time series analysis within the context of the broader Home Ownership Constraints Project.

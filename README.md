# Caffeine-effects-and-analysis-along-with-a-Rule-Based-model
# Caffeine Consumption and Sleep Cycle Analysis
# Relative t-test for hypothesis testing

This repository contains Python code for analyzing the relationship between caffeine consumption and its effects on sleep patterns. The code primarily utilizes Pandas for data handling, Matplotlib for visualization, and SciPy for statistical analysis.

## Prerequisites

To run this code, ensure you have the following dependencies installed:

- Python (>=3.0)
- Pandas
- Matplotlib
- SciPy

Install the required packages using pip:

```bash
pip install pandas matplotlib scipy
```

## Overview

The code is structured into several sections:

1. **Data Loading and Preprocessing:** 
   - Imports an Excel file containing responses on caffeine consumption and sleep quality.
   - Performs data cleaning and prepares the data for analysis.

2. **Hypothesis Testing (T-Test):**
   - Conducts a paired T-test to explore the relationship between caffeine consumption and sleep quality.
   
3. **Data Visualization:**
   - Generates various graphs to visualize the distribution and patterns of sleep quality based on different factors such as age, gender, and caffeine intake.

4. **Rule-Based Model:**
   - Implements a simple rule-based model for predicting sleep quality based on caffeine consumption, stress level, screen time, and sleep schedule.

## Usage

1. **Data Preparation:**
   - Ensure the data file (`V Caffeine consumption and it's effect on sleep cycle. (Responses).xlsx`) is placed in the same directory as the Python script.

2. **Run the Code:**
   - Execute the Python script to perform analysis and visualization. (Notebook or Python environment)

3. **Interpretation:**
   - Interpret the results obtained from the T-test and visualizations to understand the impact of caffeine consumption on sleep quality.

4. **Rule-Based Model:**
   - Use the provided script to input personal factors (caffeine consumption, stress, screen time, sleep schedule) and predict sleep quality based on a rule-based system.

## Files

- `Data_Manipulation_and_Hypothesis_testing_and_Rule_Based_model.ipynb`: Python script containing the code for analysis.
- `V Caffeine consumption and it's effect on sleep cycle. (Responses).xlsx`: Input data file.

## Important Notes

- Ensure the file paths are correctly set to read the input data.
- Adjust the code according to specific requirements or additional analyses.
- Results and interpretations may vary based on the dataset and individual circumstances.

## Acknowledgments

This analysis is for educational purposes and does not constitute professional advice. Please consult a healthcare professional for personalized guidance on sleep and caffeine consumption.

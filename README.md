
# Demographic Data Analyzer

A freeCodeCamp Data Analysis with Python project.

## What it does

The `calculate_demographic_data()` function in `demographic_data_analyzer.py`
uses Pandas to analyze 1994 Census data (`adult.data.csv`) and answers:

- How many people of each race are in the dataset
- The average age of men
- The percentage of people with a Bachelor's degree
- The percentage with and without advanced education (Bachelors, Masters,
  Doctorate) who earn more than 50K
- The minimum number of hours worked per week
- The percentage of minimum-hours workers who earn more than 50K
- The country with the highest percentage of people earning more than 50K
- The most popular occupation for >50K earners in India

All decimals are rounded to the nearest tenth.

## Run

    python main.py

This prints the answers and runs the unit tests in `test_module.py`.

## Requirements

- Python 3
- Pandas (`python -m pip install pandas`)

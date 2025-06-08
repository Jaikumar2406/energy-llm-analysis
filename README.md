# LLM-Based Code Generation on Energy Dataset

JAI KUMAR

## LLM Used
Groq API with llama3-70b-8192b model

## Summary

This project demonstrates using Large Language Models (LLMs) to generate Python code for analyzing household power consumption data. The dataset comes from the UCI Machine Learning Repository and contains measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years.

## Tasks Completed

1. Calculated average active power consumption in March 2007
2. Identified the hour with highest power usage on Christmas 2006
3. Compared energy usage between weekdays and weekends
4. Found days where energy consumption exceeded 5 kWh
5. Plotted energy usage trend for the first week of January 2007
6. Calculated average voltage for each day of the first week of February 2007
7. Analyzed correlation between global active power and sub-metering values

## Repository Structure

- `Untitled.ipynb`: Jupyter notebook containing all queries and visualizations
- `household_power_consumption.txt`: The dataset file
- `README.md`: This documentation file

## How to Run

1. Clone this repository
2. Install required packages: `pip install pandas matplotlib seaborn jupyter`
3. Launch Jupyter Notebook: `jupyter notebook`
4. Open and run `Untitled.ipynb`

## Results

All queries were successfully implemented and verified for correctness. The notebook includes both the analysis code and visualizations for each query.

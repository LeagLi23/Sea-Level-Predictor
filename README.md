# 🌊 Sea Level Predictor

Final project of the **Data Analysis with Python** certification by freeCodeCamp.

## 📌 Description

This project analyzes historical sea level data from 1880 to present and predicts future levels up to the year 2050 using linear regression.

## 🔍 Key Features

- Loads and plots CSIRO Adjusted Sea Level data from `epa-sea-level.csv`
- Plots scatter of observed data
- Creates two lines of best fit:
  - From 1880 through 2050 (historical + future trend)
  - From 2000 through 2050 (recent trend)
- Saves the figure as `sea_level_plot.png`

## 📂 Files

- `epa-sea-level.csv`: Dataset provided by FreeCodeCamp
- `sea_level_predictor.py`: Script to draw and save the plot
- `sea_level_plot.png`: Output graph

## 🧪 How to Run

```bash
python3 sea_level_predictor.py

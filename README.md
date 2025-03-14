# SkillCraft
SkillCraft tasks
# Titanic Data Cleaning & EDA

## Overview
This script cleans and analyzes the Titanic dataset.

## Steps
1. **Data Cleaning:**
   - Drop `Cabin` due to many missing values.
   - Fill `Age` with median, `Embarked` with mode.
   - Encode `Sex` (0: male, 1: female) and one-hot encode `Embarked`.

2. **EDA Visualizations:**
   - Age distribution
   - Survival count
   - Survival by gender
   - Age vs survival
   - Correlation heatmap

## Output
- Cleaned dataset saved as `cleaned_titanic.csv`.

## Requirements
- Python 3.x
- Pandas, Matplotlib, Seaborn (`pip install pandas matplotlib seaborn`)

## Usage
Run:
```bash
python script_name.py
```



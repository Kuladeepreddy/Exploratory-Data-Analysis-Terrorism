# Terrorism Data Analysis

## Introduction

This project involves the analysis of terrorism-related data from the Global Terrorism Database (GTD). The dataset includes information on terrorist attacks worldwide, covering aspects such as the year, month, day, country, region, city, latitude, longitude, attack type, casualties, target, group responsible, and more. The analysis aims to provide insights into patterns, trends, and characteristics of terrorist activities.

## Data Overview

The original dataset contains 181,691 entries with 135 columns. After renaming and selecting relevant columns, the cleaned dataset consists of 46,556 entries and 18 columns. Missing values are handled by dropping corresponding rows.

## Data Analysis

### General Insights

- The country with the most attacks: Iraq
- The city with the most attacks: Unknown
- The region with the most attacks: South Asia
- The year with the most attacks: 2011
- The group with the most attacks: Taliban
- The most common attack type: Bombing/Explosion


### Top Countries and Groups

- Top 10 countries with the highest number of activities:
  - Iraq, India, Pakistan, Afghanistan, Philippines, Thailand, Russia, United States, Colombia, Algeria.

- Top 10 groups with the most activities:
  - Unknown, Taliban, CPI-Maoist, FARC, NPA, TTP, ISIL, Maoists, Al-Shabaab, LTTE.

### Types of Attacks and Casualties

- Most common attack type: Bombing/Explosion.
- Total number of people killed in terror attacks: 112,679.
### Visualizations

1. **Attacks Over the Years:**
   - A bar chart depicting the number of attacks each year.

2. **Top Countries Affected:**
   - A bar chart showcasing the top 10 countries with the highest number of terrorist activities.

3. **Groups with Most Activities:**
   - A bar chart displaying the top 10 groups with the most terrorist activities.

4. **Types of Attacks Causing Deaths:**
   - A pie chart illustrating the types of terrorist attacks that caused deaths.

5. **Number of People Killed by Countries:**
   - Bar charts presenting the number of people killed in terrorist attacks for different sets of countries (top 50, 51-100, 101-150, 151-206).

## Files

- `Terrorism_dataset.csv`: The original dataset.
- `Analysis.ipynb`: Jupyter Notebook containing the code and analysis.
- `README.md`: Documentation providing an overview of the project.

## Acknowledgments

- The dataset used in this analysis is sourced from the Global Terrorism Database (GTD).

## License

This project is licensed under the [MIT License](LICENSE).


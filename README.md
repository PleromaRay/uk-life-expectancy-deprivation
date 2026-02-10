# UK Life Expectancy and Deprivation Analysis: Exploring Health Inequalities by Sex


## Project Overview
This repository analyzes the relationship between **life expectancy at birth** (males and females) and area-level **deprivation** in the UK, using Python for data cleaning, merging, visualization, and statistical exploration.

The project looks to highlights **social gradients in health**: people in more deprived areas live shorter lives, with males often experiencing wider absolute gaps than females — a persistent inequality documented in UK public health policylike the Marmot Review

**PROJECT VISUALIZATION - Life expectancy line plot [Male vs Female]
<img width="996" height="547" alt="image" src="https://github.com/user-attachments/assets/6aa1cf4e-67ce-4a66-b381-198d637c877b" />
 - Survivorship line plot
 <img width="1031" height="547" alt="image" src="https://github.com/user-attachments/assets/fd859ece-5d43-4855-8b21-4b9c9a1b2cff" />



**Key national insights** (from ONS 2022–2024 data):  
- Male life expectancy at birth: ~79.4 years  
- Female life expectancy at birth: ~83.3 years  
- Female-male gap: ~3.9 years  
- In the most deprived areas, **LE** drops/rises to_________ (males) and________________ (females), with gaps widening significantly compared to the least deprived areas.

This repo demonstrates end-to-end public health data science: handling messy public datasets (side-by-side male/female life tables, deprivation scores), modular code structure, reproducible workflows, and equity-focused insights.

## Features & Skills Demonstrated
- **Data Sources**:
  - Life expectancy: ONS National Life Tables (2022–2024) – full abridged life tables by age/sex (mx, qx, lx, dx, ex)
  - Deprivation: English Indices of Multiple Deprivation (IMD) scores at local authority level (sample includes high-deprivation areas like Middlesbrough ~40, Hartlepool ~37.6)
- **Python Libraries Used**:
  - pandas & numpy → data loading, cleaning, merging, type conversion
  - matplotlib & seaborn → visualisations (scatter, boxplots, line plots for survival/LE curves)
  - scipy & statsmodels → correlations, t-tests, regression
- **Workflow Highlights**:
  - Parsing wide CSV layouts (males columns 0–6, females 8–13, blank separator)
  - Removing header-as-data rows, forcing numeric types
  - Combining male/female into long format
  - Descriptive stats (gaps by sex), visualisations, potential future regression/interaction models
- **Reproducible & Modular**:
  - Notebooks for step-by-step exploration
  - src/ folder for reusable functions
  - requirements.txt + virtual env setup

## Key Findings (Would be updated from time-to-time)
- National female-male life expectancy gap at birth: ~3.9 years (females longer)
- 

# Exploratory Data Analysis – mtcars Dataset

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on the classic `mtcars` dataset, which contains specifications and performance metrics for 32 automobiles (1973–74 models).  
The goal is to uncover **statistical insights**, **relationships**, and **trends** between car features such as fuel efficiency, engine size, weight, horsepower, and transmission type.

## Dataset
**Columns:**
- `mpg`: Miles per gallon
- `cyl`: Number of cylinders
- `disp`: Displacement (cu.in.)
- `hp`: Horsepower
- `drat`: Rear axle ratio
- `wt`: Weight (1000 lbs)
- `qsec`: 1/4 mile time
- `vs`: Engine type (0 = V-shaped, 1 = straight)
- `am`: Transmission (0 = automatic, 1 = manual)
- `gear`: Number of forward gears
- `carb`: Number of carburetors

## Tools Used
- **Python** (Pandas, NumPy)
- **Matplotlib** & **Seaborn** for visualization
- Jupyter Notebook for step-by-step exploration

## Key Analysis Performed
- Data overview and cleaning
- Summary statistics (`.describe()`, `.info()`, `.value_counts()`)
- Univariate analysis (histograms, boxplots)
- Bivariate analysis (scatterplots, grouped summaries)
- Correlation heatmap & pairplot
- Identification of relationships and trends

## Findings Summary
- Fuel efficiency (`mpg`) shows **strong negative correlation** with `wt`, `disp`, and `hp`.
- **4-cylinder** and **manual transmission** cars generally have higher MPG.
- More cylinders and higher horsepower are linked to lower fuel efficiency.
- Dataset shows a trade-off between **performance** and **fuel economy**.



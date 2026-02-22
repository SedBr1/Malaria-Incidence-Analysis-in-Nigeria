##Malaria Incidence Analysis in Nigeria

# What this does
Analyses WHO malaria data (2000-2017) to examine trends and make baseline predictions for 2030.

# Key findings
- Strong negative correlation between year and incidence (r = -0.92)
- Linear model predicts ~XXX cases per 1000 by 2030
- BUT: This is a baseline only — real incidence depends on interventions

# Methods used
- Data cleaning
- Statistics: Pearson correlation, linear regression
- Validation: Train/test split (2000-2010 train, 2011-2017 test
-  Visualization: Matplotlib with trend line

# Limitations (important!)
- Linear model ignores seasonality and intervention effects
- No external predictors (rainfall, mosquito net distribution, etc.)
- Prediction uncertainty increases with time
  
# Files
- `malaria-analysis.ipynb` - Complete Jupyter notebook
- `incidence-of-malaria.csv` - Raw data from WHO
- `figures/` - Output plots

  # Acknowledgments
Data from WHO Global Health Observatory

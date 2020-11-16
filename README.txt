### Data ###
- "NG Consumption.csv": natural gas consumption data by sector; dataset dowloaded from "https://www.eia.gov/totalenergy/data/browser/csv.php?tbl=T04.03"
			and renamed as it is
- "df_ensembled.xls": dataset extracted from "NG Consumption.csv" with the code in "Data preparation.ipynb" 
		      and to be imported in Gretl; it contains the three required time series

### Programs ###
- "Data preparation.ipynb": jupyter notebook file where data are prepared for being imported in Gretl
- "gridsearch.inp": code which performs best order selection processes for ARIMA and VAR models
- "Model fitting and performance assessment.inp": code which fits ARIMA and VAR models with the best orders and computes performance measures


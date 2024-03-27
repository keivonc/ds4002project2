# DS4002 Project 2 – Predictive Climate Model: Using Data to Estimate Future Weather Patterns
## By: Nishita Cheekatamarla, Enmanuel Baez, Keivon Chamanara

## Overview

This repository contains all the source code, data, and outputs of this project. Different weather parameters across the United States over the years of 1895-2023 are analyzed in order to find trends and create a model to accurately predict future weather patterns.

## Software and Platform

For this project, a Jupyter notebook was used through Google Colaboratory, and the code was all in Python. The Python libraries/packages installed include: seasonal_decompose, LinearRegression, linear_model, r2_score, mean_squared_error, mean_absolute_error, statsmodels.api, stats. The platform used was a MacOS computer.

## Documentation Map

### /DATA

+ precipitation.csv
+ avgtemp.csv
+ maxtemp.csv
+ mintemp.csv
+ pdsi.csv
+ data_appendix.pdf

### /OUTPUT

+ avg_pdsi_june_over_time.png
+ avg_precip_june_over_time.png
+ avg_temp_june_over_time.png
+ pdsi_avg_temp.png
+ precip_avg_temp.png

### /SCRIPTS

+ Project2.ipynb
+ how-to-run-code.md

### LICENSE

### README.md

### presentation.pdf


## Results Reproduction

To reproduce the results...

1. Go to the 'SCRIPTS' folder in the repository and click on 'Project2.ipynb'.
2. In the banner directly above the Jupyter notebook, there will be a download button to the right that says "Download raw file" when you hover over it. Click on it to download the notebook.
3. The Jupyter notebook will download to your device and you can open it in any code editor of your choosing. We will use VSCode for this example but other code editors work.
4. Once you open the project in VSCode (or the code editor of your choosing), there will be a button at the top that says "Run All". Click on it.
5. First, the import packages code block will run. If there is any library/package that you do not have installed, an error will show. To fix this, simply type "pip install [name of missing library/package]" in your command line interface. For Mac users this would just be in Terminal.
6. Then, you can go back to your code editor and press "Run All" again. The code will run as expected and all the graphs and modified dataframes will appear for your observation.


## References

[1] NOAA National Centers for Environmental Information, "Climate at a Glance: Time Series," [Online]. Available: https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/national/time-series.  [Accessed: March 14, 2024]

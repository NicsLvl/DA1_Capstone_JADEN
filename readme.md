# Project Description

This project is a capstone group project that aims to provide market research for WOW!, a clean energy private equity firm based in Chicago. The objective is to assess the U.S. wind turbine market and determine whether WOW! should invest in this market and who they should approach to fund the investment.

The project will utilize the data analytics workflow within an agile development framework to transform data into useful information to support business decisions. The team will have three days to work on the project and will submit one version of all files used.

# Scenario

WOW! has been investing in U.S. hydropower and is now considering investing in U.S. wind power. The team of data analysts is being formed to assess the U.S. wind turbine market in a short turnaround. The team needs to present its findings to the investment committee in time for their quarterly investment decisions.

# Learning Objectives

Conduct market research on opportunities for WOW! in the U.S. wind turbine market
Utilize the data analytics workflow within an agile development framework
Transform data into useful information to help support business decisions
Gain experience with project management and associated tools

# Data
All the data be found in the data folder. We will use the latest datasets available which is up till 2021. The project will use the following data:
- [EIA schedule 860](https://www.eia.gov/electricity/data/eia860/): eia860_num_wt_Y2021.xlsx
- [EIA schedule 923](https://www.eia.gov/electricity/data/eia923/): 
1. EIA923_Schedules_2_3_4_5_M_12_2021_Final_Revision.xlsx
2. EIA923_Schedules_2_3_4_5_M_12_2020_Final_Revision.xlsx
3. EIA923_Schedules_2_3_4_5_M_12_2019_Final_Revision.xlsx
4. EIA923_Schedules_2_3_4_5_M_12_2018_Final_Revision.xlsx
5. EIA923_Schedules_2_3_4_5_M_12_2017_Final_Revision.xlsx
6. EIA923_Schedules_2_3_4_5_M_12_2016_Final_Revision.xlsx
7. EIA923_Schedules_2_3_4_5_M_12_2015_Final_Revision.xlsx
8. EIA923_Schedules_2_3_4_5_M_12_2014_Final_Revision.xlsx
9. EIA923_Schedules_2_3_4_5_M_12_2013_Final_Revision.xlsx
10. EIA923_Schedules_2_3_4_5_M_12_2012_Final_Revision.xlsx
- [US Wind Turbine Database](https://eerscmap.usgs.gov/uswtdb/): uswtdb_v5_0_20220427.csv
- Extra research files can be found in the research folder

# Notebooks Used
You should run these in this order:
- wind_turbine_dataset_rename.ipynb: Renaming the column names in the data files
- windturbine_datadictionary.ipynb: Updated the data dictionary based on the site description
- 10_year_data_prep_EIA860.ipynb: Cleaning the data for EIA860 Schedules
- 10_year_data_prep_EIA923.ipynb: Cleaning the data for EIA923 Schedules
- Feature Engineering.ipynb: Creating new features based on the data prep done
- sarima_forecast.ipynb: Sarima forecasting model performed on the wind market
- Model_wind_turbine.ipynb: The clustering analysis performed on the wind plants

# Visualizations Made
Cluster_Visual.twbx

# Presentation File
JADEN PRESENTATION_21MAR.pptx
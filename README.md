# sharp-tailed-grouse-sdm
A model for predicting sharp-tailed grouse distributions in Alberta 

Principle Investigators: 
- Dr. Erin M. Bayne
  Professor, Department of Biological Sciences 
  University of Alberta 
  1-275 Centennial Ctr For Interdisciplinary SCS II 
  11335 Saskatchewan Drive NW
  Edmonton, AB, T6G 2H5, Canada 
  bayne@ualberta.ca
  
- Dr. Scott E. Nielsen 
  Professor, Department of Renewable Resources 
  University of Alberta
  751 General Services Building, 
  9007 116 St NW, 
  Edmonton, AB, T6G 2H1, Canada
  scottn@ualberta.ca
  
Corresponding Investigator
- Dr. Andrew D. Crosby
  Research Associate, Department of Renewable Resources
  University of Alberta
  751 General Services Building, 
  9007 116 St NW, 
  Edmonton, AB, T6G 2H1, Canada
  crosby@ualberta.ca

Folder Structure: 
0_data # All data (or links to data) used in the analysis 
  /processed 
    /rasters
	/shapefiles 
  /raw 
    /rasters
	/shapefiles 

1_scripts # R scripts (or descriptions of other methods) used in data processing and analysis
  /functions # R functions specific to this analysis 
  /model-scripts # Bayesian models for data analysis 

2_pipeline 
  /store # Outputs of the analysis to be stored for long term use 
  /temp # Temporary outputs that may be deleted 

3_outputs # Final outputs for use in reporting 
  /figures 
  /maps
  /tables

4_reports # Files used in creating manuscripts, reports, and presentations

5_documentation # Files for creating bookdown documents that describe the analysis


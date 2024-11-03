# kriging-pH

This repository contains resources and scripts related to the spatial analysis of soil pH across the contiguous United States (CONUS) using machine learning and geostatistical methods. Below is an overview of the files included:
- **`rf.ipynb`**: Jupyter Notebook containing a Random Forest classification of rasters to predict soil pH levels across CONUS.
- **`DensityVsErrorFinal.ipynb`**: Jupyter Notebook detailing an ArcGIS Pro workflow to assess the impact of sample point density on error in Empirical Bayesian Kriging (EBK) analysis.
- **`presentation_82 (1).pdf`**: Presentation from the Summer 2024 Environmental Defense Fund Intern Symposium summarizing findings related to this project.
- **Kriging pH map**: The final map generated from `rf.ipynb`, to be included in an upcoming publication.  
  ![final_rf_map_tight](https://github.com/user-attachments/assets/67d64f7f-b46e-4642-9f99-9e80dd07e049)

### Description
This project focuses on utilizing Random Forest models and Empirical Bayesian Kriging (EBK) to analyze and predict soil pH variations across different regions of the United States. The work aims to provide insights into regions (at the county-level) with higher potential for enhanced weathering deployments based on soil pH. 

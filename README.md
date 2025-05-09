# ML_Final
Welcome to my Machine Learning Final Project!ThisThe project uses unsupervised machine learning to differentiate between routine and conflict-associated vegetation fires in Northern Syria from 2017 to 2022. Anomaly detection was performed using an Isolation Forest model applied to VIIRS fire count data, and clustering was conducted using HDBSCAN on environmental and conflict-related features. The results show that most anomalies are driven by a combination of environmental and conflict-related factors, with directly conflict-related fires appear consistently but remain spatially and temporally irregular. A rule-based baseline was included to assess the added value of machine learning.

You can find all of my code that I used for this project attached to the repository.  Geometry has the code I used to create the grid and geometry in Google Earth Engine. NDVI_Code has the code I used to get environmental data on GEE. Workflow_data has the R code I used to ingest and make my singular dataset. Then, ML_Workflow has the code that I used for the machine-learning and modeling component of the project. 

If you wanted, you could replicate the analysis. Here's where I got the data:
1. VIIRS Fire Detections: GEE dataset NOAA/VIIRS/001/VNP14IMGTDL_NRT
2. MODIS NDVI: GEE dataset MOD13Q1
3. CHIRPS Precipitation: GEE dataset UCSB-CHG/CHIRPS/DAILY
4. ACLED Conflict Data: Available via ACLED’s Export Tool
4. GAUL Boundaries: GEE dataset FAO/GAUL/2015

You can also see the very nice and fancy report I wrote at writtenreport.pdf :)

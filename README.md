# Land-Use-and-Land-Cover-Classification
# Overview
This project addresses the challenge of mapping and classifying land use and land cover (LULC) by leveraging satellite imagery and employing machine learning algorithms. The solution categorizes the landscape into various land cover types including PermanentCrop, Forest, SeaLake, River, AnnualCrop, Industrial, HerbaceousVegetation, Pasture, Residential, and Highway.

# Objective
The objective of this project is to provide a systematic and scalable method for environmental monitoring, urban planning, and agricultural management through accurate land use and land cover classification.

# Dataset
The dataset utilized for this project is EuroSAT, a comprehensive land use and land cover classification dataset derived from Sentinel-2 satellite imagery. It comprises 27,000 labeled and geo-referenced images across 10 distinct land use and land cover (LULC) classes.


# Data Processing
The process involves iterating through class folders in the EuroSAT dataset, extracting spectral bands from .tif files using rasterio for satellite imagery data processing. A Pandas DataFrame is constructed where rows correspond to image samples and columns represent spectral bands and target labels, facilitating machine learning model training.

# Machine Learning Approach
A Random Forest Classifier is employed to learn patterns in spectral features extracted from satellite imagery. The model achieved an accuracy score of 82.04% on the test set, demonstrating its ability to generalize well to new data and effectively classify land use and land cover categories.

# References
EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification. '[Download the dataset here] (https://zenodo.org/records/7711810#.ZAm3k-zMKEA)'

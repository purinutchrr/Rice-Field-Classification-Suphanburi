# Rice Field Classification Project: Suphan Buri (2021)

![Library](https://img.shields.io/badge/Library-Geopandas%20%7C%20GEE%20%7C%20Sklearn-orange)

## Project Overview
This project classifies **Rice Field** areas in Mueang District, Suphan Buri Province, utilizing **Sentinel-2** satellite imagery and **Machine Learning**. By analyzing the temporal **NDVI** signature, we can accurately distinguish rice crops from other land use types.

## Tech Stack & Workflow
1. **Spatial Preprocessing:** Managed Land Use Shapefiles (LDD) and coordinate systems using `Geopandas`.
2. **Feature Engineering (GEE):** Extracted monthly NDVI time-series data via **Google Earth Engine**.
3. **Modeling:** Trained a **Random Forest Classifier** with Hyperparameter Tuning (`RandomizedSearchCV`).
4. **Evaluation:** Achieved **80.43% Accuracy** with detailed analysis using Confusion Matrix and Feature Importance.

## Repository Structure
* `Rice_Field_Classification_Suphanburi.ipynb`: The main notebook containing the end-to-end analysis.
* `Suphan_NDVI_Dataset.csv`: Processed dataset extracted from GEE.
* `Landuse_Suphanburi.zip`: Zipped Shapefiles for spatial analysis.
* `requirements.txt`: List of dependencies.

## How to Run
1. Clone this repository.
2. Install libraries: `pip install -r requirements.txt`
3. Open the Jupyter Notebook.

---
**Author:** Purinut Chairungrueang  

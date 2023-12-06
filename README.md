# House Rent Clustering Analysis
CIS 430

## Introduction
This repository contains Python code for analyzing house rent data using K-Means clustering. The purpose of this project is to group similar rent properties based on their size and rent price, providing a detailed visualization of rental trends across various cities.

## Dataset
The dataset used is `House_Rent_Dataset.csv`, which should contain at least two columns: `Size` and `Rent`, alongside a `City` column. Each row represents a unique rental property.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

## Installation
To run this analysis, ensure that you have the required libraries installed. You can install them using pip:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Usage
1. Load your dataset in CSV format as `House_Rent_Dataset.csv`.
2. Run the script to perform the clustering analysis.
3. The script will output a series of scatter plots, one for each city in the dataset. Each plot will be shown as a subplot and shows the clustering of rental properties based on their size and rent.

## Code Overview
- The data is loaded from `House_Rent_Dataset.csv` using pandas.
- The dataset is split based on unique cities.
- K-Means clustering is performed separately for each city using the `Size` and `Rent` columns.
- The clusters and their centroids are visualized using scatter plots with seaborn and matplotlib.

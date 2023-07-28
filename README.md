# Design of Experiment ML
This repository features a Demonstration of a basic Machine Learning framework for supervised tasks.
The framework is based on the CRISP-DM methodology and is implemented in Jupyter Notebook environment.

## Usage
The framework is implemented in Jupyter Notebook environment. The notebook is divided into 5 sections, each corresponding to a step in the CRISP-DM methodology. The sections are:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation

## Data
The data used in this notebook is the [Banknote Authentication Data Set](https://archive.ics.uci.edu/ml/datasets/banknote+authentication) from the UCI Machine Learning Repository. The data contains 1372 observations of 5 variables. The variables are:
* variance of Wavelet Transformed image (continuous)
* skewness of Wavelet Transformed image (continuous)
* curtosis of Wavelet Transformed image (continuous)
* entropy of image (continuous)
* class (integer)

## Requirements
The notebook is implemented in Python 3.11. The following libraries are required:
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* imblearn
* xgboost
* scipy
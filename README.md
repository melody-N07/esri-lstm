# Esri-LSTM Project
This repo is a documentation for GPS Tech Team's work on Esri's GIS event sequence data. The goal is to get a working predictor for the 1.46GB dataset. 

The Repo includes following components:
### Datasets:
1. Original datasets provided by Esri
2. Preprocessed 5-item and 10-item dataset for training

### Notebooks:
1. Notebook to preprocess the dataset and get n-item sequence
2. Notebook to downsize categorical features, perform EDA, and train LSTM model
3. Notebook to submit machine learning training job to cluster

### Code:
1. Pipeline for training in Azure Machine Learning Studio, with custom metric logs

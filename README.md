# Naive-Bayes-KNN-Decision-Tree

# Food Delivery Time Prediction

## Overview
This project predicts whether food deliveries will be "Fast" or "Delayed" using machine learning models. It analyzes factors like distance, weather, traffic, and delivery person experience.

## Features
- Data preprocessing with feature engineering
- Three classification models:
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Decision Tree
- Model evaluation and comparison
- Visualization of results

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation
1. Clone the repository
2. Install requirements:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the Jupyter notebook:
```bash
jupyter notebook Food_Delivery_Prediction.ipynb
```
2. Execute cells sequentially

## Results
The best performing model will be displayed with evaluation metrics including:
- Accuracy
- F1 Score
- Confusion Matrix
- ROC Curve

## Files
- `Food_Delivery_Prediction.ipynb`: Main notebook with code
- `Food_Delivery_Time_Prediction.csv`: Dataset
- `README.md`: This file

## Note
The dataset should be placed in the same directory as the notebook. Adjust the threshold for "Fast"/"Delayed" classification as needed.

# chicken-vocalizations

This project focuses on signal processing and multiclass classification. Audio recordings from industrial chicken coops were manually labeled, and a Sagemaker XGBoost classifier was trained on the labeled data to classify the different types of chicken vocalization. The classifier was then used to predict a separate set of audio data, and the predicted labels were used in a vector autoregression model to predict mortality. For a report containing data, methods, and conclusions, please see https://github.com/DKHowell/chicken-vocalizations/blob/main/Poultry_Vocalization_Report.pdf

## Files

1. [Sagemaker notebook](https://github.com/DKHowell/chicken-vocalizations/blob/main/Poultry_Audio_Classifier.ipynb) including feature engineering, training and tuning classifier, and predicting vocalizations
2. [Sagemaker notebook](https://github.com/DKHowell/chicken-vocalizations/blob/main/VAR_Mortality.ipynb) for data visualization and VAR model 
3. [Final report](https://github.com/DKHowell/nfl-formation-clustering/blob/main/NFL_Clustering_Report.pdf)

### Executing program

This project was completed using proprietary data and modules within Amazon Sagemaker, and therefore cannot be reproduced.

# Crop-Yield-Prediction-Using-KNN-Classification 
The crop output is predicted using historical climate, soil, and fertiliser data using the suggested KNN classification-based model. The model is based on the following step.    
Step1:The historical data for soil,climate and fertilizer information is gathered and preprocessed.To get rid of outliers and inconsistiencies,the data is cleaned and normalized. 
Step 2: Feature Extraction - From the preprocessed data, the pertinent features are extracted. The characteristics include soil pH, soil nutrients, soil pH, soil use of fertiliser, and rainfall. 
Step 3: KNN Classification - To forecast crop yield, the collected features are subjected to the KNN classification method. The method determines a new data point's K nearest neighbours and classifies it according to the majority of those neighbours. 
Step 4: Model Evaluation - Using a variety of evaluation criteria, including accuracy, precision, recall, and F1-score, the performance of the proposed model is assessed.

By using KNN model the dataset is divided into 75% of training data and 25% of testing data to predict the crop yield production. In this module, rainfall water data set is taken for Indian data for past ten years. The data is converted into data frame and pre-processed such that zero values in all columns records are eliminated.
The methodology for crop yield prediction using KNN classification can be broken down into several steps:

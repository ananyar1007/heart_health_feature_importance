# heart_health_feature_importance
The first file is the dataset (cardio_train.csv). 
The second file (DataPreprocessing) takes in the cardio_train.csv file. It preprocesses the data and removes outliers, writing the modified data into "cardio_train_filtered.csv". The file "cardio_train_not_normalized.csv" is also created before normalization and after outliers are removed. 
The third file (CardioTrainClassifiers) runs all the classifiers on the "cardio_train_filtered.csv" file. It also computes feature importance.
The fourth file (AgeAnalysis) uses the file "cardio_train_not_normalized.csv" to analyze how the risk for heart disease changes with age. 

### RAVDESS_data_analysis

ravdess_features.csv is a csv file containing a dataset originating from audio files containing short sentences spoken by 24 actors, 12 males and 12 females, and the emotion with which they are said. Each record in the dataset represents one of these audios, and has as features the characteristics of the audio.  

- In the notebook ravdess_data_preparation.ipynb we explore the dataset and perform data cleaning.
- In ravdess_clustering.ipynb we try different clustering algorithms and compare the results: DBSCAN, single linkage, complete linkage, average linkage, ward method, k-means, bisecting k-means.
- In ravdess_classification.ipynb we try different classification algorithms to try predict the variable "emotion": knn, decision tree, random forest.

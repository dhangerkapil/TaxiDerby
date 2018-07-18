## New York City Taxi Trip Duration

Kaggle playground to predict the total ride duration of taxi trips in New York City. 

### First part - Data exploration

### Second part - Clustering

### Third part - Cleaning and feature selection 
We have found some odd long trips : one day trip with a mean spead < 1km/h.   
We have removed these outliners.  
We also added features from the data available : Haversine distance, Manhattan distance, means for clusters, PCA for rotation.

### Forth part - Prediction
We compared Random Forest and XGBoost.  
Current Root Mean Squared Logarithmic error :


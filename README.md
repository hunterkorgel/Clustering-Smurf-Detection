# Clustering-Smurf-Detection
Applying clustering algorithms to detect smurf accounts in League of Legends Solo Queue ladder.
Mean-Shift identifies certain smurf accounts from a dimension-reduced feature space built on account-wide
aggregate performance statistics.

# Data Collection
Data is collected from the Riot Games API with a free public key.
Collection scripts can be found in 'Player_Clustering_Downloads.ipynb'.

# Data Processing
Once data has been downloaded in raw json format from the API, data is processed and added to the dataset.
Processing and dataset creation scripts can be found in 'Player_Clustering_Processing.ipynb'.

# Data Analysis
Once the dataset has been generated, it is ready for interpretation and cluster modeling.
Pandas and sklearn are used to prepare the data for modeling and run clustering algorithms.
Best clustering algorithm is selected for separating high-performance accounts from the rest of the league.
Analysis and modelign work can be found in 'Player_Clustering_Analysis.ipynb'.
Data analyzed can be found in 'SILVER_Jax's Dragons.csv'.

# Additional Data
Two additional datasets were created but not analyzed in this project. Future work can be done on these and
any future gathered data.

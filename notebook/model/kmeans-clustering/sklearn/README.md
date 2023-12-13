# Recommendation System Using KMeans Clustering (Sklearn)

## Technology Used :

- Python
- Jupyter Notebook

## Installed Packages

- sklearn
- numpy
- pandas
- matplotlib

## Architecture
- Data Understanding
    - Data Path
    - Read CSV to Pandas Dataframe
    - Data Exploration
- Data Preparation
    - Get Average Talents Rating
    - One Hot Encoding Categorical Data (Talent's tags)
    - Implement PCA on One Hot Encoded Data
- Modeling
    - Kmeans Clustering System Recomendation Model
    - Initializing Model
- Evaluation (Elbow Method)
    - Fitting Model (Cluster with Every K Possible to Find the Best K Value)
    - Find Kmeans Elbow Score
    - Training Model with Elbow Score
    - Get Cluster Items Count
    - Plot Clusters
- Prediction
    - One Hot Encoding User Tags
    - Show 7 Recommended Talents sorted by Average Rating
    
## How To Run / Install On Your Local Machine

Clone this repository
```bash
git clone https://github.com/heptavators/dataset-tags.git
```

Open this project 
```bash
cd notebook/model/kmeans-clustering/sklearn/cluster-kmeans-model.ipynb
```

Running this project

- Run Selected Cell on the Notebook

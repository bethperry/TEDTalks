# Summarizing TED Talks using KMeans Clustering

This notebook explores 2,550 TED Talks given between 1972 and 2017 (dataset available from Kaggle [here](https://www.kaggle.com/rounakbanik/ted-talks)), then builds several KMeans clustering models to group the talks according to their assigned tags.

The resulting clusters are visualized through word clouds to demonstrate: 
1. The criteria each model selected for dividing the talks 
2. The effect of varying the number of clusters in each model

The models are evaluated using the silhouette score.

  
## Files

**Notebook:** TEDTalks_EDA&KMeansModel

**Data:** Data\ted_main.csv


## Python Libraries Used

**Data Prep and Analysis**
- numpy
- pandas
- ast
- datetime

**Visualization**
- matplotlib
- seaborn
- wordcloud

**Modeling**
- scikit-learn
  - To prepare text as model input: TfidfVectorizer, normalize
  - To build and score the clustering model: Kmeans, silhouette score
- kneed (to calculate the "elbow point" of the clustering model)

  
## Credits

I found these resources particularly helpful in completing this analysis:

- [K-Means Clustering](https://towardsdatascience.com/k-means-clustering-8e1e64c1561c)
- [Unsupervised learning of TED talk categories](https://www.kaggle.com/mattchurgin/unsupervised-learning-of-ted-talk-categories)
- [Knee/Elbow Point Detection](https://www.kaggle.com/kevinarvai/knee-elbow-point-detection)
- [A Data Science point of view of TED Talks](https://www.kaggle.com/liberoliber/a-data-science-point-of-view-of-ted-talks#Summarizing-the-TED-Trascripts)

My notebook has reused some of the code and concepts from each of the links listed above.

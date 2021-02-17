# Summarizing TED Talks using KMeans Clustering
===============================================

This notebook explores the TED Talks dataset (available from Kaggle [here](https://www.kaggle.com/rounakbanik/ted-talks)), then builds several KMeans clustering models to group the talks according to their assigned tags. The resulting clusters are visualized through word clouds to demonstrate the criteria each model selected for dividing the talks.

### Files
---------

**Notebook**
- TEDTalks_EDA&KMeansModel

**Data**
- Data\ted_main.csv

### Python Libraries Used
-------------------------

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
- scikit-learn (KMeans, silhouette_score, TfidfVectorizer, normalize)
- kneed (for calculating the "elbow point" of the clustering model)


### Credits
-----------

I found these resources particularly helpful in completing this analysis:

- [K-Means Clustering](https://towardsdatascience.com/k-means-clustering-8e1e64c1561c)
- [Unsupervised learning of TED talk categories](https://www.kaggle.com/mattchurgin/unsupervised-learning-of-ted-talk-categories)
- [Knee/Elbow Point Detection](https://www.kaggle.com/kevinarvai/knee-elbow-point-detection)
- [A Data Science point of view of TED Talks](https://www.kaggle.com/liberoliber/a-data-science-point-of-view-of-ted-talks#Summarizing-the-TED-Trascripts)

My notebook has reused some of the code and concepts from each of the links listed above.
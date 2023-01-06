![Title](https://user-images.githubusercontent.com/112866030/210846064-c3e544e6-9e35-45f1-8a63-3e3602c3dca5.png)

# <p align=center> Unsupervised Machine Learning project 

## Project summary
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

## Problem statement
**This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.**

## 
![netflix project approach](https://user-images.githubusercontent.com/112866030/210844322-74b9331f-bcf8-4b24-b73a-25f97ae7c507.png)

## EDA insights:- Tableau dashboard
![Netflix Dashboard](https://user-images.githubusercontent.com/112866030/210847918-7b17fbfe-4534-43e6-b253-f9dce1706b78.png)
For interactive dashboard- [Click here](https://public.tableau.com/views/Netflixdasboard_16717379913640/NetflixDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)  (please select fullscreen option given at bottom right corner of dashboard for better experience. )

## Clustering
* K-means clustering
* Elbow curve 
* Density-based spatial clustering (DBSCAN)
* Hierarchial clustering
* Agglomerative clustering
* **Recommender System**- Cosine similarity
  
## Conclusion 
* EDA of data gave very valueable insights, which will help in bussiness impact:
  * TV-shows are better for audience retention.
  * Opportunities based on countries were explored.

* Clustering shows that K-means clustering is better for provided data.
  * Silhouette score was 0.45 for 4 clusters & 4.43 for 6 clusters.
  * We selected cluster of 6 to be ideal after reviewing ELBOW CURVE.
  * Cosine based recommender system is working as expected.
 

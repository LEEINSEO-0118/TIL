# Clustering
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-clustering-k-means-hierarchical-9fd9e3dc4e72)  
Clustering : Unsupervised Classification model, 비슷한 데이터끼리 묶어주는 것

## K-Means Clustering
![image](https://miro.medium.com/v2/resize:fit:720/format:webp/1*rw8IUza1dbffBhiA4i0GNQ.png)
source : https://towardsdatascience.com/k-means-a-complete-introduction-1702af9cd8c
* 대표적인 클러스터링 방법
* 평균을 기준으로 데이터들을 묶어주는 것
* 각 클러스터와 데이터 간의 거리를 합한 Objective function 값을 통해 적합한 K를 찾는다.

## Hierarchical Agglomerative Clustering
![image](https://www.datanovia.com/en/wp-content/uploads/dn-tutorials/003-hierarchical-clustering-in-r/figures/002-agglomerative-clustering-cutree-cut-dendrogram-1.png)
source : https://www.datanovia.com/en/lessons/agglomerative-hierarchical-clustering/
* 데이터 계층 구조를 파악하는 클러스터링 방법
* 비슷한 데이터끼리 묶어가며 모든 클러스터를 합치는 상향식 방법(Agglomerative)

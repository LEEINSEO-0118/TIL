# Classification
## Linear Classifier
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-linear-classifie-4f666eaae330)
* Classification, 분류란 주어진 데이터X를 분류 기준(y, class)대로 나누는 것
* Linear Classifier, 선형 회귀식을 통해 공간을 분리하고 Class를 분류하는 것
## Decision Tree(CART)
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-decision-tree-cart-45a7055d4a7)
* Decision Tree는 해석 가능한 직관적인 머신러닝 모델
* 한 노드에 조건을 부여하여 데이터를 분류하는 것
* CART는 분류, 회귀 모두 가능한 Decision Tree
* Gini index, SSR 을 통해 분류와 회귀 문제의 Tree Best split point를 찾을 수 있다.
## Random Forest
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-random-forest-edb7ae1b7d1d)
* Random Forest는 Ensemble model이다.
* 약한 성능을 가진 CART를 조합하여 강한 성능을 가진 Random Forest를 만들었다.
* Bagging = Bootstrap + Aggregating
* Random Forest는 Random subspace method를 사용한다.
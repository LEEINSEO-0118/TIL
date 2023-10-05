# Boosting
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-boosting-ada-boost-gradient-boosting-machine-xgboost-lightgbm-catboost-d8750ac415ed)
약한 분류기를 조합하여 성능이 좋은 강한 분류기를 만드는 것 (Random Forest와 동일한 방향), Ensemble model

## AdaBoost
* 이전 트리를 보완하는 방식으로 학습
* 데이터 학습 후 model이 오분류한 데이터에 가중치를 준 후 재학습

## Gradient Boost Machine(GBM)
* 데이터를 학습 한 model과 데이터의 오차를 산출
* 오차를 학습한 model과 오차와 Model간의 오차를 산출
* 위 과정을 반복하며 여러 Model을 생성
* Predict : 각 모델에 x값을 넣은 것을 모두 더한 값이 predict 값
* 오차를 학습할 때 a(learning rate)를 주어서 overfitting 방지

## XGBoost
* GBM의 시간이 오래 걸리는 문제를 하드웨어 최적화를 통해 해결
* GBM의 대중화의 시작
* Kaggle과 같은 분석 대회에서 많이 사용

## LightGBM
* XGBoost 보다 가볍고 빠르다.
* Kaggle과 같은 분석 대회에서 많이 사용
* leaf-wise tree growth를 사용하여 split point를 찾음으로 작은 메모리로도 빠르고 성능이 좋은 트리를 만듦

## CatBoost(CAT)
* Kaggle과 같은 분석 대회에서 많이 사용
* Categorical feature에 대해 학습이 잘 된다. (자동으로 인코딩 해줌)
* parameter tuning이 쉽고 GPU 최적화가 잘 되어있다.
# Model Training
[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-training-ml-model-for-good-performance-grid-search-random-search-k-fold-cv-f45c615455a3)
## Hyper parameter tuning
ML Model이 좋은 성능을 가지기 위해서 Hyper-param Tuning이 필수적이다.
* Grid Search : 분석가가 지정한 파라미터의 모든 조합을 modeling하여 최고 성능을 보이는 파라미터를 알려준다.
* Random Search : 특정 범위와 시행횟수 안에서 Random하게 파라미터를 찾는다. 최고 성능을 보이는 파라미터를 찾을 확률이 가장 크다.
## K-Fold Cross Validation
* Training Data를 K 등분하여 최대한으로 학습에 활용하는 기법
* K-Fold modeling을 통해 얻은 최적의 파라미터를 통해 모델을 만들고 그것을 통해 P_test를 확인
## Optuna(AutoML Framework)
* 자동으로 Hyper-param tuning을 해주는 프레임워크
* Random Search + Bayesian Optimizaion
  
  
   
    
**Human research, Grid research, Optuna 모두할 수 있어야 한다.**
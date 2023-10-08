[블로그 정리 글](https://medium.com/@dlstj1506/machine-learning-eda-and-feature-engineering-for-machine-learning-fa188b949bde)
# EDA
탐색적 데이터 분석을 통해 ML에 적합한 통계량을 파악해야 한다.
* 일반적인 고려 사항
    * row, column, memory size등 데이터 확인
    * pd.DataFrame.info()를 통한 column 정보 확인
    * 결측치에 대한 정보 확인
    * Categorical feature 정보 확인    
    ML하기 위해서는 결측치가 없어야 하고, String 혹은 Categorical feature가 없어야 한다.
* 결측치 처리 방법 : 여러 조건에 따라 Column 삭제, Row 삭제, 데이터 채우기 등을 시행할 수 있다.
# Feature Engineering
데이터를 분석 목적에 가공, 분석에 필요한 Feature 추출, EDA와 함께 동시에 진행하면 된다.

* 차원의 저주 : 고차원 데이터는 머신러닝에 취약하기에 차원 수를 적절히 줄여주는 것이 필요하다. 
    * 차원을 줄이는 방법
        1. 차원 축소 기법 : PCA, AutoEncoder 등
        2. 상관관계 분석

* Feature Scaling : feature 단위가 서로 다르다면 Modeling에 문제가 생길 수 있다. 단위를 맞추어서 올바른 modeling을 해야한다.

* Encoding Categorical feature : 범주형 변수들은 modeling할 수 없기에 해당 데이터들을 numeric 데이터로 encoding 해주어야 한다.
    * One-hot encoding : 주로 Nominal feature
    * Ordinal encoding : 주로 Orginal feature

* Feature Selection : 피처의 중요도에 따라 피처를 선택하여 modeling에 사용
    * Top k feature selecition
    * threeshold
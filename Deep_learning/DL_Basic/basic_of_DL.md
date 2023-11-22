# Basic of Deep Learning
[블로그 정리 글](https://medium.com/@dlstj1506/deep-learning-basic-of-deep-learning-620bd3cda677)
## Deep Learning
Deep Neural Network를 이용한 Machine Learning
## ML vs DL
* 비정형 데이터의 경우 DL이 좋다.  
* 정형 데이터의 경우 ML이 좋다. (시계열의 경우 DL)
## Perceptron
* 인간의 neuron을 컴퓨터의 형태로 구현한 것  
* input에 가중치를 더하여 만들어낸 Linear한 값들을 Activation Function에 대입하여 output을 출력한다.
## Multi-Layer Perceptron
* MLP라고 불리는 다층퍼셉트론, 일반 Perceptron의 한계를 극복하기 위해 만들어졌다.  
* Hidden Layer 1개 - Shallow Neural Network  
* Hidden Layer 2개 이상 - Deep Neural Network  
* 각 Layer에 activation function을 적용한다. (ex. sigmoid, tanh, ReLU)
* Output Layer에 적용하는 활성함수는 Output function
## Output function
Softmax : Multi-class classification에서 사용되는 Output function
## Loss function
* Cross Entropy : 분류의 예측값이 틀린 정도를 계산
## Optimizer
Loss를 weight에 Update하는 방법 (ex. GDA, SGD, Momentum, Adam, AdamW)
## Mini-batch Training
전체 데이터 중 m개의 데이터를 한 번에 feed-forward하여 평균 Loss를 weight에 update
## Transfer Learning
기존에 학습된 모델의 weight와 architecture를 사용하는 fine tuing을 많이 사용한다.
## Back-progatation
Loss를 효율적으로 업데이트 하는 방법
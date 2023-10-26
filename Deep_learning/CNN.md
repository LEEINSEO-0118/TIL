# Convolutional Neural Network
[블로그 정리 글](https://medium.com/@dlstj1506/deep-learning-cnn-f666767e988e)
## CNN
이미지의 특징을 잘 파악하는 Neural Network ***이미지 처리 영역***과 ***NN*** 영역으로 나뉨
* 이미지 처리 영역 : Convolution과 Pooling을 통해 이미지를 학습하기 좋게 처리
* NN 영역 : MLP를 통해 처리된 이미지 데이터를 학습
## Convolution Layer
가중치가 있는 filter(kernel)을 이용하여 이미지 처리
## Pooling Layer
가중치 없는 filter를 통해 이미지를 축소
## Vanilla CNN Architecture
가장 기본이 되는 CNN 구조  
Conv Block(Conv-Conv-Pool)-Conv Block-Conv Block-FC
## Zero Padding
이미지 데이터의 가장 자리에 0으로 데이터를 채워서 Convolution으로 인한 이미지 크기 감소를 방지한다.
# RNN_LSTM_GRU
[블로그 정리 글](https://medium.com/@dlstj1506/deep-learning-rnn-lstm-gru-e2cc1436b5c1)
## Recurrent Neural Network
* Hidden Layer가 자신을 참고하는 Recurrent Layer  
* Input이 이전 Hidden state와 함께 계산되어 새로운 hidden state를 생성하고 이것이 다음 input과 다시 함께 계산되는 구조
## Long-Short Term Memory
* RNN의 단점인 장기기억 의존성을 줄여주는 알고리즘
* 장단기 기억을 잘 조합하여 output을 출력
* cell state, hidden state 2가지를 출력
## GRU
* LSTM의 계산을 더욱 효율적으로 수행
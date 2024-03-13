# **CNN-RNN 실습**

**👩🏻‍💻 AI 엔지니어 기초 다지기:**
    

## **Convolutional Neural Network(CNN): Cat-Dog Classifier**
**CNN이란?:** 
  - 공간적 데이터(이미지) 합성곱 신경망(인간의 시신경 모방)
  - 레이어로 구성
  - 특징 추출, 패턴 파악: 이미지 분류 특화/ 영상 처리
  - Convolution Layer: 데이터 특징 추출
  - Pooling Layer: Convolution Layer 사이즈 조정

**목적:** 
  - CNN을 설계하고 이미지 분류기를 학습시킨다.
  - 학습 과정에서 데이터 증식(data augmentation)을 적용한다.
  - 학습된 모델을 저장하고 불러올 수 있다.
  - 전이학습(transfer learning)을 구현할 수 있다.


## **Recurrent Neural Network(RNN): Neural Weather Forecaster**
**RNN이란?:** 
  - 시계열/ 순차 데이터 순환 신경망
  - 뉴런 연결 패턴: 이전 State 정보가 다음 State를 예측하는데 사용됨
  - Markov를 기반
  - Transformer 구현시 가장 많이 사용하는 라이브러리: Huggingface



**목적:**  
  - RNN을 설계하여 지난 며칠 동안의 날씨 정보를 기반으로 24시간 이후의 기온을 예측한다.
  - 다양한 속성의 시계열 정보를 활용하기 위해 적절한 전처리 과정을 적용한다.
  - 설계한 모델의 성능을 검증하기 위해 베이스라인 모델을 도입한다.

# Stock_Prediction

학습 데이터로 한국의 대표기업인 삼성전자를 사용하였습니다.

<img src="https://user-images.githubusercontent.com/50981989/89871074-c6f88b00-dbf1-11ea-855c-a6d2e7b41975.PNG"  width="700" height="370">

# Overview

미래의 주가는 과거의 데이터에 많은 영향을 받을 것이고,

따라서 과거 데이터를 계속해서 학습시켜 모델링 하는 Recurrent Neural Network 모델이 예측에 적합하다고 판단됩니다.

<img src="https://user-images.githubusercontent.com/50981989/89870391-bbf12b00-dbf0-11ea-8783-b926b186efd1.png"  width="600" height="470">

RNN의 vanishing gradient problem은 주가예측에 치명적이기 때문에 lstm 모델을 사용하였습니다.


# Result

train-test를 0.8 : 0.2 로 분할하여 예측하였고, 꽤나 근사한 추세를 얻어낼 수 있었습니다.

<img src="https://user-images.githubusercontent.com/50981989/89871913-2905c000-dbf3-11ea-88fc-7a45bba170b5.PNG"  width="900" height="500">

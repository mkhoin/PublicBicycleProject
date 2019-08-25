# Public Bicycle Demand Prediction in Seoul 


### 참여자
- 김인중, 정현, 권덕화, 부석준

### Abstract
- 서울시 공공자전거 따릉이는 2015년 처음 도입 된 이후로 매년 수요가 크게 늘고있는 자전거 대여 서비스로 이용량 예측에 대한 필요성이 부각되고 있다. 기존 공공자전거 이용량 데이터로부터 기계학습 방법에 기반하여 시계열 특성을 모델링하는 시도가 있었으나, 미세먼지나 날씨요인을 고려하지 않아 그 정합성에 한계가 있다. 본 논문에서는 공공자전거 이용량의 정확한 예측을 위해 외부활동에 큰 영향을 준다고 알려진 기온, 강수량, 습도 등의 기상 데이터와 미세먼지를 포함하는 대기오염도 데이터를 추가적으로수집하여 가공하였고, CNN-LSTM기반의 딥러닝 알고리즘으로 모델링하는 방법을 제안한다. 메타데이터를 추가적으로 활용하는 딥러닝 모형이 기존 기계학습모형 대비 통계적으로 유의미하게 향상된 성능을 획득함을 10겹 교차검증으로 검증하였다. 추가적으로 본 논문에서는 2,200만건에 달하는 따릉이 이용 데이터와 미세먼지를 포함하는 날씨데이터의 전처리 방법을 기술하였고, 다양한 딥러닝 하이퍼파라미터에 대해 반복실험하는 것으로 실용적인 공공자전거 이용량 예측 방법을 개발하고 검증하였다.

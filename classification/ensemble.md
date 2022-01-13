# 앙상블(Ensemble) 학습
### : 여러개의 모델을 생성하고 그 예측을 결합함으로써 보다 정확한 최종 예측을 도출하는 기법
- 어려운 문제의 결론을 내기 위하여 여러 명의 전문가의 의견을 수렴하는 것
- 다양한 모델의 예측 결과를 결함하여 단일 모델보다 더 신뢰성이 높은 예측값을 얻는 것
### 대표적인 앙상블 모델
- 랜덤포레스트(RandomForest)
- 부스팅 계열 모델
  - 그래디언트 부스팅(GBM)
  - XGBoost
  - LightGBM
### 전통적인 앙상블 학습
- [보팅(Voting)](https://github.com/HwangHanJae/ml-definitive-guide-pratice/blob/97270c41b1677b949f732d50d6323e1eeb82fd7e/classification/voting_learning.ipynb)
  - 여러개의 서로 다른 모델이 투표를 통해 최종 예측을 결정
- 배깅(Bagging)
  - 여러개의 서로 같은 유형의 모델이 결합하지만 데이터 샘플링을 서로 다르게 가져가면서 보팅을 수행
- 부스팅(Boosting)
  - 약한 모델을 결합하여 강한 모델을 만들어 예측하는것
- 스태킹(Stacking)
  - 여러가지 모델의 예측 결과값을 다시 학습데티어로 만들어 다른 모델(메타모델)로 재학습시켜 예측
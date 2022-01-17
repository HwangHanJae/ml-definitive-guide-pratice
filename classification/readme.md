# 분류(Classification)

## 지도학습(Supervised Learning)
### 명시적인 정답(Label)이 있는 데이터가 주어진 상태에서 학습하는 머신러닝 방식
## 분류란
####  - 지도학습의 대표적인 유형
#### 1. 학습 데이터로 주어진 데이터의 피처와 레이블값(결정값, 클래스 값)을 머신러닝 알고리즘으로 학습해 모델을 생성
#### 2. 생성된 모델에 새로운 데이터 값이 주어졌을 때 미지의 레이블 값을 예측
### 즉 기존 데이터가 어떤 레이블에 속하는지 패턴을 알고리즘으로 인지한 뒤 새로운 데이터에 대해 레이블을 판별하는 것

## 머신러닝 알고리즘(분류)
- 나이브 베이즈(Naive Bayes) : 베이즈(Bayes)통계와 생성 모델에 기반 
- 로지스틱회귀(Logistic Regression) : 독립변수와 종속변수의 선형 관계성에 기반
- [결정 트리(Decision Tree)](https://github.com/HwangHanJae/ml-definitive-guide-pratice/blob/82204d9b092fb377376b4ec948d6e97fd830997c/classification/decision_tree.ipynb) : 데이터 균일도에 따른 규칙 기반
- 서포트 벡터 머신(Surpport Vector Machine) : 개별 클래스 간의 최대 분류 마진을 효과적으로 찾아줌
- 최소 근접(Nearest Neighbor) 알고리즘 : 근접 거리를 기준
- 신경망(Neural Network) : 심층 연결 기반
- [앙상블(Ensemble)](https://github.com/HwangHanJae/ml-definitive-guide-pratice/blob/bab5e606fd23a50b308a2129232232d0eff2fa6f/classification/ensemble.md) : 서로 다른(또는 같은) 머신러닝 알고리즘 결합

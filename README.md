# Developing a Machine Learning-Based Algorithm for Assessing Enterprise Promisingness_sub study 1
project

## Purpose
기존의 기업 유망성 평가 방식과 다르게 재무 데이터뿐 아니라 거래 데이터를 추가하여 머신 러닝과 GNN을 활용한 기업 유망성 평가 모델을 개선할 수 있는 가능성 확인

## Methodology
GNN 모델을 통해 거래 정보를 압축한 점수를 산출하여 이를 유망 기업(향후 3년간 매출액이 연평균 20% 이상 증가할 것으로 예상되는 기업) 예측에 활용

  - Model : ML 모델(Random Forest), DL 모델(GNN-GraphSAGE)
  - Dataset : 기업 별 재무 데이터 및 거래 데이터 (비공개)

## Result
1. 1년 후 유망 기업 예측 성능이 기존 방식보다 평균 1.52%p 성능 향상 확인
2. 3년 후 유망 기업 예측 성능이 기존 방식보다 평균 0.495%p 성능 향상 확인
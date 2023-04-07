# 안전 운전자 예측

2023.04.06.목. HAI Kaggle Study

2조 2017030546 황태경

## 1. base_line

데이터 분석을 위한 코드로, baseline으로 LightGBM을 사용하여 결과를 낸 노트북입니다.

결과 : 지니계수, 0.282123

## 2. improved_LightGBM_모델

파생 피처와 베이지안 방식을 통해 하이퍼 파라미터 튜닝 방법을 사용하여 결과를 낸 노트북입니다.

결과 : 지니계수, 1 0.286008

## 3. improved_XGBoost 모델

2번과 동일하게 성능향상을 하되, XGBoost 모델을 사용하여 결과를 낸 노트북입니다.

결과 : 지니계수, 0288326

## 4. improved_XGBoost + LightGBM 앙상블

두 모델을 weighted sum하여 앙상블 한 결과를 담은 노트북입니다.

결과 : 지니계수, 0.288410

## 5. 최종 결과

Public Score : 0.28566

**Private Score : 0.29057**
# 향후 판매량 예측 경진대회

2023.05.01.월. HAI Kaggle Study

2조 2017030546 황태경

## 1. 데이터분석
데이터 분석, 데이터 시각화를 위한 노트북입니다.

## 2. 베이스라인

baseline으로 LightGBM을 사용하여 결과를 낸 노트북입니다.

결과 : RMSE, 1.08534

## 3. improved_피처_엔지니어링

이상치 제거 + 파생 피처 추가 + 시차 피처를 추가하여 LightGRM을 사용하여 결과를 낸 노트북입니다.
결과 : RMSE, 0.89534

추가로, test 데이터에만 존재하는 상점ID만 추출하여 LightGBM을 사용하여 결과를 낸 경우 다음과 같습니다.
결과 : RMSE,0.87701

## 4. 최종 결과

**Public Score : 0.87701**
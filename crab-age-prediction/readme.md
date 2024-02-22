## :books: 대회 주제 
Regression with a Crab Age Dataset : crab age prediction

> 세종대학교 2023-1 전공심화공동체
> 
> 2023.05 ~ 2023.06

<br/><br/>

## 🏆 최종 랭킹
MAE(mean absolute error)
> 1.3818

ranking 
> 687/1429

<br/><br/>

## :star2: 대회 링크
[Regression with a Crab Age Dataset](https://www.kaggle.com/competitions/playground-series-s3e16/
)

<br/><br/>

## :star2: 대회 개요 및 목적
게의 다양한 정보들을 활용한 게 나이 예측

> id, sex, length, diameter, height, weight, shucked weight, viscera weight, shell weight의 컬럼 존재

<br/><br/>

## :star2: 사용한 방법론, 모델
📌 LightGBM

📌 XGBoost

📌 KFold

📌 Ensemble

<br/><br/>

## :star2: 느낀 점
- 이상치, 결측치가 많아 데이터가 정리되어있지 못함을 느낌

- 나이의 분포를 시각화해본 결과 나이와 키, 몸무게가 비례하지 않은 것을 확인할 수 있었고 이를 통해 게의 다양한 종류가 섞여있는 것일까 하는 생각이 들며 해당 컬럼이 있었다면 더욱 정확도 높은 결과를 얻을 수 있었을 것이라는 생각이 들어 아쉬움이 남음

- 지금까지는 XGBoost, LightGBM으로 대부분 해결했는데, 더욱 다양한 모델을 활용해보고 싶다는 생각이 듦
 

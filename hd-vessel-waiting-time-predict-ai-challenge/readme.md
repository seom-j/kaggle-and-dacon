## :books: 대회 주제 
HD현대 AI Challenge : hd-vessel-waiting-time-predict-ai-challenge

> 세종대학교 2023-2 전공심화공동체
> 
> 2023.09 ~ 2023.10

<br/><br/>

## 🏆 최종 랭킹
MAE (mean absolute error)
> 45.90871

ranking 
> 117/330, 상위 35%

<br/><br/>

## :star2: 대회 링크
[HD현대 AI Challenge](https://dacon.io/competitions/official/236158/)

<br/><br/>

## :star2: 대회 개요 및 목적
접안(배를 육지에 대는 것;Berthing) 전 선박이 해상에 정박(해상에 닻을 바다 밑바닥에 내려놓고 운항을 멈추는 것;Anchorage)하는 시간을 대기시간으로 정의하고, 선박의 제원 및 운항 정보를 활용하여 산출된 항차(voyage; 선박의 여정) 데이터를 활용하여 항만 內 선박의 대기 시간을 예측하는 AI 알고리즘 개발

> [Data Description](https://dacon.io/competitions/official/236158/data)

<br/><br/>

## :star2: 사용한 방법론, 모델
📌 LightGBM

📌 KFold

📌 DNN

<br/><br/>

## :star2: 느낀 점
- 실제 활용되는 Task에서의 데이터는 정제되지 않은 데이터임을 느꼈으며 이에 어떠한 데이터가 정말 이 과제에 필요한 데이터이고, 어떻게 활용하면 좋을지를 판단하는 실력을 기를 필요가 있다는 것을 느낌

- 데이터의 컬럼이 많을수록 이들의 연관성을 파악하고, 모델이 너무 복잡해지거나 과적합되지 않도록 적절한 처리가 필요함을 느낌 

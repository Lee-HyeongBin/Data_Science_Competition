# Data_Science_Competition
🏆 데이터 사이언스 AI 경진대회 출품작 🥇
---
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLee-HyeongBin%2FData_Science_Competition&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
---
<b>Since</b> 2020.08.03 ~ ing
---
* 데이터 사이언스 AI 경진대회 출품작 코드 및 PPT 정리
* 각 코드 내 마크다운과 주석 또는 PPT를 통하여 설명
* 복사 및 수정은 leehyeongbin@naver.com 문의 먼저 부탁

<br><br>
# 📃 Table of Contents
## 1. 고양시 공공자전거 스테이션 최적화
* 고양시의 공공자전거 운영이력 데이터 및 공간 데이터를 활용
* 자전거 스테이션의 최적 위치 및 각 스테이션 별 최적 거치대 수 예측
 * H3 그리드셀 분할 시스템을 활용하여, 각 그리드의 지리적·상업적 특성을 고려한 군집을 분석
 * 각 군집별 자체 점수 산정 시스템을 통하여 상위 300개 스테이션 선정
 * 각 스테이션 별 최적 거치대 수는 MinMaxScaler 이용
 <br><br>
## 2. 상권분석 빅데이터 경진대회
### [우수상 수상]
* 블록간 파워업종과 타업종 간의 시너지를 고려한 모델
* 입지와 업종을 다각적으로 고려한 모델
* 입지 군집화 → 군집별 인구통계적·상업적 요소 점수화 → 시너지 점수화 → 각 시너지 별 방안 제시
<br><br>
## 3. LG 사용자 불편 예지 AI 경진대회
### [5위/1397팀]
* 고객 별 에러 로그 시계열 데이터를 분석하여, 소비자들이 불편을 제기하는 원인 분석 및 비즈니스 모델 제시
* 시계열 데이터 EDA를 통해, 파생변수 약 1,000개 생성
1) Pycaret으로 Best Model Selection
2) CatBoost를 Baysian Optimization & GridSearchCV로 Tunning
3) AUC 높은 모델 2개를 선정하여 Blending
4) 최종 예측 확률 Submission 제출

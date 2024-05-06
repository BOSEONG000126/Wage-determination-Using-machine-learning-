# 소상공인을 위한 영업 상황 별 아르바이트 시급 제안 서비스 Project
<img src="https://github.com/BOSEONG000126/Wage-determination-Using-machine-learning-/assets/116350240/5d400a10-0a1a-4f45-8177-096e21c78fa3" width="800" height="400">



<br/>

---
## 활용 데이터셋
### [1] 1차 모델 데이터 수집
<img src="https://github.com/BOSEONG000126/Wage-determination-Using-machine-learning-/assets/116350240/441b9fe2-5451-4396-bf5e-e88f32bf0b41" width="800" height="400">
<br/>

### [2] 2차 모델 데이터 수집 
<img src="https://github.com/BOSEONG000126/Wage-determination-Using-machine-learning-/assets/116350240/57608a3a-61e7-47d8-b40f-35a8ab4dd15a" width="800" height="400">

<br/>

## Data Engineering
### [1] Data Analysis
<img width="870" alt="스크린샷 2024-05-06 오후 3 45 04" src="https://github.com/BOSEONG000126/Wage-determination-Using-machine-learning-/assets/116350240/afa4f4df-99b7-4a28-b6f8-93748afe730e">

  + 업종, 블로그 리뷰 개수, 가까운 역까지의 시간 등 다양한 변수들에 대한 모델 설계 후, FI확인
  + 수집 데이터 세트에서 모델 학습에 유의미한 영향을 주지 못하는 배달여부, 성별, 요일 등의 속성을 제거, 모델 경량화

<br/>

### [3] ML Modeling
<img width="804" alt="스크린샷 2024-05-06 오후 3 48 10" src="https://github.com/BOSEONG000126/Wage-determination-Using-machine-learning-/assets/116350240/41b6c09d-76ff-4d2c-affc-f05fc5f426b3">

 + 6가지 모델에 대해 성능을 평가하고, 높은 성능의 모델들을 앙상블 모델 기법을 사용하여 최종 모델 결정 
 + 최종 평가 결과, R2 0.47 정도로 약하지만 일반적인 성능을 보장

<br/>

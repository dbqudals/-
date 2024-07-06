**유통 판매량 예측 및 재고 최적화**

![image](https://github.com/dbqudals/Sales-forecast/assets/117886852/3ef79d40-7d9f-4cea-bdd1-c09c85ffeeca)
![image](https://github.com/dbqudals/Sales-forecast/assets/117886852/5df8cf92-e6a8-4a82-97b1-ca14b435bf32)
![image](https://github.com/dbqudals/Sales-forecast/assets/117886852/1172d815-1be5-4bbf-ba9f-94e846d507b8)

**1.데이터 탐색 및 가설 도출_v1.0.ipynb**
  - 핵심 상품 별 sales 판매량 확인
  - 시계열 패턴 찾아보기
  - 대상 상품의 동일 카테고리의 상품별 판매량 추이
  - 휘발류 가격과 상품 판매량 추이 비교
  - 패턴 정리하기
    
**2.데이터 전처리 및 Baseline Model 생성_v1.0.ipynb**
  - 상품별 데이터셋 만들기
    - 가설로 도출된 변수를 반영한 데이터셋을 상품별로 생성
  - Baseline Model 생성
    - LSTM, CNN 생성
      
**3.모델링 및 비즈니스 평가_v1.0.ipynb**
  - 다양한 모델링 수행
    - 성능 상위 2~3개 모델 선정
  - 데이터 파이프라인 구축
    - 예측에 사용할 수 있는 형태로 데이터를 만드는 과정을 하나의 함수로 엮기
  - 비즈니스 평가
    - 모델에 대해 test셋으로 평균 재고액 평가 수행 

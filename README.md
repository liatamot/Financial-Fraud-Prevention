# Financial Fraud Prevention_Visualization Project
   
   
## 1. 프로젝트 목표
스마트 치안 빅데이터 플랫폼 데이터를 활용한 금융사기 예방 방안을 도출 및 시각화 프로젝트

   

## 2. 프로젝트 기간
2023.11.06 ~ 2023.11.14

   

## 3. 팀 프로젝트
   
### - 팀 소개 및 주요 역할
김창희 : 피해 특성에 따른 금융사기 유형 분석
진성준 : 지역별 금융사기 피해자 및 피의자 분석
박성우 : 성별/연령대별/분석지역별/피해금액별 피해 유형 및 추이 분석
   
   
## 4. 개발 환경
- Python
- IDE: VSCODE, Jupyter Notebook
- Library: pandas, numpy, matplolib, seaborn, plotly, geopandas etc
   
   
## 5. 주요 내용
   
### 1) Data
- 스마트 치안 빅데이터 플랫폼, 금융사기 피해자 및 피의자 데이터 활용
- https://www.bigdata-policing.kr/search?searchType=all&keyword=%EA%B8%88%EC%9C%B5%EC%82%AC%EA%B8%B0
- 피해자 및 피의자의 연령, 성별, 지역, 통신사, 입금은행, 피해 발생 금액/물품/사이트 등의 데이터 전처리 및 시각화
   
   
### 2) 주요 EDA 내용
- 수도권과 비수도권 사이의 피해자 발생 수가 크게 차이나며, 대부분 수도권과 부산에서 많은 피해 발생
     
  ![image](https://github.com/liatamot/Financial-Fraud-Prevention/assets/138054658/6911a663-4f6d-47ae-860b-5972c4005b9f)
- 2010년생이 가장 잦은 빈도수의 피해 사례를 나타내고 있으며, 주요 피해 연령대의 피해금액은 100만원 미만(5만원 미만 케이스가 최다 빈도수)으로 나타남
   
  ![image](https://github.com/liatamot/Financial-Fraud-Prevention/assets/138054658/c12f7f29-2a6c-431e-93d2-c88a8a638eac)
     
- 반면 중장년층(1960-1980) 피해자의 평균 피해 금액은 다른 연령대에 비해 상대적으로 높은 것으로 나타남
     
  ![image](https://github.com/liatamot/Financial-Fraud-Prevention/assets/138054658/c67f7c04-43b6-41b7-9c1a-8ca1bd3c93db)
- 기존 자료조사와 마찬가지로 접근성이 좋은 카카오뱅크(34%)에서의 금융 사기와 카카오페이증권(49%)에서의 금융 증권 사기 피해 건수가 높은 것으로 나타남
- 지속적으로 상승하고 있는 금융사기 범죄의 피해는 주로 여성 보다는 남성, 젊은 연령대에서, 100만원 미만의 소액 규모의 피해가 온라인 및 디지털화된 범죄 경로를 통하여 발생하고 있음
   





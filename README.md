# kdca_patients_prediction

#### (프로젝트 관리를 위한 repository입니다.)
---
## 온열질환자 예측을 위한 모델링
### 1. 목적 

    - 온열질환자 발생으로 인한 병원 응급시스템 관리 및 질환 예방

### 2. 프로세스
    
    - 데이터 수집/가공/정제
    - 데이터 EDA
    - ML/DL을 이용한 예측/분류
    - 결과 분석

### 3. 데이터셋

    - 종관기상관측(ASOS) 데이터, 방재기상관측(AWS) 데이터, 위성(천리안2A) 데이터, 시도별 인구 데이터, 시도별 농업종사자 인구 데이터 

### 4. 분석환경

    - 데이터 수집: python
    - 데이터 가공: MSSQL, python
    - 모델링: scikit-learn, keras


### 5. 분석내용
    
    - kdca_heat_patients_eda.ipynb: data eda
    - kdca_heat_patients_feature_select: feature selection 
    - kdca_heat_patients_modeling_cnt_01: LSTM/RNN/RandomForest/XGBoost prediction
    - kdca_heat_patients_modeling_cnt_02: feature selection with modeling
    - kdca_heat_patients_modeling_cnt_03: time series sorting modeling(RandomForest, XGBoost)
    - kdca_heat_patients_modeling_cnt_04: binning & clustering for modeling
    - kdca_heat_patients_modeling_cls_01: multivariate classification(max_ta_cluster)
    - kdca_heat_patients_modeling_cls_02: multivariate classification(max_wbtemp_cluster)
    - kdca_heat_patients_modeling_yn: classification
    - kdca_heat_patients_modeling_sido: sido LSTM/RNN/RandomForest/XGBoost sido prediction
    - kdca_heat_patients_imtermittent: PoC analysis case

### 6. 분석결과
    - Regressor: RandomForest, XGBoost
    - Classifier

### 7. 참고

    - Time Series Forecasting(TSF) Using Various Deep Learning Models
    - RNN
    - LSTM
    - RandomForest
    - XGBoost
    - Feature Selection Method
    - Croston's Method
    - DeepAR
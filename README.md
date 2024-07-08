# SKN02-2nd-2Team
김영현 서종호 장정원 황양오

# About Project
통신 3사의 기존 고객이 알뜰폰으로 갈아타는 ‘환승족’ 늘어나는 추세입니다. SKT 기준 41.3%(21년 11월) → 40.2%(22년 11월)으로 점유율 감소하였고, 알뜰폰 기준 14.1%(21년 11월) → 16.7%(22년 11월)로 급성장하였습니다.
가입자 확보 중심의 성장 전략은 포화상태로 한계가 있어 통신사 고객의 이탈 관리 방안에 대한 분석 필요성을 느꼈습니다.
이를 위해 Kaggle의 Telco Customer Churn Dataset을 분석하여 insight를 확보하고자 하였습니다.

# Dataset
- 데이터셋: Telco Customer Churn
- 출처: [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)
- 데이터 정보: 캘리포니아에서 7,043명의 고객에게 집 전화 및 인터넷 서비스를 제공한 가상의 통신사에 대한 정보가 포함된 데이터셋
    - 어떤 고객이 서비스를 떠났고, 남아있거나, 서비스에 가입했는지 확인
- Column 정보:  
    고객이 가입한 서비스 : 전화, 여러 회선, 인터넷, 온라인 보안, 온라인 백업, 기기 보호, 기술 지원, 스트리밍 TV 및 영화 등의 서비스  
    고객 계정 정보 : 고객 가입 기간, 계약, 결제 방법, 종이 없는 청구서, 월별 요금 및 총 요금  
    고객에 대한 인구통계학적 정보: 성별, 연령대, 파트너 및 부양가족이 있는지 여부

# Stack

주요 언어  
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

데이터 분석  
 ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
 ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
 ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

인공지능 모델  
 ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
 ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
 ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
  
환경  
 ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
  
협업  
 ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)

 # Models
 - LogisticRegression  
 - DecisionTree  
 - RandomForest  
 - GradientBoosting
 - XGBoost
 - LightGBM
 - CatBoost (최종모델)
 - MLP

# Results
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN02-2nd-2Team/assets/158265663/5464b7d5-ff62-4fcc-ab12-430e406acf97)
![image](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN02-2nd-2Team/assets/158265663/07a25555-cb60-4f56-815d-ff98c6e81793)
본 보고서에서는 다양한 머신러닝 모델을 활용하여 후보 예측을 수행한 결과를 분석하였습니다. 초기 테스트 결과 로지스틱 회귀 모델이 가장 높은 성능을 보였으나, Stratified K-Fold 교차 검증 및 Feature Importance 분석을 통해 추가적인 하이퍼파라미터 튜닝을 진행한 결과, 다른 모델에서도 성능 향상을 확인할 수 있었습니다. 앞으로의 연구에서는 더욱 정교한 파라미터 튜닝 및 모델 앙상블 기법을 도입하여 예측 성능을 향상시키는 방향으로 진행할 예정입니다.

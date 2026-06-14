# ML 기반 네트워크 침입 탐지 시스템 (IDS)
## 데이터셋
- NSL-KDD Dataset
- 125,973개 샘플 / 41개 피처
- 5개 클래스: Normal, DoS, Probe, R2L, U2R


## 기술 스택
Python 3.12 / Pandas / NumPy / Scikit-learn / XGBoost
Matplotlib / Seaborn / Imbalanced-learn / SHAP


## 구현 
- [x] 환경 세팅
- [x] 1단계: EDA
- [x] 2단계: 전처리 (인코딩, 스케일링, SMOTE)
- [x] 3단계: 모델 학습 & 평가 (Logistic Regression, Decision Tree, Random Forest, XGBoost)
- [ ] 4단계: SHAP 피처 중요도 분석


## 디렉토리 구조
```
ids-ml-project/
├── data/
│   ├── raw/           # 원본 NSL-KDD
│   └── processed/     # 전처리 데이터
├── notebooks/         # jupyter notebook
├── src/               # 모듈화 코드
├── models/            # 저장된 모델
└── api/                  
```

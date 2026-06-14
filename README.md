# Titanic Feature Engineering Pipeline

Titanic Dataset을 활용한 머신러닝 Feature Engineering 과제입니다.

## 구성
- `titanic_feature_engineering_pipeline.ipynb`: EDA, Feature Engineering, Feature Selection, 모델 비교, GridSearchCV, SHAP, AutoML-style 비교 코드
- `titanic.csv`: Titanic 데이터셋

## 포함 내용
- 결측치 처리 비교: Mean / Median / Most Frequent
- 인코딩 비교: One-Hot / Ordinal
- 스케일링 비교: StandardScaler / MinMaxScaler / RobustScaler
- 파생 변수: FamilySize, IsAlone, FarePerPerson, HasCabin, Title, AgeGroup
- Feature Selection: SelectKBest, Random Forest Feature Importance
- 모델 비교: Logistic Regression, Random Forest, ExtraTrees, GradientBoosting
- 가산점: Pipeline, GridSearchCV, SHAP, AutoML-style 모델 비교, Feature Importance 시각화

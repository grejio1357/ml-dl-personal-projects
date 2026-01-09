# 프로젝트 목록 (Machine Learning & Deep Learning)

본 저장소는 머신러닝 및 딥러닝의 핵심 개념을 학습하고,
다양한 데이터 유형에 적용한 **개인 실습 및 프로젝트 모음**입니다.  
각 프로젝트는 모델 구현, 학습, 평가 과정을 포함합니다.


## 1. 머신러닝 분류 (ML Classification)

**사용 알고리즘**
- Decision Tree
- Random Forest
- SVM 등

**설명**
다양한 분류 알고리즘을 적용하여 데이터셋을 예측하고,
모델별 성능을 비교·평가하였습니다.

**파일**
- `ml_classification.ipynb`


## 2. 머신러닝 회귀 (ML Regression)

**사용 알고리즘**
- Linear Regression
- Random Forest Regressor 등

**설명**
연속형 수치 예측 문제를 대상으로 회귀 모델을 학습하고
성능을 평가하였습니다.

**파일**
- `ml_regression.ipynb`


## 3. CNN 이미지 분류 (From Scratch)

**설명**
PyTorch를 사용하여 **CNN 모델을 처음부터 직접 구현**하고,
이미지 분류 문제에 적용하였습니다.

**파일**
- `cnn_new_model.ipynb`


## 4. CNN 이미지 분류 (Pretrained Model)

**설명**
ResNet, VGG, AlexNet 등 **사전 학습된 CNN 모델**을 활용하여
이미지 분류 성능을 비교·분석하였습니다.

**파일**
- `cnn_pretrained.ipynb`


## 5. LSTM 기반 시계열 예측

**설명**
LSTM 네트워크를 활용한 시계열 예측 프로젝트입니다.  
**불규칙(비균등) 시계열 데이터**를 처리하기 위한 전처리 과정과
모델링 기법을 포함하고 있습니다.

**파일**
- `lstm.ipynb`


## 모델 성능 요약

### 머신러닝 분류
- Test Accuracy (F1-score 기준): **79%**

### 머신러닝 회귀
- R² Score: **0.97**

### CNN (From Scratch)
- Test Accuracy: **34%**

### CNN (Pretrained Models)

**ResNet**
- Top-1 Accuracy: **0.8452**
- Top-5 Accuracy: **0.9582**

**VGG**
- Top-1 Accuracy: **0.8383**
- Top-5 Accuracy: **0.9554**

**AlexNet**
- Top-1 Accuracy: **0.7095**
- Top-5 Accuracy: **0.8927**

### LSTM 시계열 예측
- Test MSE Loss: **0.00215**
- Accuracy (±5% tolerance): **0.043**
- Accuracy (±10% tolerance): **0.090**

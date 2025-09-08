# Cat & Dog Classifier

딥러닝(Deep Learning)을 활용하여 **강아지와 고양이를 이미지로 분류하는 프로젝트**입니다.  
이 프로젝트는 Google Colab 환경에서 CNN 모델을 학습하고, 새로운 이미지를 입력받아 **고양이인지 강아지인지 분류**할 수 있습니다.

---

## 프로젝트 구조
├── CatDogClassifier.ipynb # 메인 Colab Notebook  
├── data/ # 데이터셋 (예: Kaggle Dogs vs Cats)  
├── models/ # 학습된 모델 저장 폴더  
└── README.md  
---

## ⚙실행 방법 (Google Colab)

### 1. Colab에서 열기
- [CatDogClassifier.ipynb](./CatDogClassifier.ipynb) 파일을 Google Colab에서 실행하세요.  

### 2️. 데이터셋 업로드
- Kaggle `Dogs vs Cats` 데이터셋을 Colab에 업로드하거나, Google Drive 연동을 통해 불러옵니다.  

### 3️. 필수 라이브러리 설치
```bash
!pip install numpy pandas matplotlib torch torchvision tensorflow scikit-learn opencv-python
```

### 4️. 실행
- 전체 셀을 순서대로 실행하면 모델 학습과 평가가 진행됩니다.  
- 학습이 완료되면 테스트 이미지에 대해 **Cat(고양이) / Dog(강아지)** 예측 결과를 확인할 수 있습니다.  

---

## 📊 모델 학습 과정
- 데이터 전처리 (이미지 리사이즈, 정규화, augmentation)
- CNN 모델 설계 (Convolution, Pooling, Fully Connected Layer)
- 학습 및 검증 (train/test split)
- 최종 정확도 및 손실(loss) 시각화

---

## 🚀 향후 개선점
- 데이터셋 확장 (다양한 품종 추가)
- Transfer Learning (ResNet, VGG 등 사전 학습 모델 활용)
- 웹/모바일 배포 (Flask, FastAPI, Streamlit)
---

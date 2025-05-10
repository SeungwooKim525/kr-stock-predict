# 📈 주가 상승 예측 모델 - kr-stock-predict 🇰🇷

해당 프로젝트는 한국 주식 데이터를 활용하여 **다음날 종가가 상승할지 여부를 예측**하는 머신러닝 모델을 구현합니다.

---

## 🔍 프로젝트 개요

- 전처리된 피처와 라벨 데이터를 활용한 분류 모델 학습
- 머신러닝 모델 성능 비교 및 평가
  - 로지스틱 회귀 (Logistic Regression)
  - K-최근접 이웃 (K-Nearest Neighbor)
  - Ridge 분류기 (Ridge Classifier)

---

## 📁 폴더 구조
kr-stock-predict/
├── data/ # 전처리된 데이터 (X.pkl, y.pkl)
├── src/ # 학습 스크립트
│ └── train_models.py
├── notebook/ # (선택) 분석용 노트북
├── models/ # (선택) 학습된 모델 저장
├── .gitignore
├── requirements.txt
└── README.md
---

## 📈 사용한 모델

- 로지스틱 회귀 (Logistic Regression)
- K-최근접 이웃 (KNN, k=5)
- Ridge 분류기

---

## ⚙️ Tech Stack

- Python 3.8+
- pandas, scikit-learn, joblib
- JupyterLab
- Git/GitHub

---

## ✅ 모델 성능 예시

| 모델명             | 정확도 (Accuracy) |
|--------------------|------------------|
| Logistic Regression| 0.5455           |
| KNN                | 0.4727           |
| Ridge              | 0.5273           |

※ 위 값은 예시이며, 실험 환경에 따라 달라질 수 있습니다.

---

## 💻 실행 방법

1. 레포지토리를 클론합니다.
2. `data/` 폴더에 `X.pkl`, `y.pkl` 파일을 넣습니다.
3. `src/train_models.py` 또는 노트북을 실행하여 모델을 학습하고 정확도를 비교합니다.
4. 결과를 확인하고 필요시 모델을 저장합니다.

---

## 🙋‍♂️ 작성자

- GitHub: [SeungwooKim525](https://github.com/SeungwooKim525)

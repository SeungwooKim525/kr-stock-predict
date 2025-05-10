# 📈 주가 상승 예측 모델 - kr-stock-predict 🇰🇷

해당 프로젝트는 한국 주식 데이터를 활용하여 **다음날 종가가 상승할지 여부를 예측**하는 머신러닝 분류 모델입니다.

---

## 🔍 프로젝트 개요

- `X.pkl`, `y.pkl`로 구성된 전처리된 데이터를 기반으로 분류 모델 학습
- 종가 상승 여부 (0 또는 1)를 타깃으로 설정
- 다양한 머신러닝 모델 비교: Logistic Regression, KNN, Ridge Classifier
- `StandardScaler`를 통한 피처 스케일링 적용

---

## 📁 폴더 구조
kr-stock-predict/
├── data/ # 전처리된 피처 및 라벨
│ ├── X.pkl
│ └── y.pkl
├── src/ # 모델 학습 코드
│ └── train_models.py
├── .gitignore
├── requirements.txt
└── README.md
---

## 🤖 사용한 모델

- Logistic Regression
- K-Nearest Neighbors (KNN, k=5)
- Ridge Classifier

---

## 📊 결과 (정확도)

| 모델명             | 정확도 (Accuracy) |
|--------------------|------------------|
| Logistic Regression| 0.5455           |
| KNN                | 0.4909           |
| Ridge              | 0.5273           |

※ 피처의 예측력이 낮아 전체적으로 낮은 정확도를 보임

---

## ⚙️ Tech Stack

- Python (pandas, scikit-learn, joblib)
- Jupyter Notebook
- Git & GitHub

---

## 💻 실행 방법

1. 레포지토리를 클론합니다.
2. `data/` 폴더에 `X.pkl`, `y.pkl` 파일이 존재해야 합니다.
3. `src/train_models.py`를 실행하여 모델 학습 및 평가를 수행합니다.

---

## ⚠️ 한계 및 향후 개선 방향

- 현재 피처는 기본적인 가격 정보와 이동평균만 포함되어 있음
- **피처 엔지니어링(RSI, 수익률, 거래량 변화 등)** 필요
- 향후 `pykrx` 등을 활용해 원본 데이터 기반 피처 재구성 예정

---

## 🙋‍♂️ 작성자

- GitHub: [SeungwooKim525](https://github.com/SeungwooKim525)


















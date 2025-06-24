# ⚽ FIFA22 선수 포지션 분류 프로젝트

FIFA 22 선수 데이터를 기반으로, 각 선수의 능력치(피지컬, 스피드, 패스 등)를 활용하여  
**주 포지션(공격/미드필더/수비)**을 분류하는 머신러닝 모델을 구축한 프로젝트입니다.

---

## 📌 프로젝트 개요

- FIFA22 선수 능력치 기반 포지션 분류
- 수치형 특성만 활용하여 포지션 자동 예측
- KNN, 로지스틱 회귀, 의사결정트리 등 다양한 분류 모델 비교

---

## 🧪 분석 과정 요약

1. **데이터 불러오기 및 전처리**
2. **포지션 라벨 간소화** (ex. ST, CF → 공격수 / CM, CDM → 미드필더)
3. **피처 스케일링**
4. **분류 모델 훈련**:
   - Logistic Regression
   - KNN
   - Decision Tree
5. **모델 성능 비교**:
   - Accuracy, Precision, Recall, Confusion Matrix

---

## 🛠 사용 라이브러리

- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

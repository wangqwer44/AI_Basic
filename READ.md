# 🚀 AI & Algorithm Implementation Lab

이 저장소는 딥러닝(Vision), 메타휴리스틱 최적화 알고리즘(TSP), 그리고 RAG(Retrieval-Augmented Generation) 기반의 주가 예측 시스템을 포함한 프로젝트 모음입니다.

## 📌 프로젝트 구성 및 설명

### 1. Vision Deep Learning (`Vision deep learning.ipynb`)
- **개요**: CNN(Convolutional Neural Network) 아키텍처를 설계하여 이미지 데이터를 분류하는 프로젝트입니다.
- **핵심 내용**: 
  - 데이터 전처리 및 증강(Data Augmentation)
  - Batch Normalization 및 드롭아웃을 통한 모델 최적화
  - 학습률 스케줄러(ReduceLROnPlateau) 적용

### 2. Traveling Salesman Problem (TSP) 최적화
복잡한 경로 최적화 문제를 두 가지 서로 다른 알고리즘으로 접근하여 해결합니다.
- **Genetic Algorithm (`TSP_GA_최종.ipynb`)**: 유전 알고리즘의 교차(Crossover) 및 변이(Mutation) 연산을 통해 최적의 경로를 진화적으로 탐색합니다.
- **Simulated Annealing (`202111612_왕석빈_TSP_SA.ipynb`)**: 담금질 기법을 활용하여 국소 최적해(Local Optimum)를 탈출하고 전역 최적해를 찾아가는 과정을 구현합니다.

### 3. RAG-based Stock Analysis (`RAG.ipynb`)
- **개요**: 외부 검색 결과(Google News RSS)를 LLM의 컨텍스트로 활용하여 특정 종목의 주가를 분석하는 RAG 시스템입니다.
- **특징**: 단순 학습 데이터가 아닌 최신 뉴스 데이터를 바탕으로 '오른다/내린다'를 판단하는 Prompt Engineering이 포함되어 있습니다.

---

## 🛠 Tech Stack
- **Language**: Python 3.x
- **Deep Learning**: TensorFlow, Keras
- **Optimization**: NumPy, Scikit-learn, Matplotlib
- **AI/NLP**: LangChain, LLM Integration

---

## 💻 시작하기

1. **저장소 클론**
   ```bash
   git clone
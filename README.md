# Human_Activity_Recognition

스마트폰 센서 기반 데이터를 활용한 행동 양식 분석

[Aivle 스쿨 1차 미니프로젝트]

📅 기간: 2025.04.14 - 2025.04.15

🎯 목표: 데이터 분석 및 머신러닝 모델링

🗃️ 사용 데이터: [Human Activity Recognition Using Smartphones](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)

### 🛠️ 역할

- 코드 리뷰 및 개선
- 협업 방식 제안 및 효율적 분업 유도
- 발표자료 검토 및 피드백 제공

### ⚙️ 사용 기술

Python

머신러닝: scikit-learn

딥러닝: Keras

### 🔍 주요 내용

- 스마트폰 센서 기반 데이터를 활용한 행동 양식 분석
- **다단계 행동 분류 시스템**을 구축
    - **1단계**: 정적 행동과 동적 행동 구분 (이진 분류)
    - **2단계-1**: 정적 행동(`LAYING`, `SITTING`, `STANDING`) 세부 분류
    - **2단계-2**: 동적 행동(`WALKING`, `WALKING UPSTAIRS`, `WALKING DOWNSTAIRS`) 세부 분류
- 데이터 전처리: 불필요 컬럼 제거, 정규화(MinMaxScaler), 레이블 추가(`is_dynamic`) 등 사전 처리
- 다양한 딥러닝 모델 설계 및 실험 → 최적 성능 모델 선정
- 단계별 학습 곡선 시각화 및 모델 평가 진행 (`dl_history_plot()` 활용)

### 📚 배운 점

- 분석 도중에도 프로젝트의 궁극적인 목적을 잊지 않는 것이 중요하다는 점을 체감
- 깊은 신경망 구조는 오히려 과적합을 유발할 수 있음을 경험
- 걷기(walking)와 앉아 있기(seating)와 같은 정적 행동 간의 구별이 어려움을 팀과 함께 인식
- 다른 팀원들의 작업을 보며 데이터 시각화의 중요성을 다시 한 번 느꼈고, 향후 프로젝트에서 이를 더 강화할 계획

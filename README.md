# PIPA22-Insight
오픈소스종합프로젝트 과제

## 과제 개요: 유럽 축구선수 분석 (EDA) 및 간단한 머신러닝 모델 사용

## 주요 기능
1. 리버풀 선수들의 능력치를 평가하고 부족한 포지션을 파악하여 방출 및 영입 전략 제안
2. 제안된 영입 조건에 부합하는 후보 선수들을 비교 분석하여 최적의 선수 명단 제시

## 사용된 기술
- Python 3.x
- 주요 라이브러리:
  - pandas: 데이터 처리
  - numpy: 수치 연산
  - scikit-learn: 머신러닝 모델 구현
  - matplotlib/seaborn: 데이터 시각화

## 머신러닝 모델
- 사용된 알고리즘: Random Forest Regressor
- 주요 특성:
  - 선수 나이
  - 포지션
  - 기술 능력 지표
  - 계약 상태
  - 팀 정보

## 초기 환경 설정
- vscode 접속 후 터미널 열기

- 가상환경 구축
    - py -m venv venv

- 가상환경 접속
    - venv\Scripts\activate

- 외부 패키지 설치
    - pip install numpy
    - pip install pandas
    - pip install matplotlib
    - pip install seaborn
    - pip install scikit-learn
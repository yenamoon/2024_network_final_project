# 2024_network_final_project

이 프로젝트는 Python을 활용하여 ER 네트워크와 voter 모델에 대한 분석 및 시뮬레이션에 대한 내용이다. `networkx`, `matplotlib` 등 주요 라이브러리를 사용하여 네트워크의 생성, 분석, 시각화를 수행하며, 애니메이션 기능을 통해 네트워크의 동적 변화를 표현한다.

## 프로젝트 구성
(0) module import\
(1) ER 네트워크에서의 보터 모델\
(2) ER 네트워크의 이웃수분포 + 포아송
(3) ER 네트워크의 mean geodesic distance
(4) ER 네트워크에서 p에 따른 giant component

## 주요 기능
- **네트워크 생성 및 분석**: `networkx`를 활용하여 네트워크를 모델링하고 다양한 분석 수행.
- **시각화**: `matplotlib`을 사용하여 네트워크 구조 및 데이터를 시각적으로 표현.
- **애니메이션**: 네트워크의 시간에 따른 변화를 동적으로 보여주는 애니메이션 기능 포함.

## 설치 방법
이 프로젝트를 실행하기 위한 라이브러리:
- `numpy`
- `networkx`
- `matplotlib`
- `random`
- `math`

필수 패키지를 설치 명령어:
```bash
pip install numpy networkx matplotlib random math
```
## 실행방법
1. 저장소 클론
```bash
git clone https://github.com/yenamoon/2024_network_final_project.git
```
2. Jupyter Notebook 실행
```bash
jupyter notebook 202210642_문예나_network_final_project.ipynb
```


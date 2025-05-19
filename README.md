# Split by Time: Dual Strategy for Autonomous Taxi Deployment

**EDA Project – Team 3 (박박이)**  

---

## 목차 (Table of Contents)

[프로젝트 소개]

[팀원 소개]

[사용 기술]

[전략 개요]

[사용자 요구사항]

[데이터 베이스 구성]

[주요 결과]



## 프로젝트 소개

자율주행 택시는 미래 교통 시스템의 핵심 중 하나. 하지만 언제, 어디에 우선도입 하면 좋을까?

**본 프로젝트는 '시간대별 전략적 자율주행택시 도입 방안'을 주제로,**  
1. **비심야 시간**에는 교통약자 보호 및 대중교통 불편 지역을 중심으로,  
2. **심야 시간**에는 수요와 안전성을 고려한 지역을 중심으로  
이중 전략을 통해 **도입 우선순위**를 분석했습니다.


## 팀원 소개

| 이름       | 역할                                                         |
|------------|--------------------------------------------------------------|
| 박효진 (팀장) | 버스 데이터 수집 및 전처리, 분석, DB 설계                      |
| 박태환     | 지하철 데이터 수집 및 전처리, 시각화, DB 관리                  |
| 이동연     | 인구/교통 데이터 수집 및 분석, 시각화, DB 구축                 |


## 사용 기술

| 구성 요소              | 사용 기술                                                                                                                                                  |
|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 개발 환경             | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white) ![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visualstudiocode&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) |
| 언어 / 분석 환경      | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) |
| 시각화                | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-1D2951?style=flat&logo=python&logoColor=white) ![Folium](https://img.shields.io/badge/Folium-77B829?style=flat&logo=python&logoColor=white) |
| 데이터 수집           | ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white) ![공공데이터 API](https://img.shields.io/badge/공공데이터_API-0052CC?style=flat&logo=apachespark&logoColor=white) ![서울열린데이터광장](https://img.shields.io/badge/서울열린데이터광장-0A74DA?style=flat&logo=datadog&logoColor=white) |
| 데이터베이스          | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) |
| 형상 관리 / 협업 도구 | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat&logo=confluence&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white) |



## 전략 개요

- **전략 1 – 주간 시간 (비심야)**  
  → 고령 인구 비율, 대중교통 불편 정도 등 복합 지표 기반 **자율주행 우선 도입 지역** 선정
  

- **전략 2 – 심야 시간**  
  → 심야 대중교통 공백, 치안, 심야 이동 수요 등을 고려해 **도입 대상 지역** 선정



## 사용자 요구사항

- "심야 시간의 도입 우선순위 지역이 궁금해요"  
- "송파구 점수는 어떻게 되나요?"  
- "우리 동네는 도입될까요?"

→  지역 기반 질의와 시각화로 결과 확인 가능


## 데이터 베이스 구성
![Image](https://github.com/user-attachments/assets/203360b4-a69c-4627-a06f-40157a9e990d)



## 주요 결과

### 복합지표

![Image](https://github.com/user-attachments/assets/46b0b997-93ca-4959-b0a2-897b346a288a)

  
### 복합지표 기반 Priority Map

![Image](https://github.com/user-attachments/assets/3e8e5c16-5d82-4cc7-89c3-10afb968a298)

  
### 각 구역별 Radar Chart

![Image](https://github.com/user-attachments/assets/c3c40215-5906-4760-897e-3526e8e2d4b2)

![Image](https://github.com/user-attachments/assets/ed1d7244-9752-4ecd-98a8-5e6ec51da945)


### 최우선 도입 추천 지역

![Image](https://github.com/user-attachments/assets/6b597cf6-c39c-42e4-b091-4ae8b0721f96)

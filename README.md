# 🚀 국외 뉴스데이터 크롤링 및 토픽모델링을 이용한 인공지능 분야 동향 분석

---

## 📌 프로젝트 개요 및 기대효과
- 본 프로젝트는 **최근 2년간의 인공지능 관련 미국 뉴스 기사(ABC, CNN뉴스)를 크롤링하여 데이터 수집 후, 텍스트마이닝(LDA 토픽모델링)을 통하여 인공지능의 발전 방향을 분석하는 것**을 목표로 합니다. 이를 위해 **파이썬을 기반으로 프로젝트를 진행하였고, BeautifulSoup, selenium을 사용해 크롤링을, Gensim을 통하여 LDA 토픽모델링을 수행하였습니다.**  

- 본 프로젝트를 통하여 **글로벌 AI 동향 파악, 데이터 기반의 트렌드 파악 결과 도출, 국내 산업에 적용 및 탐구 가능성 향상**의 효과를 기대합니다.
  
---

## 🛠️ 주요 기술 스택
- **사용 언어**: Python (ver 3.13.1, 3.12.7)
- **개발환경**: Anaconda 기반 VScode, Jupyter notebook
- **사용 패키지**: BeautifulSoup, selenium(웹 크롤링), pandas(데이터 전처리), spacy(자연어 전처리), gensim(LDA 토픽모델링), pyLDAvis(토픽 모델링 시각화)

---

## 👥 팀 구성 및 역할 분담
| 이름 | 역할 | 주요 업무 | 주요 기술 | GitHub 프로필 |
|------|------|----------|----------|------------|
| **유승태** | 팀장 | 일정 관리, PLC 회로 설계 및 프로그래밍 | ![PLC](https://img.shields.io/badge/PLC-XG5000-blue) ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/dawoonykim) |
| **고찬국** | 팀원 | 제어 회로 설계 및 프로그램 작성 | ![PLC](https://img.shields.io/badge/PLC-XG5000-blue) ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/Yoo-Seung-Tae) |
| **이혜린** | 팀원 | HMI 화면 설계 및 이벤트 처리 로직 구현 | ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/hyerin00)](https://github.com/KYEONGJUN-LEE) |
| **최창일** | 팀원 | HMI 보조 작업 및 발표 자료 제작 | ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) |  |
---

## 📚 개발 일정
| 마일스톤 | 목표 날짜 | 설명 |
|------------|-------------|---------------------------------|
| 준비 및 기획 | 2025-02-12 ~ 2025-02-13 | 주제 선정 및 역할 분담 |
| PLC 설계 및 연동 | 2025-02-14 | PLC 회로 구성 및 프로그래밍 (HMI 인터페이스 고려) |
| HMI 개발 및 연결 | 2025-02-18 ~ 2025-02-20 | HMI 화면 설계 및 PLC-HMI 통합 테스트 |
| 통합 테스트 및 디버깅 | 2025-02-21 ~ 2025-02-22 | 전체 시스템 점검 및 오류 수정 |
| 발표 준비 | 2025-02-23 ~ 2025-02-24 | 발표 자료 준비 및 부족한 자료 보충 |
| 최종 발표 | 2025-02-25 | 프로젝트 최종 발표 |

---

## 🔧 분석결과 및 한계점
- **수집 데이터**
    1. CNN 뉴스 ’24. 12. 27.기준 검색단어: ‘Artificial Intelligence’ 311건
    2. ABC 뉴스 ’24. 12. 24. 기준 검색단어: ‘Artificial Intelligence’ 385건
       
- **LDA 토픽모델링 분석 결과**
    - **GitHub**: 코드 및 HMI 프로젝트 관리, 이슈 트래킹  
    - **Notion**: 문서 공유 및 일정 관리
      
- **본 분석의 한계점**
    - 간헐적으로 삭제되는 등 변동성이 높은 데이터이다 보니 누락된 부분이 있을 것으로 추정
    - 기술적 진보나 발전의 측면보다 정치적 사회적인 측면이 더 강조되어 있음

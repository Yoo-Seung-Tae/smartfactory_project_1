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
| 이름 | 역할 | 주요 업무 |  GitHub 프로필 |
|------|------|----------|------------|
| **유승태** | 팀장 | 주제선정, LDA토픽모델링 모델 구축 및 분석 시행, 발표 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/Yoo-Seung-Tae) |
| **고찬국** | 팀원 | 웹 크롤링(CNN 뉴스) 시행, 토픽모델링 결과 분석 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/ChankookKo) |
| **최창일** | 팀원 | 웹 크롤링(ABC 뉴스) 시행, 토픽모델링 결과 분석 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/ckddlf050) |
| **이혜린** | 팀원 | 선행연구 시행 및 자료 작성, PPT 작성 | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/hyerin00) |

---

## 📚 개발 일정
| 마일스톤 | 목표 날짜 | 설명 |
|------------|-------------|---------------------------------|
| 사전 기획 | 2024-12-21 | 프로젝트 기획 및 주제 선정 |
| 데이터 크롤링 및 전처리 | 2024-12-23 ~ 2024-12-25 | CNN, ABC 뉴스 데이터 수집(csv 파일 수집) |
| LDA 토픽 모델링 | 2024-12-25 ~ 2024-12-27 | Python Gensim패키지 기반 LDA 토픽모델링 구현 |
| 토픽모델링 결과 해석 | 2024-12-27 ~ 2024-12-30 | 토픽모델링 분석 결과 정성적 해석 |
| PPT 작성 | 2024-12-28 ~ 2024-12-30 | 자료 종합 및 발표준비 |

---

## 🔧 분석결과 및 한계점
- **수집 데이터**
    1. CNN 뉴스 ’24. 12. 27.기준 검색단어: ‘Artificial Intelligence’ 311건
    2. ABC 뉴스 ’24. 12. 24. 기준 검색단어: ‘Artificial Intelligence’ 385건
       
- **LDA 토픽모델링 분석 결과**
    - **CNN 뉴스**: 10개의 토픽 도출
    - **ABC 뉴스**: 4개의 토픽 도출
        - Topic 1. AI분야의 여성 인력 양성 - #singh, #girls

      
- **본 분석의 한계점**
    1. 간헐적으로 삭제되는 등 변동성이 높은 데이터이다 보니 누락된 부분이 있을 것으로 추정
    2. 기술적 진보나 발전의 측면보다 정치적 사회적인 측면이 더 강조되어 있음

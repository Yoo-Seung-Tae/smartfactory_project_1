# 🚀 PLC & HMI 기반 ABC 분석 자동 분류 시스템

![PLC](https://img.shields.io/badge/PLC-XG5000-blue)
![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey)
![Ladder Logic](https://img.shields.io/badge/Ladder%20Logic-%E2%9C%94-green)
![Industrial Automation](https://img.shields.io/badge/Industrial%20Automation-%E2%9C%94-orange)

---

## 📌 프로젝트 개요
본 프로젝트는 **비효율적인 수작업 물류 관리 문제를 해결하고, 자동화된 창고 관리 시스템(AWMS)을 구축하는 것**을 목표로 합니다. 이를 위해 **XG5000 기반의 PLC 제어 시스템과 XP-Builder 기반의 HMI를 활용하여 ABC 분석을 자동화하고, 효율적인 물류 분류 및 재고 관리를 지원하는 시스템을 개발합니다.**  

이 프로젝트를 통해 창고 운영자는 **실시간으로 제품 입출고 상태를 확인하고, HMI 화면을 통해 적절한 재고 배치를 수행할 수 있습니다.**  

---

## 🛠️ 주요 기술 스택
- **PLC**: XG5000 (시뮬레이터 활용)
- **HMI**: XP-Builder (LS산전)
- **프로그래밍 언어**: Ladder Logic, FBD
- **통신 방식**: Modbus, RS-232C/RS-485, Ethernet  
  → PLC-HMI 간 **Modbus/TCP 통신을 활용하여 실시간 데이터 송수신**
- **데이터 처리**: 실시간 센서 데이터 모니터링 및 저장  

---

## 🚀 주요 기능
1. **ABC 분석 기반 자동 분류**
   - 입고된 제품의 재고 데이터를 수집하여 A, B, C 등급으로 자동 분류  
   - **주요 로직**: 출고 빈도, 보관 비용, 회전율 등의 기준을 적용하여 등급 분류
2. **HMI 인터페이스 제공**
   - XP-Builder를 활용하여 **직관적인 UI** 설계  
   - 사용자 친화적인 **터치스크린 기반 재고 관리 시스템** 구현
3. **실시간 데이터 모니터링**
   - 입출고 데이터 감지 및 시각화  
   - **Modbus 통신 기반으로 실시간 반영**
4. **PLC-HMI 통합 제어**
   - XG5000(시뮬레이터)와 XP-Builder를 연동하여 시스템 자동화 구현  

---

## 👥 팀 구성 및 역할 분담
| 이름 | 역할 | 주요 업무 | 주요 기술 | GitHub 프로필 |
|------|------|----------|----------|------------|
| **김다운** | 팀장 | 일정 관리, PLC 회로 설계 및 프로그래밍 | ![PLC](https://img.shields.io/badge/PLC-XG5000-blue) ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/dawoonykim) |
| **유승태** | 팀원 | 제어 회로 설계 및 프로그램 작성 | ![PLC](https://img.shields.io/badge/PLC-XG5000-blue) ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/Yoo-Seung-Tae) |
| **이경준** | 팀원 | HMI 화면 설계 및 이벤트 처리 로직 구현 | ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/KYEONGJUN-LEE) |
| **이혜린** | 팀원 | HMI 보조 작업 및 발표 자료 제작 | ![HMI](https://img.shields.io/badge/HMI-XP--Builder-lightgrey) | [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/hyerin00) |
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

## 🔧 프로젝트 규칙
- **Daily Scrum 방식 (매일 30분)**
    1. 어제 무엇을 했는가?
    2. 오늘 무엇을 할 것인가?
    3. 문제가 있거나 도움이 필요한 것은 무엇인가?
- **주요 협업 툴**
    - **GitHub**: 코드 및 HMI 프로젝트 관리, 이슈 트래킹  
    - **Notion**: 문서 공유 및 일정 관리  
- **팀 규칙**
    - 모든 진행 사항을 Notion에 기록  
    - 출석을 지키되, 사전에 협의 후 유연한 일정 조정 가능  
    - 협업 시 적극적인 커뮤니케이션 유지
---
## 🏆 수상 내역
-  PLC&HMI 팀 프로젝트 최우수상
  <img src="https://raw.githubusercontent.com/ProjectPLC/PLC_ABC_Logistics/main/PLC&HMI_award.png" width="600">

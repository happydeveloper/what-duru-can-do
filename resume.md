# [KOR] 이력서 (Resume)

## 강두루 (Duru Kang)
Senior Software Engineer / Tech Lead  
Email: enfn2001@gmail.com | Phone: 010-3058-0589

## Professional Summary
"비즈니스의 언어(회계)와 기술의 언어(개발)를 모두 구사하는 20년 차 엔지니어"

2006년부터 웹/앱 개발, DB 아키텍처 설계, 인프라 구축, 팀 빌딩까지 소프트웨어 엔지니어링의 전 주기를 경험했습니다.  
170만 명 규모의 글로벌 서비스(TTMIK) 기술 리딩 경험을 바탕으로, 대규모 트래픽 처리와 글로벌 결제 시스템을 안정적으로 안착시켰습니다.  
국회 및 공공기관의 미션 크리티컬 AI DB 인프라를 구축했고, 회계/세무 실무 능력을 기반으로 기술적 안정성과 사업적 효율성을 함께 달성하는 데 강점이 있습니다.

<!-- todo 기타로 빼고 한줄로 -->
## Patents (지식재산권)
- 엣지 AI 기반 복합 비주얼 코드를 이용한 디지털 콘텐츠 보정 및 연결 시스템
- 출원번호: 10-2026-0002139 (특허청)
- 출원일: 2026년 1월
- 내용: 물리적 표식(QR 등) 없이 사물의 시각적 특징을 Edge AI로 분석하여 디지털 콘텐츠를 매핑하는 O2O 기술

## Work Experience

| 회사/프로젝트 | 역할 | 기간 | 핵심 업무 및 성과 |
|---|---|---|---|
| 톡투미인코리안 (Talk To Me In Korean) <br> https://talktomeinkorean.com | 엔지니어링 팀장 | 2020.01 - 2026.03 (예정) | 170만 회원 글로벌 한국어 교육 플랫폼 기술 리딩 및 초기 팀 빌딩. 워드프레스/우커머스 커스텀 개발과 SaaS 연동 (`auth`, `brand`, `store`), Paddle + Apple IAP 구독 결제 구현, 코호트 판매 운영, `TTMIK Stories`/`Seyo`/`TTMIK Audio` 앱 인프라 구축. AWS QuickSight + Redash 데이터하우스와 Glue/Athena ETL, PayPal/Paddle/IAP 통합 매출 대시보드 구축. |
| 국립중앙박물관 (National Museum of Korea) <br> https://www.museum.go.kr | 전시안내 시스템 총괄 (계약) | 2024 - 현재 | 전시 안내 앱 및 백엔드/DB 아키텍처 총괄 설계. 운영/유지보수 체계 수립 및 안정화. 대규모 관람객 트래픽 대응 성능 튜닝과 데이터 파이프라인 최적화 수행. |
| 대한민국 국회 & 한컴AI 협력 <br> https://www.assembly.go.kr / https://www.hancom.com | AI DB 인프라 구축 | 2025.07 - 2025.09 | AI 서비스용 MySQL 3중화(Clustering) 및 Failover 구축. 민감 데이터 DB 암호화 솔루션 적용과 대용량 처리 튜닝 수행. 관련 정리: https://github.com/happydeveloper/redhat |
| 코딩온 (Coding On) <br> https://codingon.co.kr | 초기 멤버 & 개발팀 셋팅 | 2018 - 2020 | 창업 초기 멤버로 LMS 아키텍처 설계, 핵심 기능 개발, 초기 개발팀 빌딩 주도. |
<!--
todo : 제거하고, 오픈튜토리얼스 활동을 공백에 대신 추가
 | 두루옵스 (Duru Ops) | 대표 & 기술 컨설턴트 | 2018 - 2020 | 삼성전자, 현대모비스, KT, 성균관대 등 대상 DB 설계, 장애 대응, 성능 최적화 컨설팅 수행. | -->
| 패션그룹 형지 <br> https://www.hyungji.co.kr | 전산실 과장 | 2015 - 2018 | 20개 브랜드 사이트 통합 운영, ERP 연동, 외주 파트너 관리 및 운영 효율화. |
| 정원엔시스 <br> https://www.zungwon.co.kr | R&D 연구원 | 2009 - 2014 (약 7년) | WinCE/Embedded 기반 병렬 네트워크 전송 모듈 개발, DB 암호화 모듈 개발, 내부 그룹웨어 및 회계 통제 시스템 개발. |

### 2025 주요 프로젝트 및 성과
- **Paddle 결제 플랫폼 구축 및 자동 복구 시스템 개발**
  - 대규모 트래픽 환경에서 예외 케이스 방어 로직 설계
  - 결제 실패 자동 재시도/복구 로직 구현으로 결제 성공률 향상
  - Webhook 지연/네트워크 유실 상황을 고려해 멱등성(Idempotency) 설계와 Retry Queue 도입
- **이벤트 운영 기술 지원**
  - 연말 세일/프로모션 운영을 위한 할인 링크/쿠폰 자동 적용 기능 개발
  - 일정 내 안정 배포로 마케팅/운영팀 이벤트 실행 리스크 축소
- **매출 데이터 대시보드 자동화 (Redash)**
  - 수기 집계 중심 매출 데이터를 자동 수집/시각화 체계로 전환
  - 결제 채널별 매출 모니터링 및 의사결정 속도 개선
- **대용량 메일 서버(Sendy) 튜닝 및 성능 개선**
  - 마케팅 캠페인 발송 시 병목 구간 튜닝으로 처리 시간 3~5분 -> 약 10초로 단축(약 95% 개선)
  - 발송 모니터링 업무를 1시간+ -> 5분 이내로 단축해 마케팅팀의 전략 업무 집중도 향상
- **마케팅 성과 추적 체계(GTM/GA4) 구축**
  - 코스 랜딩 페이지 구축 및 유저 행동(클릭/전환) 추적 환경 세팅
  - A/B 테스트 기반의 성과 분석 체계 마련

## 초기 경력 (Early Career)
- 미래에셋증권 협력사: HTS 모듈 개발(소켓 기반 실시간 처리)
- 삼보/주현컴퓨터: 임베디드 기기 트러블슈팅
- 수원대학교 사회교육원: 홈페이지 및 학사관리 시스템 개발

## Projects & Community

### 오픈튜토리얼스 (OpenTutorials.org) | 초기 멤버 & 회계 담당
- 기간: 2015 - 현재
- 사이트: https://opentutorials.org
- 개발: 웹 서비스 백엔드 유지보수, 코딩야학 프로젝트 PM, otu.ai 모바일 개발 총괄
- 운영: 비영리 단체 회계/세무 실무 담당

### 형태소 분석/언어 AI 프로젝트
- 프로젝트: https://github.com/hyusap/deconstructor
- 설명: 언어 형태소 분석을 AI로 다루기 위해 참여/기여 후 포크하여 커스터마이징
- 한국어 버전/연동: https://deconstructor-ko-git-ko-style-opentutorials.vercel.app

### 오토커밋 프로젝트
- 프로젝트: https://github.com/happydeveloper/auto-commit-push
- 설명: Git 내부 구조 학습 및 자동 커밋/자동화 실험 프로젝트

## Education & Skills
- 학력: 수원대학교 회계학과 / 컴퓨터학과 복수전공
<!-- todo 수준이 누락됨 -->
- Skills:
  - Languages: C#, Java, Python, Node.js, PHP
  - Backend: Nust.js, Spring Boot, Restful 및 GraphQL API 설계 및 운영
  - Data/Infra: ORACLE, Tibero, SQLServer, MySQL(HA), Docker
  <!-- todo 클라우드는 세부적으로 작성 -->
  - Cloud :  
   - AWS : EC2, ECS, S3, RDB, CF, WAF, LAMBDA, API Gateway, Cognito
   - Google Cloud Platform : App Engine, Cloud SQL for MySQL 8.0, Comput Engine
   - AZure
  - Mobile: iOS/Android Native, React Native (hybrid, WebView), 
  - Payment: Paddle Payment, In-App Purchase, Revenuecat, Paypal, PaymentWall, 2CO

---

<!-- todo:  IOT, Embed programming으로 양념추가 -->
### 메이커/실험 프로젝트
- 감자 리프팅 장치 (Maker Faire 출품)
- BU 프로젝트(전자공학도 팀 활동)
- 중력가속도 측정 장치
- 전압/전류 측정 및 제어 장치
- RFID/WiFi 기반 출입 관리 실험 프로젝트

## 커뮤니티/지식 공유
<!-- 레퍼런스를 명확하게 첨부 -->
- 생활코딩 강좌 기여(자바 등)
- 기술서적 검토 참여(예제 중심 Python3)

## 학력/기타
- 수원대학교 컴퓨터학과 / 회계학과 복수전공
- 교육: Spring/JSP-Servlet/Tibero 실무 교육 이수
- 자격: MCT (Windows Server 2003 Hosting)

## 일하는 방식
- 빠른 구현보다 운영 가능한 구조로 끝까지 완성합니다.
- 데이터 정합성과 사용자 신뢰를 우선으로 의사결정합니다.
- 배운 내용을 문서/코드/강의로 공유해 팀 생산성을 높입니다.
- 원활한 의사소통을 바탕으로 문제 해결 과정에서 팀원 의견을 조율하고 합리적인 결론을 도출합니다.
- 팀원별 강점을 파악해 적재적소에 업무를 배분하고, 다양한 상황에서 갈등을 예방/해결합니다.
- 비즈니스 목표 달성과 업무 효율 향상을 위해 새로운 기술과 방식을 적극적으로 시도합니다.
- 논리적이고 수평적인 업무 문화를 지향하며, 역할과 책임을 투명하게 정리합니다.
- 서비스 전체 아키텍처를 조망하고, 중장기 기술 로드맵을 제시해 실행까지 연결합니다.


# AI Project Planning
Agentic AI · RAG · 사회문제 해결 중심 기획 포트폴리오

**Agentic AI와 RAG 기술을 활용해 일상·지역·사회 문제를 해결하는 AI 서비스 기획 프로젝트**를 정리한 포트폴리오입니다.  
단순 아이디어 제안이 아닌, **명확한 타깃 · 기획 배경 · 기술 스택 · 실행 가능한 기능 설계**에 초점을 두었습니다.

---

## Projects Overview

### 1. AI 음성 기반 가족형 안부 케어콜 + 감정 돌봄  
**사회복지 × 헬스케어**

#### Problem
- 독거노인 증가와 가족 돌봄 공백 심화
- 기존 안부콜 서비스는 단순 생존 확인 수준
- 정서·인지 변화 조기 감지 시스템 부재

#### Solution
AI가 매일 음성으로 안부를 묻고, 대화 내용을 분석해  
감정·인지 변화를 감지하고 가족·복지사에게 알림을 제공하는  
**개인화된 음성 돌봄 서비스**

#### Target
- 75세 이상 독거노인
- 30~50대 자녀 세대
- 지자체 및 복지기관

#### Tech Stack
- RAG: Pinecone, Azure AI Search  
- AI: 한국어 음성 인식, 감정 분석 모델  
- Voice: 전화 / 카카오톡 음성 API  
- Data: 보건복지부, 치매안심센터 공공 데이터

#### Key Features
- 자동 음성 안부 통화
- 감정·인지 변화 탐지 및 알림
- 가족 사진·기억 기반 개인화 대화
- 추억 회상, 퀴즈 등 정서·인지 케어 콘텐츠
- 가족·복지사용 모니터링 대시보드

---

### 2. AI 스마트 팜 코치  
**농업 × RAG × Vision × IoT**

#### Problem
- 농촌 고령화 및 인력 부족
- 병충해·관수·출하 시점 판단의 어려움
- 고가 스마트팜 솔루션의 접근성 문제

#### Solution
작물 사진과 간단한 질문만으로  
병충해 진단부터 농사 일정, 출하 타이밍까지 지원하는  
**소규모 농가 맞춤형 AI 농업 코치**

#### Target
- 소규모 농가
- 스마트팜 초보 농부
- 농업 협동조합

#### Tech Stack
- RAG: Pinecone (농촌진흥청 데이터)
- Vision: CLIP 등 이미지 분석 모델
- Cloud: AWS / Azure FarmBeats
- Drone & IoT: DroneDeploy, John Deere API

#### Key Features
- 작물 사진 기반 병충해 진단
- 토양·기후 센서 실시간 모니터링
- 자동 농사 일정 관리
- 기후 반영 관수·방제 알림
- 시장 가격 예측 및 출하 타이밍 추천

---

### 3. AI 감정 기반 웰빙 코치 & 스케줄러  
**일정관리 × 멘탈 헬스케어**

#### Problem
- 직장인·육아 세대 번아웃 증가
- 일정 관리 도구에 감정 요소 부재
- 사후 대응 중심의 멘탈 케어 한계

#### Solution
사용자의 감정 상태를 이해하고  
일정을 재구성하며 예방적 웰빙 코칭을 제공하는  
**감정 중심 AI 스케줄러**

#### Target
- 30~40대 직장인
- 육아 세대
- 기업 복지 프로그램 (B2B)

#### Tech Stack
- RAG: 캘린더 데이터 + 심리학 논문 + 공공 자료
- API: Google Calendar, Microsoft Graph
- Emotion Analysis: AWS Comprehend, Azure Text Analytics
- Generative AI: Azure OpenAI

#### Key Features
- 감정 입력 기반 일정 재배치
- 번아웃 패턴 분석 및 알림
- 맞춤형 웰빙 코칭
- 생성형 AI 기반 긍정 시나리오 제공
- 조직 단위 익명 웰빙 리포트

---

### 4. AIoT 기반 지속가능 에너지 관리 플랫폼  
**에너지 × IoT × Agentic AI**

#### Problem
- 농가·가정 에너지 비용 증가
- 탄소 중립 정책 대응 필요
- 수동적 에너지 관리의 한계

#### Solution
AI가 에너지 사용을 분석하고  
기기를 자율 제어해 에너지 절감과 탄소 감축을 수행하는  
**Agentic AI 기반 에너지 관리 플랫폼**

#### Target
- 농가 및 가정
- 지자체·환경 관련 기관

#### Tech Stack
- AIoT: Azure IoT Edge, AWS Greengrass
- RAG: Chroma DB (기후·정책 데이터)
- Agentic AI: Llama 기반 모델
- Blockchain: 탄소 크레딧 스마트 컨트랙트

#### Key Features
- 실시간 에너지 소비 분석
- 스마트 기기 자동 제어
- 전기 절감 플랜 자율 실행
- 스마트 그리드 연동
- 탄소 크레딧 계산 및 거래

---

### 5. AI 개인화 쇼핑 에이전트  
**쇼핑 × Agentic AI × AR**

#### Problem
- 선택 과잉으로 인한 쇼핑 피로
- 지역 소상공인 정보 접근성 부족
- 건강·예산 고려 소비 니즈 증가

#### Solution
쇼핑을 직접 고르는 대신  
AI가 대신 계획·추천·주문까지 수행하는  
**개인화 쇼핑 에이전트**

#### Target
- 바쁜 직장인·가족
- 지역 소상공인 상점

#### Tech Stack
- Agentic AI: LangChain
- RAG: Pinecone (사용자·상점 데이터)
- Cloud: Azure AI Search
- AR: ARCore, ARKit

#### Key Features
- 자연어 기반 쇼핑 요청
- 맞춤 쇼핑 리스트 생성
- 자동 주문·장바구니 연동
- AR 냉장고 시뮬레이션
- 소상공인 수요 예측 리포트

---

### 6. AI 투자 의사결정 어시스턴트  
**금융 × 뉴스 × 시뮬레이션**

#### Problem
- 투자 정보 과잉
- 뉴스 해석과 행동 사이의 간극
- 즉각적 의사결정 도구 부재

#### Solution
뉴스를 요약하고  
바로 행동 가능한 선택지를 제공하는  
**투자 의사결정 보조 AI**

#### Target
- 개인 투자자
- 바쁜 직장인 투자자

#### Tech Stack
- AI Summary: Azure Cognitive Services
- Chatbot: Dialogflow
- Data: 금융 뉴스 API
- Trading: 증권사 Open API

#### Key Features
- 실시간 뉴스 3줄 요약
- 매수·보유·매도 액션 버튼
- 미래 시나리오 시뮬레이션
- 리스크–리턴 점수화

---

### 7. AI 감정 일기 분석기  
**멘탈 헬스 × 생성형 AI**

#### Problem
- 일상적 감정 관리의 어려움
- 상담 접근성 한계
- 개인 기록 기반 멘탈 케어 수요 증가

#### Solution
일기를 분석해 감정 패턴을 시각화하고  
개인 맞춤 멘탈 케어를 제공하는  
**AI 감정 기록 분석 서비스**

#### Target
- 직장인·학생
- 상담소·복지기관

#### Tech Stack
- RAG: LangGraph
- Emotion Analysis: Azure Cognitive Services
- Generative AI: Azure OpenAI
- Voice: ElevenLabs

#### Key Features
- 텍스트·음성 일기 분석
- 감정 패턴 시각화
- 맞춤형 조언 제공
- 긍정 미래 시나리오 생성
- 지역 단위 멘탈 통계 리포트

---

## Keywords
Agentic AI · RAG · AI Service Planning · Social Impact · Healthcare · Agriculture · Energy · Finance


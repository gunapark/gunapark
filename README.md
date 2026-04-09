# 박건아 | AI Developer

**FastAPI 기반 AI 서비스를 모델 설계부터 Docker·CI/CD 배포까지 직접 담당하는 AI 개발자입니다.**
재무지표 예측 서비스에서 R² 0.665·LLM 응답 55초→12초 달성, RAG 파이프라인 3개 프로젝트 실전 구현, 합성음성탐지 EER 7.38%→0.04% 개선까지 수치로 검증했습니다.

📄 [포트폴리오 전체 보기](https://harvest-hollyhock-56b.notion.site/AI-Developer-33ddf32efa7e80bd8554e0e7b84c2240)

---

## 🚀 Projects

### 재무지표 예측 AI 서비스 (2025.12 ~ 2026.02)
`Python` `FastAPI` `XGBoost` `SHAP` `OpenAI API` `Docker` `GitHub Actions` `Azure` `AWS`

- KOSPI/KOSDAQ 2,422개 기업 재무지표 예측 + AI 분석 보고서 자동 생성
- RF·LSTM·XGBoost 비교 실험 후 XGBoost 선정, Optuna 튜닝으로 **R² 0.665** 달성
- LLM 17회 순차 호출 → asyncio 병렬처리 전환으로 **55초 → 12초 (78% 단축)**
- Docker + GitHub Actions CI/CD → Azure App Service + AWS EC2 **듀얼 클라우드 자동 배포**

### 합성음성 탐지 연구 (2025.09 ~ 2025.12)
`Python` `PyTorch` `WavLM` `Nes2Net` `Hugging Face`

- AASIST3 vs Nes2Net 논문 비교 후 연산 효율 기준으로 Nes2Net 선정
- 한국어 TTS 3종(GPT·Google·Coqui)으로 합성 데이터 12,000개 직접 구축
- 파인튜닝으로 **EER 7.38% → 0.04%** 달성

### 논문 이미지 수집 파이프라인 (2025.03 ~ 2025.09)
`Python` `Kafka` `MySQL` `AWS S3`

- 학술 논문 PDF에서 이미지 자동 수집·전처리·생성까지 전체 파이프라인 구축
- 배치 처리 지연 문제 → Kafka 도입으로 각 단계 토픽 기반 **비동기 병렬처리** 전환
- 이미지는 AWS S3, 메타데이터는 MySQL에 저장하는 확장성 있는 스토리지 구조 구성

### 반려동물 동반 앱 AI 기능 (2025.03 ~ 2025.09)
`Python` `FastAPI` `LangChain` `FAISS` `Gemini API`

- 펫로스 증후군 사용자를 위한 반려동물 동반 애플리케이션 AI 기능 담당
- 외부 의존도를 낮추기 위해 LangChain+FAISS 선택, RAG 기반 반려동물 전문 챗봇 구현
- RAG 응답 시간 **2분 → 20~30초** 단축 (청크 크기·임베딩 전처리 최적화)

### AI 기반 일정관리 웹 (2024.12 ~ 2025.02)
`JavaScript` `Node.js` `Gemini API`

- 감정 분석·맞춤형 목표 추천 기능을 갖춘 AI 일정관리 웹 서비스
- Node.js 백엔드 API 개발 및 Render 자동화 배포 구성

### 광고·유튜브 채널 AI 매칭 서비스 (2024.08 ~ 2024.12)
`Python` `FastAPI` `Pinecone` `OpenAI API` `AWS`

- 유튜브 채널 1,600개 수집 → OpenAI 임베딩 → Pinecone 벡터 검색으로 양방향 AI 매칭
- **Human Evaluation 매칭 정확도 88.5%** 달성

---

## 🛠️ Skills

| 분류 | 기술 |
| --- | --- |
| AI / ML | PyTorch, XGBoost, SHAP, LangChain, Hugging Face, OpenAI API |
| Backend | FastAPI, Uvicorn, Node.js |
| Infra / DevOps | Docker, GitHub Actions, AWS (EC2·S3), Azure (App Service·ACR), Kafka |
| Database | MySQL, Pinecone, FAISS |

---

## 🏆 Awards & Certification

| 날짜 | 수상 | 주최 |
| --- | --- | --- |
| 2026.03 | AIVLE Big Project 우수상 | KT, 고용노동부 |
| 2025.10 | AICE Associate (100점) | KT, 한국경제신문 |
| 2025.02 | 코드잇 부스트 데모데이 최우수상(2등) | 코드잇 |

---

📧 ncc0816@gmail.com

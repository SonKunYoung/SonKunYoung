동국대학교 정보통신공학전공

## 🚀 Projects

### 👁️ 아이즈온(Eyes-On) — 시각장애인 보행 보조 웨어러블 · [VIAssist-Edge](https://github.com/VIAssist-Edge)
> 에스컬레이터 방향, 엘리베이터 문 상태, 장애물을 접촉 전에 음성으로 안내하는 착용형 AI 시스템 (한이음 드림업)

- Jetson Orin Nano 한 대에서 **YOLO(33클래스) → Optical Flow 방향 판정 → 규칙/VLM 라우터 → STT/TTS**를 전부 오프라인으로 처리
- VLM 출력을 그대로 쓰지 않고 YOLO·Flow 메타데이터와 대조하는 안전 검증 + 결정적 fallback 구조
- `Python` `YOLO` `OpenCV` `SmolVLM` `llama.cpp` `faster-whisper` `MeloTTS` `Flask` `Jetson`
- 📂 [VIAssist_Total](https://github.com/VIAssist-Edge/VIAssist_Total) · [vlm](https://github.com/VIAssist-Edge/vlm) · [YOLO_pipeline](https://github.com/VIAssist-Edge/YOLO_pipeline) · [Optical-flow](https://github.com/VIAssist-Edge/Optical-flow)

### 🏠 자연어 기반 스마트홈 AIoT 제어 시스템 — 졸업 캡스톤 · [Capstone-Edge](https://github.com/Capstone-Edge)
> "나비야, 에어컨 켜줘" 같은 자연어 명령으로 가전을 제어하고 3D 시뮬레이터에 실시간 반영

- **Edge**: Jetson에서 VAD → Whisper STT → 호출어 인식 → gTTS 응답
- **Backend**: 자연어 해석 → 명령 실행 → MySQL 상태 갱신 → WebSocket 동기화, 모호한 명령 재질문
- **Frontend**: React Three Fiber 3D 집 시뮬레이터 + 대화 패널
- `FastAPI` `MySQL` `SQLAlchemy` `WebSocket` `React` `TypeScript` `three.js` `Whisper`
- 📂 [Edge](https://github.com/Capstone-Edge/Edge) · [Backend](https://github.com/Capstone-Edge/Backend) · [Frontend](https://github.com/Capstone-Edge/Frontend) · [발표자료](https://github.com/Capstone-Edge/Edge_SmartHome_AIoT_Materials)

### 💱 KB TradeTwin — KB국민은행 제8회 AI Challenge · [KB-TradeTwin](https://github.com/KB-TradeTwin)
> 수출 중소기업의 계약서·인보이스로 미래 외화 현금흐름을 만들고, 환율 시나리오별 위험을 계산해 헤지 전략을 근거와 함께 제시

- 환율을 예측하지 않고, **금융 계산은 LLM 없이 결정론적 엔진(`Decimal`)으로** 처리
- Moving block bootstrap 10,000 경로로 CFaR·Expected Shortfall 산출, 설명은 엔진이 만든 숫자만 인용하도록 검증
- 테스트: backend pytest 1,483개 · frontend vitest 652개
- `FastAPI` `Next.js` `Docker Compose` `pytest` `vitest`
- 📂 [kb-tradetwin](https://github.com/KB-TradeTwin/kb-tradetwin)

### 📈 연금 계산기 · [pension-app](https://github.com/SonKunYoung/pension-app)
> 예상 연금과 노후 자산을 계산하고 부부 합산, 동년배 비교, 연봉 검색까지 제공하는 웹앱

- `Next.js` `React` `TypeScript` `Tailwind CSS` `Chart.js`


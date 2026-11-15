동국대학교 정보통신공학전공

## Projects

### 아이즈온(Eyes-On) — 시각장애인 보행 보조 웨어러블
한이음 드림업 · [VIAssist-Edge](https://github.com/VIAssist-Edge)

에스컬레이터 방향, 엘리베이터 문 상태, 장애물을 접촉 전에 음성으로 안내하는 착용형 AI 시스템입니다.

- Jetson Orin Nano 한 대에서 YOLO 탐지, Optical Flow 방향 판정, 규칙/VLM 라우터, 음성 입출력을 모두 오프라인으로 처리
- VLM 출력을 YOLO·Optical Flow 결과와 대조해 검증하고, 실패 시 규칙 기반 안내 문장으로 대체
- 레포: [VIAssist_Total](https://github.com/VIAssist-Edge/VIAssist_Total) · [vlm](https://github.com/VIAssist-Edge/vlm) · [YOLO_pipeline](https://github.com/VIAssist-Edge/YOLO_pipeline) · [Optical-flow](https://github.com/VIAssist-Edge/Optical-flow)

### 자연어 기반 스마트홈 AIoT 제어 시스템
졸업 캡스톤 · [Capstone-Edge](https://github.com/Capstone-Edge)

자연어 음성 명령으로 가전을 제어하고, 바뀐 상태를 3D 시뮬레이터에 실시간으로 반영하는 시스템입니다.

- Edge: Jetson에서 발화 감지, 음성 인식, 호출어 확인 후 음성으로 응답
- Backend: 자연어 해석, 명령 실행, 기기 상태 저장, 실시간 동기화, 모호한 명령 재질문
- Frontend: 3D 집 시뮬레이터와 대화 패널
- 레포: [Edge](https://github.com/Capstone-Edge/Edge) · [Backend](https://github.com/Capstone-Edge/Backend) · [Frontend](https://github.com/Capstone-Edge/Frontend) · [발표자료](https://github.com/Capstone-Edge/Edge_SmartHome_AIoT_Materials)

### KB TradeTwin — 수출 중소기업 환위험 의사결정 지원
KB국민은행 제8회 AI Challenge · [KB-TradeTwin](https://github.com/KB-TradeTwin)

계약서·인보이스로 미래 외화 현금흐름을 구성하고, 환율 시나리오별 위험을 계산해 헤지 전략을 근거와 함께 제시하는 서비스입니다.

- 환율을 예측하지 않고, 금융 계산은 LLM 없이 결정론적 엔진으로 처리
- 환율 경로 10,000개 시뮬레이션으로 유동성 위험지표 산출
- 설명 문장은 엔진이 계산한 숫자만 인용하도록 검증
- 레포: [kb-tradetwin](https://github.com/KB-TradeTwin/kb-tradetwin)

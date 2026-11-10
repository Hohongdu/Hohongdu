### 안녕하세요, 생성형 AI 서비스 개발자 Hohongdu입니다 👋

AI가 낸 결과뿐 아니라 **그 결과를 재는 기준까지 검증**하고, 모델을 실제 서비스에 연결하는 일을 합니다.
KT Cloud TECH UP 2기 생성형 AI 과정을 수료했고(2026.03 ~ 10), 통합 프로젝트 '뭉치'로 대상을 받았습니다.

## 프로젝트

| 프로젝트 | 내용 | 맡은 일 |
|---|---|---|
| [뭉치 · MoongCheap-AI](https://github.com/V-MoongCheap/MoongCheap-AI) | 수요 집결형 AI 공동구매 플랫폼 (7개 직군 16인, **대상**) | 판매자 매칭·낙찰 판정 엔진(조건 게이트 5종과 총액 최저 순위로 판정, 판정 사유도 규칙·템플릿으로 생성), 판매자 수요 분석 고정 평가셋 100건과 채점기, API 계약(JSON 스키마)·백엔드 연동 문서, FastAPI·Docker |
| [InTheBrain](https://github.com/OOB-Out-of-Brain/OOB_InTheBrain_v2) | 뇌 CT 출혈 검출·판독 보조 (5인) | 불균형 데이터 평가 기준 재설계(출혈 recall, 병변 슬라이스 Dice), 재학습 설계, LLaMA 3.2 Vision 판독 보조 리포트, RAG 답변 개선 |
| [chiwawa](https://github.com/hekim-cse/chiwawa) | AI 여행 일정 플래너 (5인) | 팀의 유일한 프론트엔드(Flutter/Riverpod), AI 경로 최적화 결과 화면 |
| [company-site](https://github.com/Hohongdu/company-site) | 의뢰받은 기업 웹사이트 (ENERMADE) — 현재 운영 보류 중 | Express 5·EJS·MySQL 풀스택, 세션 인증·CSRF, 카카오페이 결제 연동(테스트 모드), Raspberry Pi 5 + Nginx + PM2 자체 배포·운영 문서 |
| [LastDance](https://github.com/Hohongdu/LastDance) | 물품 대여 앱 (팀) | Expo/React Native, 지도 API, 채팅방, 카메라, Expo 푸시 알림 |

## 기술

- **AI·데이터:** Python, PyTorch, FastAPI, LLM, RAG, Ollama, pytest
- **웹·앱:** TypeScript/JavaScript, Node.js(Express), MySQL, PostgreSQL, Flutter, React Native(Expo)
- **배포·협업:** Docker, Nginx, PM2, Jenkins, Git/GitHub
- **AI 개발 도구:** Claude Code, Codex CLI, Figma MCP — 세 도구를 묶은 멀티 에이전트 오케스트레이터를 직접 만들어 사용

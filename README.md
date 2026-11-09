# Sun & Moon

**Backend Developer** — 서비스를 나누고, 이어 붙이고, 운영하는 시스템을 만듭니다.
설계 결정은 ADR 로 남기고, AI Agent 와 함께 개발하는 방식을 규칙으로 정리하고 있습니다.

## 대표 프로젝트

### [sun-moon-java-platform](https://github.com/schware/sun-moon-java-platform)
매장 주문·주방·매출 시스템. 손님 주문(QR·앱·키오스크)부터 POS·주방 화면·매출까지를
Spring Boot 서비스 6개, Netty Device Server, React 단말 화면, Electron 매장 셸로 나누어 만들었습니다.
설계 결정 15편을 ADR 로 남겼습니다.
`Java 21` `Spring Boot` `Netty` `PostgreSQL` `Redis` `React` `TypeScript` `Electron` `Docker`

### [AI-Native-Development-Rules](https://github.com/schware/AI-Native-Development-Rules)
AI Agent 와 함께 개발할 때, 사람의 요청·AI 의 제안·사람의 결정 사이에 경계를 세우는 규칙입니다.
결정을 채팅 속에 묻지 않고 기록으로 남기는 방법을 v0.5 까지 다듬었고, 아래 프로젝트에 적용하고 있습니다.

### [aidev-KEDP001](https://github.com/schware/aidev-KEDP001)
한국 경제 데이터 플랫폼. 한국은행 ECOS·KOSIS·공공데이터포털의 공식 통계를 수집해 보여 줍니다.
위 규칙을 적용해 만든 프로젝트입니다.
`Go` `Rust` `gRPC` `TypeScript` `PostgreSQL` `Docker`

## 기술

- **Backend**: Java 21, Spring Boot 3, Netty, Go, REST, WebSocket, gRPC
- **Data**: PostgreSQL (JSONB, postgres_fdw), Redis
- **Frontend · Client**: React, TypeScript, Electron
- **운영**: Docker, Debian, nginx

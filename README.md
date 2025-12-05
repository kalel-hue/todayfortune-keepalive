# TodayFortune Keep-Alive

Render 백엔드 서버를 슬립 모드로 전환되지 않도록 유지하는 GitHub Actions 워크플로우입니다.

## 작동 방식

- 5분마다 자동으로 Render 백엔드의 `/api/health` 엔드포인트를 호출합니다
- Render는 외부 요청을 받아 활성 상태를 유지합니다

## 설정

이 저장소는 Public 저장소로 생성되어 GitHub Actions를 무제한 무료로 사용할 수 있습니다.

## 백엔드 URL

- Health Check: `https://todayfortunebackend.onrender.com/api/health`


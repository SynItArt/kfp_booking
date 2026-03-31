# KFP Export 미팅 예약 페이지

한국재무설계(주) KFP Export 사업부 · 해외 바이어 발굴 상담 예약 시스템

## 🔗 Live URL
https://synitart.github.io/kfp_booking/

## 📋 기능
- Zoom 비대면 / 대면 방문 미팅 선택
- 주간 시간표에서 가능한 시간 선택
- 예약 확정 시 SMS(모바일) 또는 이메일(PC)로 알림 발송

## 🔧 시간 차단 방법
`index.html` 파일 내 `BLOCKED_SLOTS` 배열에 차단할 시간을 추가:
```javascript
const BLOCKED_SLOTS = [
  '2026-04-01 09:00',
  '2026-04-01 13:00',
  // 추가...
];
```

## 🚀 배포 방법
1. GitHub Pages 활성화: Settings → Pages → Source: main branch
2. 자동 배포됨: https://synitart.github.io/kfp_booking/

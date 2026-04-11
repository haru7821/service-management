# Vantive Technical Service v3.1
로그인 없이 개인 거래처 설정으로 데이터 필터링

## 사용 방법
1. GitHub Pages URL 접속
2. 첫 접속 시 **이름 입력 + 담당 거래처 선택** 화면 자동 표시
3. 저장 후 선택한 거래처 데이터만 표시
4. 상단 **⚙ 설정** 버튼으로 언제든 변경 가능

## Firebase 설정
Realtime Database 규칙:
```json
{ "rules": { ".read": true, ".write": true } }
```

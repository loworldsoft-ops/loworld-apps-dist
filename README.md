# 로월드소프트 앱 배포 센터 (LoworldSoft App Distribution Portal)

로월드소프트 모바일 안드로이드 애플리케이션 공식 배포 및 테스트 포털입니다.

- 🌐 **웹 배포 사이트**: https://loworldsoft-ops.github.io/loworld-apps-dist/
- 📱 **지원 기기**: Android 8.0 (API 26) 이상 스마트폰 및 태블릿

## 등록된 애플리케이션

1. **스토리리더 (Story Reader)** `v0.3.1` (Build 4)
   - 독자의 선택과 상태값에 따라 문장이 다르게 엮이는 인터랙티브 무협 서사 리더
   - 완전한 오프라인 구동 (무협 2권 및 도감 20종 내장)
2. **스토리매스 (Story Math)** `v1.2.0` (Build 8)
   - 초등 1~6학년 수학 교과과정을 탐험과 모험으로 풀어가는 인터랙티브 스토리 수학 게임
   - 12막 146단원 전수 커리큘럼 완비

## 배포 및 업데이트 방법

`loworld-workspace`에서:
```bash
npm run deploy:portal
```
자동으로 최신 빌드된 APK를 복사하고 Release에 업로드한 뒤 웹 포털을 갱신합니다.

# DR-0001 · GitHub 초기 운영 환경

- 상태: Accepted (인프라 구축 범위에 한함)
- 승인자: GitHub 관리자 serithemage인 사용자, Codex 대화에서 구축 승인
- 시행일: 2026-11-24

## 배경

AMC의 기록·의사결정·업무 추적과 공개 안내를 분리할 초기 환경이 필요합니다.

## 검토 대안

- 단일 공개 저장소: 비공개 기획과 공개 자료가 섞일 위험이 있습니다.
- 유료 도구 및 독립 플랫폼: 초기 무료 구축 범위를 넘습니다.
- 비공개 운영·공개 커뮤니티·공개 웹 저장소 분리: 이번 승인 범위와 정보 경계에 맞습니다.

## 결정과 근거

`ai-makers-community`에 operations(Private), community(Public), website(Public)를 사용합니다. Issues·Projects·Discussions·Decision Records·PR·Issue Forms·최소 권한 Actions·Pages를 구성합니다. 회원에게 GitHub 사용을 강제하지 않습니다.

유료 전환, 외부 초대, AWS 연결·리소스 생성, 카카오톡 봇 구현·배포는 제외합니다. 운영 정책의 초안과 역할·신고 경로·개인정보 보관 기간·행사 일정은 별도 확정이 필요합니다.

## 재검토 조건

운영진 구성, 비용 발생 기능 추가, 개인정보 처리 범위 변경 또는 첫 90일 회고 시 재검토합니다. 이번 기록으로 미확정 정책을 승인하지 않습니다.

## 관련 링크

- Discussion: https://github.com/ai-makers-community/community/discussions/1
- 구축 Issue: https://github.com/ai-makers-community/community/issues/2
- Pull Request: https://github.com/ai-makers-community/community/pull/4

# Sendy 대용량 메일 시스템 성능 개선

## Summary

마케팅 CRM 캠페인 발송을 위한 Sendy 기반 대용량 메일 시스템의 병목을 분석하고 성능을 개선한 프로젝트입니다.

## Context

마케팅 캠페인 발송 과정에서 작업 생성과 처리 속도가 느려 운영 효율이 떨어지고 있었습니다.

## Problem

- 대량 메일 발송 시 작업 처리 시간이 길어 캠페인 실행 속도가 저하되었습니다.
- 운영자가 발송 상태를 확인하고 대기하는 데 많은 시간이 소요되었습니다.
- 캠페인 즉시성과 운영 효율에 영향을 주었습니다.

## My Role

- Sendy 서버 성능 병목 분석
- 서버 및 애플리케이션 설정 튜닝
- 실제 운영자의 사용 흐름 기준으로 성능 개선 검증

## What I Built / Improved

- Sendy 서버 환경 점검 및 병목 구간 분석
- DB 및 서버 설정 최적화
- 대량 발송 작업 처리 속도 개선
- 운영 모니터링 및 확인 절차 정리

## Tech Stack

Sendy, PHP, MySQL, Linux, AWS EC2, Email Delivery Infrastructure

## Impact

- 발송 작업 처리 시간을 기존 3~5분대에서 약 10초 내외로 단축
- 약 95% 이상의 처리 시간 개선
- 마케팅팀의 캠페인 운영 대기 시간 감소
- 반복적인 발송 운영 업무를 1시간 이상에서 5분 이내로 단축하는 데 기여

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

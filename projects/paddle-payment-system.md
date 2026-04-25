# Paddle 글로벌 결제 시스템 구축 및 안정화

## Summary

Talk To Me In Korean의 글로벌 구독 결제 환경을 Paddle 기반으로 전환하고, Kajabi 및 외부 결제 시스템과의 연동을 안정화한 프로젝트입니다.

## Context

글로벌 한국어 교육 플랫폼에서 구독 결제, 원타임 결제, Kajabi 오퍼 부여, 고객 복구 흐름이 함께 운영되고 있었습니다.

## Problem

- 결제 완료, 연락처 생성, 오퍼 부여, 구독 권한 반영이 여러 외부 시스템에 걸쳐 있었습니다.
- Webhook 지연, 네트워크 실패, 중복 이벤트, 외부 SaaS 자동화 실패 등 실제 운영 예외 케이스가 많았습니다.
- 결제 오류는 고객 경험 저하, CS 증가, 매출 누락으로 이어질 수 있었습니다.

## My Role

- 결제 시스템 실무 오너
- Paddle Checkout, Webhook, Kajabi 연동 구조 설계 및 구현
- 장애/예외 케이스 분석 및 자동 복구 로직 설계
- 운영팀, 고객지원팀, 마케팅팀과 협업해 결제 운영 프로세스 정리

## What I Built / Improved

- Paddle Checkout 연동 및 구독 결제 플로우 구현
- Kajabi 연락처 생성 및 오퍼 부여 연동
- Webhook 기반 결제 이벤트 처리 구조
- AWS SQS 기반 순차 처리 및 재시도 구조
- 멱등성 기반 중복 이벤트 방어 로직
- 결제 실패 또는 외부 연동 실패 케이스를 탐지하고 복구하는 Auto-recovery 로직
- Sentry 및 커스텀 로그 기반 결제 흐름 추적 체계

## Tech Stack

Paddle Payment API, Paddle.js, Webhook, AWS SQS, AWS Lambda, Kajabi API, PayPal, Apple IAP, Sentry, JavaScript/TypeScript, PHP, WordPress/WooCommerce

## Impact

- 약 8,000~9,000건 이상의 결제 트랜잭션을 안정적으로 처리
- 자동 복구 로직 도입 이후 결제 누락 및 오류를 0% 수준으로 운영
- 결제 실패로 이어질 수 있는 케이스를 시스템이 자동 수집·복구하도록 개선
- CS 대응 시간을 줄이고 글로벌 결제 운영 안정성 확보

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

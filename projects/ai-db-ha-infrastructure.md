# AI/DB 고가용성 인프라 구축 — 국회 & 한컴AI 협력

## Summary

AI 서비스 운영에 필요한 데이터베이스 고가용성, 보안성, 장애 대응 구조를 구축한 프로젝트입니다.

## Context

AI 서비스 운영에 필요한 데이터베이스 인프라의 안정성, 보안성, 고가용성 확보가 필요했습니다.

## Problem

- AI 서비스 데이터 처리를 위한 안정적인 DB 클러스터링 구성이 필요했습니다.
- 민감 데이터 보호와 장애 대응을 고려한 인프라 설계가 필요했습니다.
- Red Hat 계열 환경에서 재현 가능한 설치 및 운영 절차가 필요했습니다.

## My Role

- MySQL 클러스터링 및 Failover 구성
- DB 암호화 솔루션 적용
- 운영 절차 정리 및 실습 환경 구성

## What I Built / Improved

- MySQL 3중화 클러스터링 구조
- 장애 대응을 위한 Failover 구성
- DB 암호화 적용
- Red Hat 기반 설치 및 운영 문서 정리
- Docker 기반 사전 실습 환경 구성

## Tech Stack

MySQL, MariaDB/Galera, Red Hat Enterprise Linux, Docker, DB Encryption, Linux, Shell Script

## Impact

- AI 서비스용 DB 인프라의 가용성과 보안성 강화
- 실제 운영 환경 적용 전 실습 및 검증 절차 마련
- 장애 대응 가능한 DB 운영 기반 구축

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

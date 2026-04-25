# 매출 데이터 파이프라인 및 Redash 대시보드 구축

## Summary

Paddle, PayPal, Apple IAP 등 여러 결제 채널의 데이터를 통합 수집하고 Redash 기반 매출 분석 환경을 구축한 프로젝트입니다.

## Context

결제 채널별 데이터가 분산되어 있어 매출 분석과 의사결정에 시간이 많이 소요되었습니다.

## Problem

- 결제 채널별 데이터 구조가 달라 통합 분석이 어려웠습니다.
- 일별/주별/월별 매출, 상품별 매출, 신규/재구매 고객 분석이 수작업에 의존했습니다.
- 마케팅 캠페인과 프로모션 성과를 빠르게 확인하기 어려웠습니다.

## My Role

- 데이터 파이프라인 설계 및 구축 담당
- 결제 데이터 수집/정제/분석 구조 설계
- Redash 기반 매출 대시보드 구축
- 운영팀과 경영진이 사용할 수 있는 지표 설계

## What I Built / Improved

- Paddle, PayPal, Apple IAP 매출 데이터 수집 파이프라인
- S3 기반 원천 데이터 저장 구조
- AWS Glue/Athena 기반 ETL 및 분석 테이블 구성
- Redash 매출 대시보드 구축
- 일별/주별/월별 매출, 상품별 매출, 기간별 매출 추이 조회 기능
- 신규/기존 구매자 분류 로직 설계
- 데이터 수집 누락 및 이상 징후 확인을 위한 운영 체크 구조

## Tech Stack

AWS S3, AWS Glue, AWS Athena, AWS Lambda, EventBridge, Redash, SQL, Paddle API, PayPal API, Apple IAP Data

## Impact

- 수작업 중심의 매출 확인 과정을 자동화
- 전 기간 매출 추이와 상품별 성과를 빠르게 확인할 수 있는 환경 구축
- 마케팅/경영 의사결정을 데이터 기반으로 지원
- 이상 징후 탐지와 매출 현황 파악 리드타임 단축

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

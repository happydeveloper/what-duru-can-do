# Metrics

이 문서는 이력서와 포트폴리오에 사용되는 정량 지표의 근거를 정리하는 공간입니다.

## Payment

| Metric | Value | Source / Evidence | Notes |
|---|---:|---|---|
| Paddle transaction volume | 약 8,000~9,000건 | 내부 결제 로그 / Paddle dashboard | 공개 시 범위 표현 권장 |
| Payment error rate after recovery | 0% 수준 | 내부 운영 기록 / CS 기록 | “0%”는 근거 확인 후 표현 확정 |
| Recovery flow | 자동 복구 로직 운영 | Sentry / custom logs | Webhook 지연, SaaS 연동 실패 대응 |

## Email Infrastructure

| Metric | Before | After | Improvement |
|---|---:|---:|---:|
| Sendy processing time | 3~5분 | 약 10초 | 약 95% 이상 단축 |
| Manual monitoring time | 1시간 이상 | 5분 이내 | 운영 효율 개선 |

## Data Pipeline

| Metric | Before | After | Notes |
|---|---|---|---|
| Revenue reporting | 수작업 중심 | Redash 대시보드 자동 조회 | Paddle/PayPal/IAP 통합 |
| Sales visibility | 채널별 확인 | 일/주/월/상품별 조회 | 경영/마케팅 의사결정 지원 |

## Infrastructure

| Metric | Value | Notes |
|---|---:|---|
| Potential monthly cost saving | 약 170만 원 수준 | Cloudflare/레거시 인프라 정리 관련 |
| Potential annual saving | 약 2,040만 원 수준 | 실제 청구서 기준 검증 필요 |

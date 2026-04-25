# 레거시 WordPress/WooCommerce 플랫폼 운영 및 비용 최적화

## Summary

WordPress/WooCommerce 기반 레거시 플랫폼의 운영 비용, 보안 리스크, SEO 리디렉션, 인프라 이전 가능성을 분석하고 정리한 프로젝트입니다.

## Context

TTMIK는 WordPress/WooCommerce 기반 레거시 플랫폼과 Kajabi 기반 신규 학습 플랫폼을 함께 운영하고 있었습니다.

## Problem

- 레거시 플랫폼 유지 비용과 보안 리스크가 존재했습니다.
- Cloudflare, AWS, WordPress, WooCommerce, Kajabi, DNS, WAF가 복합적으로 얽혀 있었습니다.
- 서비스 종료 또는 이전 시 SEO 손실, 리디렉션 오류, 도메인 장애, 고객 접근 문제를 고려해야 했습니다.

## My Role

- 레거시 인프라 구조 분석
- 비용 절감 및 종료 계획 수립
- DNS, CDN, WAF, WordPress 의존성 검토
- ECS/Fargate 마이그레이션 가능성 검토
- 운영팀 및 경영진에게 리스크와 선택지 설명

## What I Built / Improved

- Cloudflare DNS 및 캐싱 구조 분석
- AWS Route 53 기반 DNS 이전 검토 및 작업 지원
- WordPress SEO-safe redirect 전략 수립
- EC2 기반 레거시 환경의 ECS 이전 가능성 검토
- WAF/ModSecurity 기반 보안 로그 분석 및 차단 전략 검토
- 레거시 서비스 종료 및 핸드오버 문서화

## Tech Stack

WordPress, WooCommerce, PHP, MySQL, AWS EC2, ECS/Fargate, Route 53, Cloudflare, WAF, ModSecurity, Apache, Docker

## Impact

- 월 단위 인프라 비용 절감 가능성 도출
- 레거시 플랫폼 종료 및 이전에 필요한 리스크를 구조적으로 정리
- SEO와 고객 접근성을 고려한 안전한 전환 계획 수립
- 남은 기간과 기술 리스크를 고려해 무리한 마이그레이션 대신 작업 중단/문서화/핸드오버 판단

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

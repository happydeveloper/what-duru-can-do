# TTMIK 앱 서비스 인프라 및 React Native 운영

## Summary

TTMIK Stories, Seyo, TTMIK Audio 등 앱 서비스의 iOS/Android 빌드, 앱 심사, 결제, React Native 운영 이슈를 지원한 프로젝트입니다.

## Context

여러 앱 서비스가 운영되고 있었고, iOS/Android 빌드, 인앱결제, 오디오, WebView, React Native 버전 이슈, 앱 심사 대응이 필요했습니다.

## Problem

- React Native 및 네이티브 모듈 버전 충돌이 빈번했습니다.
- iOS/Android 빌드 환경, 앱 심사, 인앱결제, 오디오 기능 안정화가 필요했습니다.
- 앱 서비스별로 운영 목적과 기술 구조가 달라 유지보수 난이도가 높았습니다.

## My Role

- 앱 빌드 및 배포 이슈 대응
- React Native/Native 모듈 연동 검토
- Apple Developer Program 및 앱 심사 대응
- 오디오 앱 및 학습 앱 운영 지원

## What I Built / Improved

- React Native 프로젝트 Android/iOS 빌드 이슈 해결
- Apple IAP 및 구독 결제 관련 운영 지원
- 오디오 앱 평가/심사 케이스 대응
- WebView 기반 앱 구조 및 네이티브 연동 검토
- Expo barcode scanning 등 신규 기능 POC 검토

## Tech Stack

React Native, iOS, Android, Kotlin, Java, Swift, Apple IAP, RevenueCat, WebView, Expo, Sentry/Firebase Crashlytics

## Impact

- 앱 빌드 및 배포 안정성 개선
- 앱 심사 및 운영 리스크 대응
- 구독/오디오/학습 앱 운영에 필요한 기술 기반 유지

## Evidence

- Related metrics: [evidence/metrics.md](../evidence/metrics.md)
- Architecture decisions: [evidence/architecture-decisions.md](../evidence/architecture-decisions.md)
- References: [evidence/references.md](../evidence/references.md)

## Next Improvements

- 더 정확한 정량 지표 보강
- 실제 아키텍처 다이어그램 추가
- 공개 가능한 스크린샷 또는 익명화된 운영 자료 추가

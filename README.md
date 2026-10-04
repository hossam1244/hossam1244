# 👋 Hi, I'm Hossam Rakha

Senior Software Engineer with **8 years** shipping production software:
- 📱 **15+ mobile apps** to Google Play & the App Store — Flutter (8 production client apps), native Android (Kotlin/Jetpack), native iOS (Swift/SwiftUI), React Native
- 🛠️ **Django/DRF backends** — fintech, marketplace, insurance, telecom and SaaS.
- 📦 **9 OSS libraries** distilled from that work, across Dart, Python and Kotlin — token refresh, idempotency, offline queues, error envelopes, the transactional outbox

I've spent years on both sides of the API contract — so the backends I build are the kind I always wanted as a client developer: clean contracts, honest errors, and performance that holds up on real devices and real networks.

## 🚀 Featured work

**NovaBank — a full-stack banking platform** (portfolio system: one backend, three clients, one contract):

| Repo | Stack | Highlights |
|---|---|---|
| [novabank-api](https://github.com/hossam1244/novabank-api) | Django · DRF · Celery · Channels | Idempotent payments on a double-entry ledger, RBAC, audit trail, WebSocket updates · 89 tests / 90% cov |
| [novabank-flutter](https://github.com/hossam1244/novabank-flutter) | Flutter · Bloc | Biometrics, secure storage, synchronized JWT refresh, offline-tolerant cache |
| [novabank-android](https://github.com/hossam1244/novabank-android) | Kotlin · Compose · Hilt | Lock-guarded refresh interceptor, Room cache, MVVM + Clean Architecture |
| [novabank-ios](https://github.com/hossam1244/novabank-ios) | Swift · SwiftUI + UIKit | async/await client, Keychain, Face ID, xcodegen-managed project |

**More products**: [marketpulse-api](https://github.com/hossam1244/marketpulse-api) — marketplace backend with a 500k-product catalog, cursor pagination, cache-aside and stock-reserving checkout (measured: 1 vs 49 queries) · [crewops-rn](https://github.com/hossam1244/crewops-rn) — offline-first React Native field app with a persisted mutation queue.

## 📦 Libraries (9)

**Dart / Flutter** — [sync_refresh](https://github.com/hossam1244/sync_refresh): one refresh for concurrent 401s (single-flight, replay-once) · [mutation_queue](https://github.com/hossam1244/mutation_queue): offline-first persisted FIFO writes with retries and dead-lettering · [idempotency](https://github.com/hossam1244/idempotency): client-side idempotency keys that survive retries and restarts · [poll_until](https://github.com/hossam1244/poll_until): async polling with backoff, deadline and cancellation

**Python / Django** — [django-idem](https://github.com/hossam1244/django-idem): Stripe-style request idempotency for DRF · [drf-envelope](https://github.com/hossam1244/drf-envelope): uniform `{error: {code, message, details}}` envelopes with stable codes · [django-event-outbox](https://github.com/hossam1244/django-event-outbox): transactional outbox with locked relay, retries and lease expiry · [drf-request-id](https://github.com/hossam1244/drf-request-id): request-ID middleware with ContextVar propagation and logging filter

**Kotlin / JVM** — [auth-refresh](https://github.com/hossam1244/auth-refresh): lock-guarded OkHttp token refresh with single replay and session teardown

Pairs worth noticing: `idempotency` (client) + `django-idem` (server) close the double-submit hole end to end; `sync_refresh`, `auth-refresh`, and the refresh logic inside the banking clients are the same contract in three languages.

## 💻 Tech Stack

**Backend** — Python · Django · DRF · GraphQL · Celery · Redis · Channels · PostgreSQL · Docker · GitHub Actions · Nginx/Gunicorn · AWS

**Mobile** — Flutter/Dart · Kotlin/Jetpack · Swift/SwiftUI/UIKit · React Native · Firebase · Room · Core Data

**Practices** — Clean Architecture · MVVM · TDD · SOLID · REST & GraphQL API design · CI/CD · code review

## 🌐 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hossam-rakha-325364122/) [![Dev.to](https://img.shields.io/badge/dev-to?label=dev.to&color=%23000)](https://dev.to/hossamrakha0) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/hossamrakha0)


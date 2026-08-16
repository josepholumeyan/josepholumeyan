# Joseph Olumeyan
**Full-Stack Software Engineer | Kotlin End-to-End (Android + Backend) | Spring Boot | Jetpack Compose**

I build full-stack systems where the client and the backend are both mine, in the same language — Kotlin on Android, Kotlin on the server. I care about owning a feature from database schema to UI state: concurrency, caching, and reliability across the client-server boundary, simply put, I bring ideas into reality.

Most recently, I solo-built **Mowa**, an AI career companion app moving into open testing on Google Play, with production billing and ad-monetization already live end-to-end. Before that, **Channel0**, a real-time streaming state machine, and a predictive sales forecasting system before that, all the tech words aside i'm constantly chasing that random thought of what if. 

---

## What I Work On
- Full-stack systems where I own both the Kotlin/Jetpack Compose client and the Kotlin/Spring Boot backend
- Backend services with real concurrency, caching, and data-consistency concerns — not just CRUD
- Android apps built on modern architecture (MVVM, unidirectional state, offline-first)
- System design focused on reliability under real constraints (small hardware footprints, live users, real payments)

---

## Technical Stack

**Mobile / Android**
- Kotlin, Jetpack Compose
- Coroutines & Flow (structured concurrency, cache invalidation)
- Hilt (DI), Retrofit, Room
- MVVM, unidirectional state management

**Backend / Systems**
- Kotlin, Spring Boot, JPA/Hibernate
- PostgreSQL (schema design, query tuning), HikariCP
- Python, FastAPI
- JWT-based security, rate limiting (Bucket4j)
- Docker, Render/Railway deployment

**Tools**
- Git & GitHub
- Android Studio, IntelliJ IDEA

---

## Featured Work

**[Mowa](https://github.com/josepholumeyan) — AI Career Companion** *(private repo — happy to walk through the codebase or give a demo)*
Kotlin end-to-end: Jetpack Compose client + Spring Boot/PostgreSQL backend. Seven-layer memory architecture that lets a stateless AI feel continuous over months, a provider-agnostic AI layer with automatic failover, and Google Play Billing end-to-end with a rewarded-ads path for free users. Backend context-assembly latency cut from ~1400ms to ~300ms via bounded local parallelism. Runs on 512MB RAM / 0.1 vCPU.

**[Channel0](https://github.com/josepholumeyan/Channel0Backend) — Continuous Playback Platform**
Full-stack streaming system: Android client (Jetpack Compose, MVVM) + Spring Boot/JPA backend orchestrating a linear TV experience via deterministic scheduling. ~80% reduction in playback state sync errors, ~30% API latency reduction from query and Hibernate tuning, 100% state reliability across restarts in testing.

**[Sales Prediction / Forecasting](https://github.com/josepholumeyan/Consumer-Behaviour-ML-API) — ML Pipeline + Android App**
FastAPI backend serving real-time and batch predictions from an XGBoost/Random Forest model trained on ~51k rows (R = 0.71, MAE = 50.38, RMSE = 135), plus a native Kotlin app consuming it. ~23s to batch-process 500 rows on constrained (8GB RAM) hardware.

---

## Current Focus
- Taking Mowa through open testing toward public launch (billing and ad-monetization already live, reliability at small scale)
- Deepening backend systems design — concurrency, caching, fault tolerance
- Shipping full products end-to-end rather than isolated demos

---

## 📫 Connect
[LinkedIn](https://www.linkedin.com/in/joseph-olumeyan-225a5b292) · [josepholumeyan@gmail.com](mailto:josepholumeyan@gmail.com)

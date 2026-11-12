# Antônio Paes

**Software Engineer · AI Systems · Backend · Native Applications**

[Portfolio](https://antoniopaesss.vercel.app/en) · [LinkedIn](https://www.linkedin.com/in/antoniopaess/) · [Email](mailto:paesdeandradeantonio@gmail.com) · Recife, Brazil

I build native applications and software systems that connect language models, platform APIs and backend services, with an emphasis on testable architecture and clearly documented limits. I study Computer Science at [CESAR School](https://www.cesar.school/) and work as a Native Mobile Developer Intern at CESAR.

> 🏆 **Distinguished Winner, Apple Swift Student Challenge 2026** for [Juru AAC](https://apps.apple.com/br/app/juru-aac/id6776475179), one of 50 top-ranked student developers worldwide, invited to WWDC26 · [CESAR School announcement](https://www.cesar.school/blog/aluno-distinguished-winner-swift-challenge-2026/)

## Selected projects

### [Juru AAC](https://apps.apple.com/br/app/juru-aac/id6776475179) · Published on the App Store · Individual

Offline communication app for iPad, built for people living with ALS or recovering from stroke. Users compose text with two facial gestures through a binary letter tree, or with iPadOS Eye Tracking; context-aware word prediction runs on device with Core ML. No accounts, no network, no data collection.

`Swift` `SwiftUI` `ARKit` `Core ML` `AVSpeechSynthesizer` `VoiceOver / Dynamic Type`
· [App Store](https://apps.apple.com/br/app/juru-aac/id6776475179) · [Case study](https://antoniopaesss.vercel.app/en/juru)

### [HeyChomp](https://github.com/AntonioPaess/HeyChomp) · macOS · In development · Personal

Native macOS assistant that routes requests from a coordinator to specialist agents and runs them on local Apple Foundation Models. Implemented today: `LanguageModelSession` with custom tool calling (`@Generable` arguments, per-reply tool budgets, untrusted-content handling), a bridge to the Claude Agent SDK and Codex app-server over a local RPC process, Vision OCR and screen capture, Speech, EventKit and Open-Meteo integrations. Voice, screen-reading and diagram flows still have open acceptance items, tracked publicly in [KNOWN_ISSUES.md](https://github.com/AntonioPaess/HeyChomp/blob/main/KNOWN_ISSUES.md).

`Swift 6` `SwiftUI / AppKit` `Apple Foundation Models` `Claude Agent SDK` `Swift Testing`
· [Code](https://github.com/AntonioPaess/HeyChomp) · [Architecture](https://github.com/AntonioPaess/HeyChomp/blob/main/Sieghart/ARCHITECTURE.md) · [Test suite](https://github.com/AntonioPaess/HeyChomp/blob/main/Sieghart/Tests/README.md) · [Case study](https://antoniopaesss.vercel.app/en/heychomp)

### [Ceres AI](https://github.com/AntonioPaess/ceres-ai-coffee-quality) · Web + Telegram · Hackathon prototype · Team of three

Experimental first read on green coffee quality from a photo. A Roboflow object-detection model finds defective beans, deterministic and unit-tested rules turn the detections into a score, grade and suggested price, and an AI assistant explains the result on the web and in Telegram. The model only explains: it never computes the grade. Context is built server-side from the user's own data, and Telegram actions run only after explicit confirmation. Model accuracy has not been measured.

`TypeScript` `React` `PocketBase` `Roboflow` `AI agents` `Telegram Bot API` `Vitest`
· [Code](https://github.com/AntonioPaess/ceres-ai-coffee-quality) · [Architecture](https://github.com/AntonioPaess/ceres-ai-coffee-quality/blob/main/docs/ARCHITECTURE.md) · [AI integrations](https://github.com/AntonioPaess/ceres-ai-coffee-quality/blob/main/docs/AI_INTEGRATIONS.md) · [Case study](https://antoniopaesss.vercel.app/en/ceres-ai)

### [Murphy](https://github.com/AntonioPaess/Murphy) · Android + iOS · In development · Personal

Kotlin Multiplatform core for offline peer-to-peer messaging over a BLE mesh. Shared code holds the connection state machine, a packet router with TTL and duplicate suppression, a binary radio protocol, bounded retries and receiver receipts; native BluetoothGatt and CoreBluetooth adapters plug into it. A deterministic topology simulator tests relay failure and rerouting. Physical Android ↔ iPhone interoperability is not yet validated.

`Kotlin Multiplatform` `Jetpack Compose` `SwiftUI` `BLE / GATT` `kotlin.test`
· [Code](https://github.com/AntonioPaess/Murphy) · [Architecture](https://github.com/AntonioPaess/Murphy/blob/main/docs/architecture.md) · [Radio protocol](https://github.com/AntonioPaess/Murphy/blob/main/docs/radio-protocol.md)

### [SportSnap](https://github.com/AntonioPaess/sportsnap-api) · Backend · Team of four

Academic platform linking sports sessions, photographers and a photo marketplace, split into Spring Boot services with DDD / Clean Architecture and Cucumber BDD acceptance tests. I scaffolded the multi-module Maven project and owned the marketplace stories: photo batch management, photographer dashboard, image upload with watermarking (Decorator), and the REST integration with the Next.js frontend.

`Java 21` `Spring Boot 3` `Spring Data JPA` `Flyway` `Cucumber / JUnit 5`
· [Code](https://github.com/AntonioPaess/sportsnap-api)

More projects, with my role in each, are on the [portfolio](https://antoniopaesss.vercel.app/en#projects).

## Engineering focus

- **AI integration:** on-device models (Apple Foundation Models, Core ML), tool calling and agent workflows, bounded context, cancellation, and testing AI-backed features with injected dependencies.
- **Backend:** REST APIs and services in Java / Spring Boot, domain modeling, persistence with JPA, Flyway and SQL (H2, PostgreSQL), BDD and unit tests.
- **Native applications:** Swift, SwiftUI and AppKit on iOS, iPadOS and macOS; Kotlin and Jetpack Compose on Android; Kotlin Multiplatform for shared logic.
- **Engineering practice:** state machines, deterministic tests, explicit failure handling, accessibility, and documentation that separates what is implemented from what is planned.

Also used: TypeScript / Next.js, Python, C, Git, Docker.

## Experience

**CESAR** · Native Mobile Developer Intern · Aug 2025 – present\
iOS and Android rotations in native mobile R&D: SwiftData modeling and queries, memory investigation with Instruments, Swift Testing scenarios, Swift 6 concurrency, and pair work on a Kotlin library built on Android's Accessibility Service with GitLab CI/CD. Product details are under NDA.

**Cloudin** · Full Stack Developer Intern · Feb 2025 – Aug 2025\
Frontend development with React, TypeScript and Next.js, plus PHP and Firebase, for hospitality software and client onboarding automation.

**CESAR School** · Teaching Assistant, C Programming · Feb 2025 – Feb 2026

## Education

**CESAR School** · B.Sc. Computer Science · 2024 – 2027 (expected) · GPA 8.81/10\
Ranked first in CESAR School's double-degree selection with Instituto Politécnico de Bragança (Informatics Engineering, planned start 2027).

## Contact

Open to conversations about software engineering, backend, AI integration and native applications.

[Portfolio](https://antoniopaesss.vercel.app/en) · [LinkedIn](https://www.linkedin.com/in/antoniopaess/) · [Email](mailto:paesdeandradeantonio@gmail.com)

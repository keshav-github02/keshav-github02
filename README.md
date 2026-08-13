<h1 align="center">Keshav Agarwal</h1>

<p align="center">
  <b>Software Engineer · Systems & Backend · Competitive Programmer</b><br>
  C++ and backend engineer building telemetry SDKs, multithreaded services, and production APIs.<br>
  Codeforces Expert (1608) · LeetCode Guardian (2127) · CodeChef 4★ (1886)
</p>

<p align="center">
  <a href="https://github.com/keshav-github02"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/keshav-agarwal-b5874b257/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/keshavagarwal02/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://codeforces.com/profile/ka45"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" alt="Codeforces"></a>
  <a href="https://www.codechef.com/users/ka45"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=flat-square&logo=codechef&logoColor=white" alt="CodeChef"></a>
  <a href="mailto:keshaviiitr@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

- SDK Intern at **MediaMelon Inc.**, working on C++ and Kotlin instrumentation for media-analytics SDKs used across **1M+ sessions daily**.
- Comfortable low in the stack — multithreading, bounded queues, in-memory time-series aggregation — and across the stack, from REST APIs to Flutter apps.
- B.Tech CSE at **IIIT Ranchi** (2022–2026), CGPA 8.51.
- Long-running competitive programming habit: Expert on Codeforces, Guardian on LeetCode, 4★ on CodeChef.

---

### Experience

**Software Development Kit (SDK) Intern — MediaMelon Inc.** · Apr 2026 – Present
- Built offline payload persistence in **C++** for the SES-Inverto SDK: configurable storage up to 100 MB, size-bounded buffering, and automatic sync on network reconnection.
- Hardened error detection and playback monitoring across **5+ player platforms** (THEO, Shaka, Roku, Web, native SDKs) for consistent cross-platform observability.
- Standardized **DRM** reporting into a unified JSON schema with DRM-level/type classification, plus buffering-event payload reporting.
- Added telemetry to a custom **Android SDK in Kotlin**, enabling reliable analytics event collection at production scale.

**Software Development Intern — Infrawave Solutions** · Mar 2025 – May 2025
- Shipped a production **Flutter** app to the [Google Play Store](https://play.google.com/store/apps/details?id=com.ybrut.android.steplnsa&hl=en_IN) (500+ downloads) with context-based theme switching.
- Cut load times using **Redis** caching and tighter **BLoC** state management.
- Built **20+ REST APIs** with **Node.js / Express.js** for survey and student-management modules.
- Containerized backend services with multi-stage **Docker** builds for reproducible deploys across environments.

---

### Tech Stack

| | |
|---|---|
| **Languages** | C++, C, Kotlin, Python, JavaScript, Dart |
| **Backend & Frameworks** | Node.js, Express.js, FastAPI, WebSockets, LangChain, REST APIs |
| **Frontend & Mobile** | Flutter, React, TypeScript |
| **Databases** | MySQL, MongoDB, Redis, ChromaDB |
| **Tools & DevOps** | Docker, Git, GitHub Actions, AWS, CMake, Postman, Android Studio |
| **Fundamentals** | Data Structures & Algorithms, Multithreading, Operating Systems, System Design, Computer Architecture |

---

### Competitive Programming

| Platform | Rating | Rank |
|---|---|---|
| [Codeforces](https://codeforces.com/profile/ka45) | 1608 | **Expert** |
| [LeetCode](https://leetcode.com/u/keshavagarwal02/) | 2127 | **Guardian** |
| [CodeChef](https://www.codechef.com/users/ka45) | 1886 | **4★** |

**Contest highlights**
- Global **rank 39** — CodeChef Starters 175, Division 2
- Global **rank 166 / 35K+** — LeetCode Biweekly Contest 183
- Global **rank 816 / 30K+** — Codeforces Round 1028, Division 2

---

### Featured Projects

**[PulseDB — Telemetry Analytics Platform](https://github.com/keshav-github02/PulseDB)**
A multithreaded **C++20** telemetry engine that ingests media-playback events over HTTP through a producer–consumer pipeline (thread-safe bounded queue, per-core worker pool, exponential-backoff retries) and aggregates them in memory as time series with O(1) minute-bucket lookups and lock-free atomic counters. Metrics are served over a REST API to a React + Recharts dashboard, with disk persistence and spool-and-replay recovery when downstream is offline. Benchmarked at **1M+ events/sec**, covered by **122 unit/integration tests** with Docker and GitHub Actions CI.
`Tech Stack: C++20, Multithreading, CMake, REST, React, TypeScript, Docker, GitHub Actions`

**[EchoMind](https://github.com/keshav-github02/perplexity)**
An AI answer engine that pairs web retrieval with LLM filtering: the **Tavily API** plus cosine similarity narrows results to the top 5 relevant sources, and **Google Gemini** re-ranks and synthesizes them into context-aware responses. A **FastAPI** backend streams updates to the Flutter client over WebSockets for low-latency interaction.
`Tech Stack: Flutter, Dart, FastAPI, WebSockets, Tavily API, Google Gemini, LangChain`

---

### Engineering Focus

| Area | What I've built |
|---|---|
| Systems & concurrency | Multithreaded C++ pipelines, bounded queues, worker pools, lock-free counters |
| SDK & instrumentation | Offline payload persistence, telemetry collection, DRM/analytics schemas, cross-platform player monitoring |
| Backend & APIs | REST services in Express.js and FastAPI, Redis caching, WebSocket real-time channels |
| Reliability & delivery | Retry/backoff, spool-and-replay recovery, multi-stage Docker builds, CI with automated test suites |

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=keshav-github02&show_icons=true&hide_border=true&theme=github_dark" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=keshav-github02&layout=compact&hide_border=true&theme=github_dark" alt="Top languages" height="165">
</p>

---

### Connect

📧 [keshaviiitr@gmail.com](mailto:keshaviiitr@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/keshav-agarwal-b5874b257/) · 🧩 [LeetCode](https://leetcode.com/u/keshavagarwal02/) · ⚔️ [Codeforces](https://codeforces.com/profile/ka45) · 🍳 [CodeChef](https://www.codechef.com/users/ka45)

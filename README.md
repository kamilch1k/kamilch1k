# kamilch1k

Backend-focused developer building practical systems in .NET, Go, and TypeScript.

I like projects that have a real backend shape: authentication, idempotency, concurrency, outbox-style workflows, metrics, tests, and local verification scripts. Right now I am building a portfolio around APIs and services that can be cloned, run, tested, and discussed in interviews.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

## Featured backend projects

| Project | Stack | What it shows |
| --- | --- | --- |
| [settlement-recon](https://github.com/kamilch1k/settlement-recon) | Go, HTTP, CSV | Deterministic payment settlement reconciliation, mismatch classification, strict CSV parsing, CLI/API workflows, sample data, tests, Docker, CI |
| [cacheguard](https://github.com/kamilch1k/cacheguard) | ASP.NET Core, .NET | Resilient API gateway demo with rate limiting, request coalescing, circuit breaker, stale cache fallback, tests, Docker, CI |
| [migrationsafe](https://github.com/kamilch1k/migrationsafe) | Go, PostgreSQL, SQL | Migration safety checker for destructive DDL, unsafe indexes, locking risks, text/JSON reports, sample migrations, tests, Docker, CI |
| [ledgerline](https://github.com/kamilch1k/ledgerline) | Go, PostgreSQL | Idempotent double-entry ledger, concurrency-safe transfers, no-overdraft guarantees, real Postgres tests |
| [signalforge](https://github.com/kamilch1k/signalforge) | ASP.NET Core, SQLite, GitHub API | Maps backend vacancies to open-source proof opportunities, explains scoring, tracks proof actions with idempotency keys, ships with UI, CI, Docker, tests |
| [oss-scout](https://github.com/kamilch1k/oss-scout) | ASP.NET Core, Go | Scores open-source issues by fit, recency, labels, backend signals, and contribution risk with tests and a Go worker |
| [vacancy-signal-radar](https://github.com/kamilch1k/vacancy-signal-radar) | ASP.NET Core, Go, SQLite | Scores backend job postings and persists apply/watch/skip decisions with idempotency-key protection |
| [job-application-tracker-api](https://github.com/kamilch1k/job-application-tracker-api) | ASP.NET Core, EF Core | Auth, user-owned resources, migrations, dashboard queries, reminders, integration tests |
| [mixed-order-ledger-system](https://github.com/kamilch1k/mixed-order-ledger-system) | .NET, Go | Order API, durable outbox events, Go worker processing, ledger entries, end-to-end local verification |
| [go-url-shortener-api](https://github.com/kamilch1k/go-url-shortener-api) | Go | Short links, redirects, click analytics, rate limiting, metrics, HTTP tests |
| [hire-bridge](https://github.com/kamilch1k/hire-bridge) | TypeScript | Webhooks, retries, drift reconciliation, append-only audit trail |
| [droolcat-agent](https://github.com/kamilch1k/droolcat-agent) | JavaScript | Visual cockpit for CLI agents with live actions, windows, and navigable graphs |

## Systems and game tech

| Project | Stack | What it shows |
| --- | --- | --- |
| [lattice-survivors](https://github.com/kamilch1k/lattice-survivors) | Three.js, WebGL, JavaScript | Procedural shader arena, full-screen 3D rendering, wave gameplay, desktop/mobile controls, GitHub Pages deployment |
| [voxv2-mobile-voxel-renderer](https://github.com/kamilch1k/voxv2-mobile-voxel-renderer) | Unity, C#, Burst, ShaderLab | Chunked voxel storage, greedy meshing, procedural generation, mobile controls, shaders, and source-only packaging |

## What I am sharpening

- Backend APIs with clean contracts and useful tests
- Idempotency, concurrency, and failure recovery
- Event-driven flows that are understandable without heavy infrastructure
- Local developer experience: seed data, smoke tests, docs, and CI

## Current focus

Building portfolio projects that are small enough to understand quickly but real enough to discuss deeply: why the data model works, how failures are handled, what the tests prove, and where the system would go next in production.

[🇧🇷 Português](README.md) | 🇺🇸 English

# ledgerflow

A transaction processing service built with pure Node.js, created to master the fundamentals of the platform.


## About

ledgerflow receives financial transactions (deposits, withdrawals and transfers), validates them, applies business rules and records everything in an append-only ledger.

The project is built in phases. Each phase focuses on a core Node.js concept, using built-in modules wherever possible.

## Getting started

### Prerequisites

- Node.js (LTS version)

### Installation

```bash
git clone https://github.com/ludimilladev/ledgerflow.git
cd ledgerflow
npm install
```


For development with automatic restart:

```bash
npm run dev
```

## Roadmap

- [x] Project setup
- [ ] Phase 1: CLI that processes large transaction files with streams
- [ ] Phase 2: HTTP server using only the built-in `http` module
- [ ] Phase 3: Event-driven transaction pipeline with `EventEmitter`
- [ ] Phase 4: Background processing with `worker_threads`
- [ ] Phase 5: Persistence, logging and graceful shutdown
- [ ] Phase 6: Automated tests with the built-in test runner
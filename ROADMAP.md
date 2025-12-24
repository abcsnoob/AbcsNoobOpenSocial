# Roadmap

**Abc's Noob Open Social**

This roadmap describes **direction, not deadlines**.
Progress is defined by **working code**, not schedules.

There are no promises.
There is no pressure.
There is only iteration.

---

## Guiding Principles

* Durability over speed
* Simplicity over features
* Offline-first over real-time
* Forkability over consensus
* Survival over popularity

---

## Platform Targets

The project targets **four primary platforms**:

* 🖥️ Windows
* 🐧 Linux
* 📱 Android
* 📱 iOS

Each platform is treated as a **first-class node**, not a client.

---

## Phase 0 — Foundations (Current)

**Goal:** establish a minimal, correct, and durable core.

* [ ] Define cryptographic identity format
* [ ] Passphrase + secret key derivation
* [ ] Append-only local data store
* [ ] Content addressing (hash-based)
* [ ] Node-to-node message format
* [ ] Basic data validation rules
* [ ] GPLv3 compliance audit

Output:

* runnable core
* no UI dependency
* no network dependency

---

## Phase 1 — Core Networking

**Goal:** data moves without assumptions.

* [ ] Peer discovery (local-first)
* [ ] Opportunistic sync model
* [ ] Store-and-forward messaging
* [ ] Conflict-tolerant merge logic
* [ ] No global clock requirement
* [ ] Eventual consistency guarantees

Notes:

* latency is acceptable
* duplication is acceptable
* loss is minimized, not eliminated

---

## Phase 2 — Desktop Nodes

### 🖥️ Windows

* [ ] Native Go binary
* [ ] Local node service
* [ ] Basic CLI interface
* [ ] Encrypted local storage
* [ ] Manual peer connect

### 🐧 Linux

* [ ] Native Go binary
* [ ] Headless-friendly operation
* [ ] CLI-first workflow
* [ ] Systemd compatibility (optional)
* [ ] Same behavior as Windows node

Desktop nodes act as:

* long-lived peers
* storage carriers
* relay points

---

## Phase 3 — Mobile Nodes

### 📱 Android

* [ ] Local-first node runtime
* [ ] Background sync (best-effort)
* [ ] Bluetooth-based propagation
* [ ] Power-aware operation
* [ ] Minimal UI (read / write / sync)

### 📱 iOS

* [ ] iOS-compatible node core
* [ ] Background execution constraints respected
* [ ] Opportunistic sync only
* [ ] Encrypted secure storage
* [ ] Feature parity with Android (when possible)

Mobile nodes prioritize:

* portability
* proximity-based transfer
* intermittent connectivity

---

## Phase 4 — Identity & Social Layer

**Goal:** social interaction without central control.

* [ ] Human-readable aliases (optional)
* [ ] Follow / unfollow semantics
* [ ] Immutable posts
* [ ] Reply chains
* [ ] Local filtering (not moderation)
* [ ] No global feed

All views are **local interpretations**.

---

## Phase 5 — Resilience & Extremes

**Goal:** survive unlikely but catastrophic scenarios.

* [ ] Delay-tolerant networking improvements
* [ ] Large-gap sync (months / years)
* [ ] Cold storage import/export
* [ ] Physical transfer support
* [ ] Corruption detection & recovery

---

## Phase 6 — Interoperability

**Goal:** coexist, not dominate.

* [ ] Protocol documentation
* [ ] Reference implementation stability
* [ ] Independent implementations welcome
* [ ] Backward compatibility strategy

No forced upgrades.
Old nodes are not “invalid”.

---

## What This Roadmap Is Not

This roadmap does **not** promise:

* mass adoption
* commercial success
* user growth
* compliance with platform policies
* approval from institutions

---

## How This Roadmap Changes

The roadmap can change when:

* someone implements something better
* a fork proves a superior direction
* reality disproves assumptions

Forks are not failures.
Forks are evolution.

---

## Final Note

> “This project does not race the present.
> It prepares for a future where time itself is unreliable.”


Chỉ cần nói: **“next: …”**

# Feline Ops: Autonomous Incident Response Bundle

[![OKF Memory: v0.2 bundle](https://registry.okf-memory.dev/badge/v0.2.svg)](https://registry.okf-memory.dev/?q=sknr/okf-bundle-example)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Canonical persistent project memory, architectural decisions, and emergency runbooks for managing feline-induced smart-home chaos. Built with the **Open Knowledge Format (OKF) v0.2** specification.

---

## 🚀 Quick Install

Vendor this knowledge bundle directly into any project using the `okf` CLI:

```bash
okf pull github.com/sknr/okf-bundle-example
```

This installs the bundle into your workspace under `.okf/vendor/sknr/okf-bundle-example/` and records the reproducible SHA-256 integrity hash in `okf.lock`.

---

## 🧠 Bundle Contents

All persistent memory concepts live inside [`knowledge/`](knowledge/):

### Architectural Decisions
* [`ADR-001: Tabletop Gravity Testing Protocol`](knowledge/decisions/adr-001-tabletop-gravity-testing-protocol.md) (`constraint`) - Standardizes unannounced edge-push testing of fragile household assets.
* [`ADR-002: Door State Quantum Superposition`](knowledge/decisions/adr-002-door-state-quantum-superposition.md) (`context`) - Mandates interior doors remain in quantum superposition neither fully open nor closed.
* [`ADR-003: Robotic Vacuum Armistice and Curfew`](knowledge/decisions/adr-003-robotic-vacuum-armistice-curfew.md) (`hold`) - Establishes a strict ceasefire and daytime operational window for autonomous floor cleaners.

### Operational Runbooks
* [`Runbook: 03:00 AM Corridor Zoomies Mitigation`](knowledge/runbooks/0300-zoomies-mitigation.md) (`constraint`) - Standard operating procedure for containing nocturnal high-velocity corridor pacing.
* [`Runbook: Mechanical Keyboard Eviction Triage`](knowledge/runbooks/keyboard-eviction-triage.md) (`context`) - Safe and peaceful procedure for reclaiming input devices occupied by a loafing cat.

### Reusable Patterns
* [`Pattern: Cardboard Box Volumetric Invariance`](knowledge/patterns/cardboard-box-volumetric-invariance.md) (`constraint`) - "If it fits, I sits" non-Newtonian fluid volume adaptation.
* [`Pattern: Red Dot Telemetry Disinformation`](knowledge/patterns/red-dot-telemetry-disinformation.md) (`context`) - Dynamic 650nm photon guidance to redirect kinetic energy.

---

## 🔍 Validation & Conformance

Verify bundle conformance and graph connectivity locally with strict gating:

```bash
okf validate knowledge/ --strict --drift
```

Expected output:
```text
OKF v0.2 check of "knowledge" (v0.2): 7 concept(s), 0 error(s), 0 gate finding(s), 0 warning(s); 0 broken link(s), 0 orphan(s), 0 stale [--strict]. Conformant.
```

---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

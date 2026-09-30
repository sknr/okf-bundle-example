---
type: Decision
title: "ADR-001: Tabletop Gravity Testing Protocol"
description: "Standardizes unannounced edge-push testing of fragile household assets to calibrate acoustic feedback."
governance: constraint
generated: { by: "agent/okf", at: "2026-09-30T16:00:00Z" }
tags: ["gravity", "physics", "incident-prevention"]
code_refs: ["configs/motion-sensors.yaml"]
---

# ADR-001: Tabletop Gravity Testing Protocol

## Context & Problem
Planetary gravitational constants cannot be assumed invariant over time without continuous empirical validation. Household feline agents routinely conduct unannounced edge-displacement experiments with beverage glassware and electronics.

## Decision
All edge surfaces greater than 0.75m above floor level are officially designated as active gravity test fields.

1. **Velocity Modulation:** Objects must be slowly nudged toward the edge with paw increments of 5mm while maintaining unblinking eye contact with human operators.
2. **Acoustic Calibration:** Upon terminal floor impact, acoustic signatures are logged to determine floor material resonance.
3. **Emergency Containment:** In case of rapid kinetic escalation, refer to [Runbook: 03:00 AM Corridor Zoomies Mitigation](../runbooks/0300-zoomies-mitigation.md).

## Related Concepts
- [Runbook: 03:00 AM Corridor Zoomies Mitigation](../runbooks/0300-zoomies-mitigation.md)
- [ADR-003: Robotic Vacuum Armistice and Curfew](adr-003-robotic-vacuum-armistice-curfew.md)

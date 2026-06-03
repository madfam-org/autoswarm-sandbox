# selva-sandbox — Ecosystem Context

> [!IMPORTANT]
> MADFAM-ENCLII-FIRST-LEGACY-RAW v1: This document contains legacy raw infrastructure command examples.
> Routine production operations must use Enclii web, API, or CLI. Treat raw
> `kubectl`, `helm`, SSH, provider CLI/API, `docker exec`, and direct container
> access as platform bootstrap or documented break-glass only, and record any
> missing Enclii adapter gap.

> **Disposable sandbox for Selva autonomous agent workflow experiments.**

## What this repo is

Selva Sandbox is a throwaway repository for testing autonomous agent
workflows, branch protection patterns, and CI guardrails before promoting
patterns to production MADFAM services.

**Pillar**: Platform / R&D
**Type**: sandbox
**Status**: experimental

### Scope

- No production deployment or customer-facing domains
- Not registered in Enclii production status
- Safe target for agent-driven PRs, merge queues, and workflow prototyping

### Related repos

- `selva-office` — production Selva product surface
- `enclii` — platform control plane when experiments graduate to Enclii-first ops
- `solarpunk-foundry` — shared `@madfam/*` packages and port registry

### Entrypoints

- `README.md` — sandbox purpose and TODOs
- `AGENTS.md` — canonical agent instructions

### Production operations

Not applicable — no production workloads. If an experiment needs cluster access,
use a dedicated staging namespace via Enclii; do not normalize raw `kubectl` in
this repo's docs.

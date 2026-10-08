# host-lang - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
> Master plan: ../_lexersketch/ROADMAP.md and ../_lexersketch/NEW-LIBS.md
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Registry, typed signatures, permission model and gate, marshalling over value-lang values.
- [ ] Property tests: deny-by-default, signature checks.

## v0.5.0 - Implementation
- [ ] Standard host library (io, fs, env, time, process) behind permissions; native-call descriptors for compiled code.

## v0.9.0 - Hardening
- [ ] Audit of permission bypass paths; fuzzing marshalling.

## v1.0.0 - Stable
- [ ] Frozen after the VM and evaluator both call through it (D18).

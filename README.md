# Exchange8

> Secure Post-Quantum-Safe Securities Exchange Platform That Heals and Scales Itself.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Built with Rust](https://img.shields.io/badge/Built%20with-Rust-orange.svg)](https://www.rust-lang.org/)
[![Docs](https://img.shields.io/badge/docs-read-3aa757.svg)](https://exchange8.dev)
[![Website](https://img.shields.io/badge/website-exchange8.dev-1a73e8.svg)](https://exchange8.dev)

Sentin8 capital-markets vertical - exchange / MTF / ATS platform built
as Rust services + Flutter apps on the Sentin8 platform.

## Layout

- `design/` - technical design docs (see `design/README.md`)
- `crates/` - shared codecs + domain types
- `services/` - the 13 services
- `BACKLOG.md` - implementation backlog (epics D1/E1/E2/.../CO1)
- `PARITY.md` - verification matrix (design → backlog → test)

## Build

```bash
make build-rust   # cargo build --workspace --release
make test         # cargo test --workspace
```

## Status

Design phase complete (2026-08-29). Implementation in progress - see
`BACKLOG.md` for per-epic status and `PARITY.md` for the verification matrix.

---

**Architecture & Design:** exchange8 and its underlying concepts were designed by [Hamid Jahanzad](https://www.linkedin.com/in/hamidjahanzad/).

## Website

The public website at **exchange8.dev** lives in the sibling
`exchange8-site` repo - Docusaurus v3 on `@sentin8/site-engine`, with
product/app/SDK pages and a Reference section harvested at build time
from these repositories (program design:
`../design/sentin8-websites-design.md`).

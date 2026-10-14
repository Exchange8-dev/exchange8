# Exchange8

Sentin8 capital-markets vertical — exchange / MTF / ATS platform built
as Rust services + Flutter apps on the Sentin8 platform.

## Layout

- `design/` — technical design docs (see `design/README.md`)
- `crates/` — shared codecs + domain types
- `services/` — the 13 services
- `BACKLOG.md` — implementation backlog (epics D1/E1/E2/.../CO1)
- `PARITY.md` — verification matrix (design → backlog → test)

## Build

```bash
make build-rust   # cargo build --workspace --release
make test         # cargo test --workspace
```

## Status

Design phase complete (2026-08-29). Implementation in progress — see
`BACKLOG.md` for per-epic status and `PARITY.md` for the verification matrix.

---

**Design attribution:** exchange8 and its underlying concepts were designed by Hamid Jahanzad <Hamid@Jahanzad.com>.

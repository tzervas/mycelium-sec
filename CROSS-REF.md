# CROSS-REF — mycelium-sec

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-cli-common | https://github.com/tzervas/mycelium-cli-common | `c673fafdd1bcecb713e3560689af6ab152033867` | tree `c6fc7df3db94db6de08a7004729b1c37a7f5fc76` | Rust API of `mycelium-cli-common` (see monorepo `docs/api-index/INDEX.md#mycelium-cli-common`) |

**Owning docs:** see monorepo `docs/Doc-Index.md`.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.

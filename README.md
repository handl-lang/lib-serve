# lib-serve

HTTP server around a fetch-shaped handler arrow — WinterCG/srvx-style surface.

Part of the `handl-lang` org split (ADR-0128). History is a `git subtree
split` of the platform monorepo's `serve/` (via `web`).

## Layout

```text
src/        the .hnl sources
pkg.hnl     dependencies, when any: `{ deps: { <name>: "branch:<ref>" } }`
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

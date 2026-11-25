# lib-serve

HTTP server around a fetch-shaped handler arrow — WinterCG/srvx-style surface.

## Layout

```text
src/index.hnl   the .hnl sources
pkg.hnl         package manifest — modules, deps, description, license
workflows/gate.yaml           bupha entry (handl-gates) → scripts/hnl-gate.sh
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.

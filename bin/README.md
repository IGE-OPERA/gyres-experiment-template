# bin/

CLI helpers for the ledger:

- **`run-experiment`** — `init | run | record | reproduce <run-dir>`.
  Bridges `run.yaml` declarations to the `gyres` CLI of the ocean-gyres
  checkout (`gyres_dir`, default sibling `../ocean-gyres`).
- **`detect-machine`** — matches `hostname -s` against `machines/*.yaml`;
  `--write` creates a starter machine config.

Environment overrides: `GYRES_DIR` (checkout path), `GYRES_PYTHON`
(interpreter), `GYRES_BIN` (full command prefix, e.g.
`uv run --project ~/git/ocean-gyres python -m gyres.cli`).

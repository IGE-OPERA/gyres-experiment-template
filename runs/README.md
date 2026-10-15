# runs/

One directory per experiment, named `<nickname>_<YYYY-MM-DD>_<description>`.
Each directory is self-contained: `run.yaml` (intent) → `config.yaml`
(resolved) → `run_manifest.json` (provenance), plus notes and analysis.
Output data (`*.nc`, `*.npz`) is git-ignored.

Create a new experiment by writing `run.yaml` (see the template in
`../AGENTS.md` §6), then `bin/run-experiment init runs/<name>`.

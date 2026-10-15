# machines/

Personal machine configurations. Schema reference:
[`_template.yaml`](_template.yaml).

- `nickname` — used to build run-directory names (`<nickname>_<date>_<desc>`)
- `hostnames` — `hostname -s` outputs for `bin/detect-machine` auto-detection
- `scheduler` — `null` (direct) | `slurm` | `oar`; drives the `run.sh` header
  generation in `bin/run-experiment init`
- `gyres_dir` — absolute path of the ocean-gyres checkout on this machine
- `env_setup` — shell commands embedded at the top of every generated `run.sh`

Add a machine with `bin/detect-machine --write`, then edit.

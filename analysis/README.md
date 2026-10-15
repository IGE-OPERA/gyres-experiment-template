# analysis/

Reusable analysis code:

- importable diagnostic functions (take `xarray.Dataset`, no side effects)
- `intercomparisons/` — cross-experiment comparison scripts; output images
  saved alongside and copied into `reports/` companion folders

Per-experiment analysis lives inside `runs/<experiment>/` so each run
directory stays self-contained.

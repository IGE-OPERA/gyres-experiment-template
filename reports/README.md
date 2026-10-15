# reports/

Dated, shareable experiment-series reports:

```
<YYYY-MM-DD-description>/
  series.yaml                 # name, gyres_commit, machine, experiments, status
  <YYYY-MM-DD-title>.md       # the report (relative image links)
  <YYYY-MM-DD-title>/         # companion images (copied, committed)
```

`series.yaml.gyres_commit` must match the manifest commit of every member
experiment. Reports are immutable once shared — write a new dated report
instead. Schema details: `../AGENTS.md` §11.

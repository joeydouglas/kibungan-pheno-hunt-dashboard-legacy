# Kibungan Pheno Hunt — Legacy Static Dashboard

Generated static dashboard for the **Kibungan** Filipino landrace pheno hunt,
split out of `joeydouglas/kibungan-pheno-hunt` (NICK-701) so that repo can be
a pure markdown data repo.

- `index.html`, `style.css`, `plants/<ID>.html` — output of `generate_dashboard.py`
- Plant ID convention: TWO prefixes share one population — `PK01`, `PK03`, ...
  and `PL05`, `PL06`, ... (both route to the same project).

Record of truth is **not** here: it lives as `project.md` + `plants/<ID>.md` in
**https://github.com/joeydouglas/kibungan-pheno-hunt**, which `breeding-data-api`
clones and the shared `breeding-frontend` renders. This repo holds the generated
static HTML only, kept as a working checkout until Task 7.3 retires it.

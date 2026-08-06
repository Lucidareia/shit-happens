# Case list

| # | Case | Status | Link |
|---|---|---|---|
| 0000 | Case template | — | [`0000-template/`](0000-template/) |
| 0001 | Missing cat | HappensNow | [`0001-cat-missing/`](0001-cat-missing/) |
| 0002 | Traffic incident | NotValidated | [`0002-traffic-incident/`](0002-traffic-incident/) |
| 0003 | House damaged by a hurricane | NotValidated | [`0003-hurricane-house-damaged/`](0003-hurricane-house-damaged/) |
| 0004 | Layoff | NotValidated | [`0004-layoff/`](0004-layoff/) |

This list is maintained by hand — whoever adds or changes a case updates it in the same PR.

## Conventions

A case is one numbered folder (`NNNN-slug`). Inside it, `index.md` holds the case's data and
its status, `README.md` is the case's front door, and anything deeper is up to the case.
Statuses: `NotValidated` · `HappensNow` · `Validated` — `HappensNow` means someone is inside
the situation right now. Validation is human review of the PR.

A case whose `README.md` opens with a **Case seed** note is a seed: the situation is named but the
material hasn't been worked through yet. Seeds are where contribution helps most — the note stays
until the case has content behind it.

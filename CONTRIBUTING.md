# Contributing

Anyone on the internet can open a PR — to add a new case, upload validation evidence, or
enrich an existing case.

## Adding a new case

1. Copy [`0000-template/`](0000-template/) into `shitlog/NNNN-slug/`, using the next free
   number.
2. Fill it in.
3. Add the case to the list in [`shitlog/README.md`](shitlog/README.md) in the same PR.

A new case is born `NotValidated` — unless it's genuinely live for you right now, in which
case it's `HappensNow` (someone is inside the situation right now; contributions are worth
the most then).

## Validation

Validation is human-gated: the maintainer reviews the PR — that *is* the validation. There
are no checks to run and no CI.

## Numbering etiquette

Two PRs opened at the same time can both claim the same number — whoever merges second
renames to the next free number.

## License

Contributions land under the repo license, [CC BY-SA 4.0](LICENSE).

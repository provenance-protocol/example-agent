# example-agent

A reference **Provenance declaration** for an imaginary research agent — the
file developers can copy, and the one watchers can point at to see the
Provenance Protocol working.

- [`PROVENANCE.yml`](PROVENANCE.yml) — the signed declaration (spec 0.2; the signature covers every field)
- Check it yourself: `npx provenance-protocol verify provenance:github:provenance-protocol/example-agent`
- Write your own: `npx provenance-protocol init`

This repository's history includes deliberate changes — a promise removed, a
file reformatted — used to demonstrate how watchers detect and classify
changes. There is no running agent behind it.

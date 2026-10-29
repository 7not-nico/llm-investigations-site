---
layout: default
title: llm-investigations — four LLM studies
description: Four LLM investigations rendered from markdown; source PDFs linked.
---

# llm-investigations

Four LLM investigations, rendered from the repo markdown. Source PDFs are linked, not hosted — see each investigation's `raw/*-papers.md`.

## Investigations

- [llm-item-omission](llm-item-omission/) — which item kind gets dropped, and whether the corpus can say so
  - [meta-audit](llm-item-omission/meta-audit.html) · [granular](llm-item-omission/granular-investigation/can-this-corpus-say-which-item-kind-gets-dropped.html) · [source](https://github.com/7not-nico/llm-investigations/tree/main/llm-item-omission)
- [llm-operator-meta-audit](llm-operator-meta-audit/) — early/late operator mechanism, instruction tuning, token reduction, negation processing
  - [meta-audit](llm-operator-meta-audit/meta-audit.html) · [granular ×4](llm-operator-meta-audit/granular-investigation/does-the-early-late-operator-mechanism-have-a-source.html) · [sources](llm-operator-meta-audit/raw/operator-fidelity-papers.html) · [source](https://github.com/7not-nico/llm-investigations/tree/main/llm-operator-meta-audit)
- [llm-semantic-weight](llm-semantic-weight/) — function-word heads, determiner recruitment, where meaning lives
  - [meta-audit](llm-semantic-weight/meta-audit.html) · [granular ×4](llm-semantic-weight/granular-investigation/are-function-word-heads-a-general-llm-finding.html) · [sources](llm-semantic-weight/raw/function-word-and-agreement-papers.html) · [source](https://github.com/7not-nico/llm-investigations/tree/main/llm-semantic-weight)
- [llm-specification-gotcha-contraction](llm-specification-gotcha-contraction/) — middle vs early layer negation, declarative rewrites, the 40% threshold, priming evidence
  - [meta-audit](llm-specification-gotcha-contraction/meta-audit.html) · [granular ×4](llm-specification-gotcha-contraction/granular-investigation/do-middle-and-early-layers-disagree-about-negation.html) · [sources](llm-specification-gotcha-contraction/raw/negative-constraint-papers.html) · [source](https://github.com/7not-nico/llm-investigations/tree/main/llm-specification-gotcha-contraction)

Each folder ships `meta-audit.md`, `granular-investigation/`, `raw/` (source notes + paper links), and `_schema/` where present.

Repo: [7not-nico/llm-investigations](https://github.com/7not-nico/llm-investigations)
EOF
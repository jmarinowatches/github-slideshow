---
layout: slide
title: "Workflow"
---

1. Parse arguments (`$ARGUMENTS`, `--mode`, `--voice`, `--file`, ...)
2. Detect AI patterns across the 55-pattern catalog
3. Apply rewrite craft: voice injection, concretizer pass, burstiness
4. Execute per mode: `detect` reports, `rewrite` transforms, `edit` patches in place
5. Final quality check, plus an optional `--score` and `--iterate N` convergence loop

No fabrication: sharpen and restructure, but never invent facts, names, dates, or quotes.

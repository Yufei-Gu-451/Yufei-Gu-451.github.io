---
title: Topic Name — Paper List
subtitle: One-sentence description shown on the hub page and per-list page.
status: active            # "active" while you still add to it, "archived" once you stop
date: 2026-06-04          # YYYY-MM-DD; used for sorting and the timeline badge
---

<!--
HOW TO ADD A NEW READING LIST
=============================
1. Copy this file: `cp _reading_lists/_TEMPLATE.md _reading_lists/<slug>.md`
2. Fill in front matter above. Slug becomes the URL: /reading-lists/<slug>/
3. Paste the body content below this comment.
4. Set `status:` to "active" (still updating) or "archived" (no longer maintained).
5. Commit. The hub page at /reading-lists/ picks it up automatically.

YUQUE EXPORT CLEANUP
====================
When pasting from Yuque, fix these export artifacts:
- Remove all `<font style="color:rgb(...);">…</font>` wrappers — they hard-code
  colors that fight the site theme.
- Replace `:::tips … :::` / `:::warning … :::` fences with regular `## Heading`
  sections (kramdown won't render the Yuque fence syntax).
- Convert `####` Yuque sub-headings to `##` so they match the page hierarchy
  (this layout uses one H1 in the page intro and H2 per section).
- Escape backslash-LaTeX: `\muP` -> `\\muP`, or just write `μP`.
- De-duplicate any entries that appear twice in the source.

ENTRY FORMAT
============
Top-level (primary) papers use numbered lists. Nested follow-up / derivative
papers use bullets (`-`) so the visual hierarchy mirrors the lineage:

  1. *Paper Title.* Venue Year. [\<label\>](https://example.com)
     - *Follow-up Paper.* Venue Year. [\<arxiv\>](https://arxiv.org/abs/...)
        - *Further-derivative Paper.* Venue Year.

Prefer venue links (ICLR/ICML/NIPS/CVPR) over arXiv when both exist; fall back
to arXiv for preprints. Use `\<label\>` angle brackets to match site style.
-->

## Section 1

1. *Example Paper Title.* Venue Year. [\<link\>](https://example.com)
    - *Follow-up Paper.* Venue Year. [\<arxiv\>](https://arxiv.org/abs/0000.00000)
        - *Further-derivative Paper.* Venue Year.

## Section 2

1. *Another Paper.* Venue Year.

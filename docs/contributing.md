---
title: Contributing
---

# Contributing to the Knowledge Base

This wiki is built to grow. Anyone on the team can add or improve a page. Here's how to do it without breaking things or drifting in quality.

## The 5-minute version

1. Click the **:material-pencil: edit** button at the top of any page (opens GitHub).
2. Make your change in Markdown.
3. Write a short note describing the change and commit.
4. The site rebuilds and republishes automatically within ~1–2 minutes.

For a **new page**, copy [`docs/templates/page-template.md`](https://github.com/lunatech2022/DHealth/blob/main/docs/templates/page-template.md), drop it in the right section folder, and add it to the `nav:` in `mkdocs.yml`.

## Quality bar (every page)

- [ ] **Level tag** set (Beginner / Intermediate / Advanced).
- [ ] **"In one sentence"** summary a non-scientist could repeat.
- [ ] Built **simple → advanced** within the page.
- [ ] Every factual claim has an **inline footnote citation**.
- [ ] A **"Why it matters for Dayhoff / DHealth"** section connecting science to commercial value.
- [ ] All citations resolve to an entry in [References](resources/references.md).
- [ ] No unverified or vendor-marketing claims presented as fact.

## Writing style

- Lead with the plain-language answer, then add depth.
- Define a term the first time it appears, and link it to the [Glossary](foundations/glossary.md).
- Use admonitions (`!!! note`, `!!! warning`, `!!! example`) to separate "nice to know" from core content.
- Prefer tables for comparisons (e.g. method A vs method B).
- Keep customer-facing claims conservative and cited.

## Folder structure

```
docs/
├── index.md                # Home + learning paths
├── foundations/            # Microbiome 101 (Beginner)
├── testing/                # NGS, 16S, shotgun, workflow
├── epigenetics/            # Methylation & epigenomics
├── interpreting/           # Reading results
├── clinical/               # Use cases, competitors, sales FAQs
├── advanced/               # Pipelines, databases, limitations
├── resources/              # References + further reading
└── templates/              # page-template.md
```

## Adding a citation

See the full convention in [References](resources/references.md). Short version: use a Markdown footnote at the point of the claim, key it `firstauthorYYYY`, and include a DOI.

## Review

For anything customer-facing (sales FAQs, competitive claims, clinical applications), get a **second reviewer** before merging. Mark the page's "Last reviewed" date when you do.

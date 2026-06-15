---
title: "Reference Databases"
tags:
  - advanced
  - databases
  - bioinformatics
---

# Reference Databases

!!! info "Page status"
    **Level:** Advanced &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Explain the reference databases that pipelines compare reads against, and why a result is only as good as the database behind it.

## In one sentence

Reference databases are the curated catalogues of known sequences that pipelines compare your reads against, and their completeness directly limits how accurately microbes and functions can be named.

## Key points

- A sequencing read means nothing until it is matched to a reference; databases are that reference.
- Public, widely used standards exist for **taxonomy** (e.g. SILVA, GTDB) and **function** (e.g. KEGG).
- Taxonomy databases answer "who is this"; function databases answer "what can it do".
- Results depend on database completeness: missing or mislabelled entries lead to gaps and errors.
- Databases are versioned and updated; the version used affects reproducibility.

!!! abstract "In simple terms"
    A snippet of genetic code is meaningless on its own; it only gets a name when it's matched against a reference catalogue, like looking up a word in a dictionary. These catalogues list the known microbes and the jobs their genes do. The catch is that no dictionary is complete: if a microbe isn't in the book yet, it can't be named properly, or it gets matched to its closest known cousin. So every result is really a "best match against what's known today," not the final word.

## The detail

**Why databases matter.** Profiling works by comparison: a read is identified by finding its closest match in a reference. Best-practice guidance stresses that the choice and quality of reference data is a core determinant of result accuracy, on par with the wet-lab and computational steps.[^knight2018] No database, no name.

**Taxonomy databases.** Several public scientific resources are treated as industry standards for naming microbes:

- **SILVA** — a comprehensive, quality-checked reference of ribosomal RNA gene sequences, widely used for 16S-based taxonomy.
- **GTDB (Genome Taxonomy Database)** — a standardised, genome-based taxonomy that brings consistency to microbial classification.

These are public scientific databases maintained by the research community, not commercial vendors.

**Function databases.** To describe what a community can *do*, pipelines map genes to functional references:

- **KEGG (Kyoto Encyclopedia of Genes and Genomes)** — a widely used resource linking genes to pathways and functions.

Functional annotation from shotgun data leans heavily on resources like these to translate raw genes into interpretable pathways.[^quince2017]

**Completeness is the catch.** A database can only match what it contains. If an organism or gene is absent, underrepresented, or mislabelled, the pipeline cannot identify it correctly, it may be missed, assigned to the nearest known relative, or mislabelled. Because microbial diversity is vast and still being catalogued, every database has gaps, and best practice is to acknowledge this rather than treat a reference as complete truth.[^knight2018]

| Database | Type | Answers | Note |
|---|---|---|---|
| SILVA | Taxonomy (rRNA) | Who is this (16S)? | Public standard |
| GTDB | Taxonomy (genome) | Who is this (standardised)? | Public standard |
| KEGG | Function | What can it do? | Pathways & functions[^quince2017] |

!!! tip "So what?"
    A result is a *best match against a known catalogue*, not an absolute identity. If a buyer asks "how do you know what's in my sample?", the honest answer is: we compare it to the best public reference databases, and we are clear that those databases, while excellent, are not exhaustive.

## Why it matters for Dayhoff / DHealth

Database choice and version shape accuracy and reproducibility, so they are part of why results can be trusted, and part of why honesty about gaps builds credibility. Being able to name SILVA, GTDB, and KEGG as recognised public standards signals technical seriousness without revealing anything internal.

## Common questions

- **Why might a microbe be "unclassified"?** It may be absent from the reference database or too novel to match confidently.[^knight2018]
- **Do different databases give different answers?** They can, because they use different sequences, scopes, and naming conventions; version matters for reproducibility.
- **Are these databases proprietary?** No, SILVA, GTDB, and KEGG are public scientific resources used across the field.

### References

[^knight2018]: Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [DOI](https://doi.org/10.1038/s41579-018-0029-9)
[^quince2017]: Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [DOI](https://doi.org/10.1038/nbt.3935)

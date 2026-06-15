---
title: "Bioinformatics Pipelines"
tags:
  - advanced
  - bioinformatics
  - pipeline
---

# Bioinformatics Pipelines

!!! info "Page status"
    **Level:** Advanced &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Explain how raw sequencing reads become interpretable results, so technically curious team members understand what happens between sample and report.

## In one sentence

A bioinformatics pipeline is the ordered series of computational steps that cleans raw sequencing reads, removes human DNA, identifies which microbes are present, and works out what they can do.

## Key points

- A pipeline runs in stages: **QC → host-read removal → taxonomic profiling → functional annotation**.
- Quality control trims and filters low-quality reads before anything else.
- Host (human) DNA is removed so it does not contaminate microbial results.
- Taxonomic profiling answers "who is here"; functional annotation answers "what can they do".
- The field shifted from clustering reads into **OTUs** to resolving exact **ASVs** (amplicon sequence variants).

!!! abstract "In simple terms"
    Turning a raw sample into a readable report is like an assembly line. First, blurry or sloppy readings get cleaned up and tossed out. Next, your own human DNA is filtered away so it doesn't drown out the microbes. Then the leftover bits are matched up to figure out which microbes are present, and finally what those microbes can actually do. The same care a good kitchen takes prepping ingredients is what keeps the final result trustworthy rather than a black box.

## The detail

**1. Quality control (QC).** Sequencing machines produce reads with errors and low-quality stretches. The first stage trims adapters, drops low-quality bases, and removes reads that fail thresholds. Best-practice guidance treats rigorous QC as non-negotiable, because errors introduced here propagate through every later step.[^knight2018] Sequencing-technology characteristics, read length, error profile, throughput, all shape how QC is tuned.[^goodwin2016]

**2. Host-read removal.** Human samples contain large amounts of human DNA. Pipelines align reads against the human genome and discard matches, so downstream microbial profiling is not skewed by host sequence. This matters most for shotgun data, where all DNA, not just a marker gene, is sequenced.[^quince2017]

**3. Taxonomic profiling.** This stage assigns reads to microbes. For marker-gene (16S) data, reads are compared against reference databases to name taxa. For shotgun data, reads are classified across the whole community, enabling finer resolution.[^quince2017] The output is a profile of who is present and in what relative abundance.

**4. Functional annotation.** Shotgun data also carries genes, so pipelines can map reads to functional categories and pathways, describing what the community is *capable* of doing, not just who is there. Meta-omics approaches extend this further, layering transcriptomic, proteomic, and metabolomic readouts to move from potential function toward actual activity.[^metaomics2019]

**The OTU-to-ASV shift.** Historically, similar 16S reads were clustered into **Operational Taxonomic Units (OTUs)** at a fixed similarity threshold (often 97%), a pragmatic way to absorb sequencing error but one that blurs fine distinctions. The field has largely moved to **Amplicon Sequence Variants (ASVs)**, also called exact sequence variants, which model and correct error to resolve single-nucleotide differences. ASVs are more reproducible and comparable across studies, and current best-practice guidance favours this exact-variant approach.[^knight2018]

| Stage | Question answered | Key risk if done poorly |
|---|---|---|
| QC | Are reads clean? | Errors propagate downstream[^knight2018] |
| Host removal | Is this microbial? | Human DNA skews results[^quince2017] |
| Taxonomic profiling | Who is here? | Misassignment, false taxa |
| Functional annotation | What can they do? | Overstating capability vs. activity[^metaomics2019] |

!!! tip "So what?"
    When someone asks "how do you turn a sample into a report?", walk them through the four stages and the OTU-to-ASV shift. It shows the result is the product of careful engineering, not a black box, which is reassuring to technical buyers.

## Why it matters for Dayhoff / DHealth

The pipeline *is* the product behind the result. Knowing the stages lets you explain why quality and method matter, why results are trustworthy, and where the genuine hard work lives. It also equips you to answer pointed technical questions without overclaiming.

## Common questions

- **Why remove human DNA?** It can dominate a sample and would otherwise distort which microbes appear present.
- **What's wrong with OTUs?** They cluster reads at a fixed threshold and blur fine differences; ASVs resolve exact variants and are more reproducible.[^knight2018]
- **Does the pipeline tell us what microbes are actually doing?** Functional annotation shows potential; confirming activity needs meta-omics layers like transcriptomics.[^metaomics2019]

### References

[^knight2018]: Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [DOI](https://doi.org/10.1038/s41579-018-0029-9)
[^quince2017]: Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [DOI](https://doi.org/10.1038/nbt.3935)
[^goodwin2016]: Goodwin S, McPherson JD, McCombie WR. *Coming of age: ten years of next-generation sequencing technologies*. Nat Rev Genet. 2016;17(6):333-351. [DOI](https://doi.org/10.1038/nrg.2016.49)
[^metaomics2019]: *Advancing functional and translational microbiome research using meta-omics approaches*. Microbiome. 2019. [DOI](https://doi.org/10.1186/s40168-019-0767-6)

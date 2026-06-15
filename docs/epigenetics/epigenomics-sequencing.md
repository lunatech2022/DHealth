---
title: "Epigenomics & Methylation Sequencing"
tags:
  - sequencing
  - EM-seq
  - bisulfite
  - DNA-methylation
  - epigenetic-clock
  - biological-age
  - advanced
---

# Epigenomics & Methylation Sequencing

!!! info "Page status"
    **Level:** Advanced &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Explain how DNA methylation is measured across the whole genome, compare the main method families, and introduce biological-age clocks.

## In one sentence

Methylation sequencing reads which positions across the genome carry methyl tags, and different methods (bisulfite-based or enzymatic) achieve this with different trade-offs in quality and coverage.

## Key points

- Methylation is the addition of a methyl group to cytosine, and sequencing reveals this pattern genome-wide.[^moore2012]
- Traditional methods use bisulfite chemistry; enzymatic methyl-seq (EM-seq) uses enzymes instead of harsh chemical conversion.[^han2021]
- For low-input DNA, EM-seq delivered better library quality, higher CpG coverage, and higher consistency than conventional bisulfite (PBAT).[^han2021]
- Both approaches accurately quantify methylation across the genome.[^han2021]
- Methylation patterns can be used to estimate biological age via epigenetic "clocks."

## The detail

To read the epigenome we need to detect, at single-base resolution, which cytosines carry a methyl group.[^moore2012] Because ordinary sequencing cannot tell a methylated cytosine from an unmethylated one directly, methylation methods first convert the DNA in a way that makes the difference readable.

**Traditional bisulfite conversion** is the long-standing approach. Bisulfite chemistry converts unmethylated cytosines to uracil while leaving methylated cytosines intact, so after sequencing the methylation state can be inferred base by base. Whole-genome bisulfite sequencing and library variants such as **PBAT** (post-bisulfite adapter tagging) fall into this family.[^han2021] The chemistry is well validated but harsh, which can damage and fragment DNA, an issue that matters most when only a small amount of starting material is available.

**Enzymatic methyl-seq (EM-seq)** reaches the same readout using enzymes rather than chemical conversion.[^han2021] In a head-to-head comparison for **low-input DNA**, both EM-seq and PBAT accurately quantified methylation genome-wide, but EM-seq produced **better library and sequencing quality, higher CpG coverage, and higher consistency**.[^han2021] That makes enzymatic approaches especially attractive when sample material is limited.

| Method family | Conversion | Notable trait |
| --- | --- | --- |
| Bisulfite (e.g. WGBS, PBAT) | Chemical | Established; harsher on DNA[^han2021] |
| Enzymatic (EM-seq) | Enzymatic | Better quality, coverage, consistency on low-input DNA[^han2021] |

**Target enrichment** is a complementary strategy. Rather than sequencing the entire genome, a methylome panel focuses sequencing on the most informative regions, concentrating coverage where it is most useful and making large studies more efficient.

A newer direction is **combined readouts**: library preparations designed so that a single sequencing run can report both methylation state and underlying genetic variants from the same molecules. Read generically, this means one assay can capture two layers of biology at once, reducing sample use and linking epigenetic and genetic signals.

Finally, methylation data underpins **epigenetic clocks**. By measuring methylation at a defined set of sites and feeding those values into a mathematical model, researchers can estimate a person's **biological age**, an indicator of how the body is aging that can differ from chronological age. The concept is to translate a methylation pattern into a single, interpretable age-related score.

!!! tip "So what?"
    Enzymatic methods like EM-seq are particularly valuable when only a little DNA is available, because they preserve more of the sample while still quantifying methylation accurately and with higher coverage than conventional bisulfite.[^han2021] That means more reliable results from smaller, less invasive samples.

## Why it matters for Dayhoff / DHealth

This page explains the "how" behind our methylation results. When a customer asks how methylation is measured, or why one method is chosen over another, the team can speak to the bisulfite-versus-enzymatic trade-off, the value of targeted panels, and the emerging promise of biological-age clocks, all without naming any specific vendor or partner.

## Common questions

**What is the difference between bisulfite and EM-seq?**
Both reveal methylation genome-wide, but bisulfite uses chemical conversion while EM-seq uses enzymes. On low-input DNA, EM-seq showed better quality, coverage, and consistency.[^han2021]

**Why use a methylome panel instead of sequencing everything?**
A panel focuses sequencing on the most informative regions, making studies more efficient while still capturing the signals that matter.

**What is a biological-age clock?**
It is a model that turns methylation measurements into an estimate of biological age, which can differ from your calendar age.

---

### References

[^moore2012]: Moore LD, Le T, Fan G. *DNA methylation and its basic function*. Neuropsychopharmacology. 2013;38(1):23-38. [DOI](https://doi.org/10.1038/npp.2012.112)
[^han2021]: Han Y, Zheleznyakova GY, Marincevic-Zuniga Y, et al. *Comparison of EM-seq and PBAT methylome library methods for low-input DNA*. Epigenetics. 2021;17(10):1195-1204. [DOI](https://doi.org/10.1080/15592294.2021.1997406)

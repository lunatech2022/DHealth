---
title: "Shotgun Metagenomic Sequencing"
tags:
  - shotgun
  - metagenomics
  - sequencing
  - microbiome
  - bioinformatics
  - testing-methods
---

# Shotgun Metagenomic Sequencing

!!! info "Page status"
    **Level:** Intermediate &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Explain how shotgun metagenomics reads *all* the DNA in a sample, the deeper insight it unlocks (species, strains, function), and the tradeoffs that come with that power.

## In one sentence

Shotgun metagenomics sequences all the DNA in a sample at once, identifying microbes to the species and strain level and revealing what they can *do* — at the cost of more money, compute, and complexity.

## Key points

- **Reads everything.** Not just one gene — all DNA from bacteria, archaea, viruses, and eukaryotes.[^quince2017]
- **Higher resolution.** Enables species- and strain-level identification.[^quince2017]
- **Functional insight.** Profiles pathways, antibiotic-resistance and virulence genes — what the community *does*, not just who's there.[^quince2017]
- **Catches non-bacterial members** that 16S misses entirely.[^quince2017]
- **More sensitive in practice.** Head-to-head on the same stool samples, shotgun identified more species per sample than 16S.[^laudadio2018]
- **Tradeoffs:** higher cost, heavier computation, host-DNA contamination, and reference-database gaps.

## The detail

**The core idea.** Where 16S reads one targeted gene, shotgun metagenomics chops up and sequences *all* the DNA in a sample. That includes not just bacteria but archaea, viruses, and eukaryotes — the whole genetic community.[^quince2017] This matters because many microbes are hard or impossible to culture, and a 16S survey blind to non-bacterial members will simply miss them.[^quince2017]

**Higher resolution and function.** Reading whole genomes rather than a single barcode gene lets shotgun resolve organisms to the species and even strain level. Crucially, it also reveals **functional** information: the metabolic pathways present, and genes for antibiotic resistance or virulence. So shotgun answers two questions at once — *who is here* and *what can they do*.[^quince2017] More broadly, meta-omics approaches — metagenomics together with metatranscriptomics and metabolomics — are what let researchers read microbial **function**, not just taxonomy.[^metaomics2019] Analysis can proceed by assembling reads into longer genome fragments (assembly-based) or by mapping reads to references (mapping-based).[^quince2017]

**Real-world sensitivity.** This isn't just theoretical. In a direct head-to-head on the same human stool samples, shotgun sequencing identified more species per sample than 16S amplicon sequencing.[^laudadio2018] For clinical contexts, untargeted sequencing of all genetic material is also what allows metagenomic NGS to detect pathogens that conventional, culture-based diagnostics miss.[^gu2019]

**Scale and applications.** Because it captures whole genomes, shotgun metagenomics powers studies at population scale. Shotgun sequencing of 250 adult twins, for instance, revealed both the heritability of specific gut taxa and functions and disease-associated functional modules.[^xie2016] The same depth supports longitudinal work: metagenomic profiling has been used to trace how the gut microbiome develops through distinct phases in early childhood.[^stewart2018]

**The tradeoffs — set expectations.** Power comes at a price:

| Dimension | Shotgun reality |
| --- | --- |
| Cost | Higher per sample than 16S |
| Compute | Heavier data and bioinformatics load |
| Host DNA | Human/host DNA can dominate and must be filtered |
| Databases | Resolution is limited by gaps in reference databases |

For a structured decision on 16S versus shotgun, see the [16S vs Shotgun](../testing/16s-vs-shotgun.md) page.

!!! tip "So what?"
    Shotgun is the right call when a customer needs confident species/strain identity, functional and resistance-gene insight, or detection of viruses and other non-bacterial members. It reliably finds more than 16S on the same sample — the upgrade is real, not marketing.[^laudadio2018] [^quince2017]

## Why it matters for Dayhoff / DHealth

Shotgun is our premium, high-resolution offering and a clear differentiator from commodity 16S testing. When customers care about strain-level identity, antimicrobial resistance, or catching organisms that 16S can't see, this is the method to lead with. Being precise about both its advantages *and* its cost/compute tradeoffs lets the team position it as the right tool for the right job, rather than overselling.

## Common questions

**Q: How is shotgun different from 16S, in one line?**
16S reads one gene; shotgun reads all the DNA — so it can identify more organisms and reveal their functions.[^quince2017]

**Q: Will shotgun really find more than 16S?**
Yes. In a same-sample comparison on stool, shotgun identified more species per sample.[^laudadio2018]

**Q: Why does shotgun cost more?**
It sequences far more material and needs heavier computation and bioinformatics to interpret, plus filtering of host DNA.

### References

[^quince2017]: Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [DOI](https://doi.org/10.1038/nbt.3935)
[^laudadio2018]: Laudadio I, Fulci V, Palone F, Stronati L, Cucchiara S, Carissimi C. *Quantitative Assessment of Shotgun Metagenomics and 16S rDNA Amplicon Sequencing in the Study of Human Gut Microbiome*. OMICS. 2018;22(4):248-254. [DOI](https://doi.org/10.1089/omi.2018.0013)
[^gu2019]: Gu W, Miller S, Chiu CY. *Clinical Metagenomic Next-Generation Sequencing for Pathogen Detection*. Annu Rev Pathol. 2019;14:319-338. [DOI](https://doi.org/10.1146/annurev-pathmechdis-012418-012751)
[^xie2016]: Xie H, Guo R, Zhong H, et al. *Shotgun metagenomics of 250 adult twins reveals genetic and environmental impacts on the gut microbiome*. Cell Syst. 2016;3(6):572-584. [DOI](https://doi.org/10.1016/j.cels.2016.10.004)
[^metaomics2019]: Zhang X, Li L, Butcher J, Stintzi A, Figeys D. *Advancing functional and translational microbiome research using meta-omics approaches*. Microbiome. 2019;7(1):154. [DOI](https://doi.org/10.1186/s40168-019-0767-6)
[^stewart2018]: Stewart CJ, Ajami NJ, O'Brien JL, et al. *Temporal development of the gut microbiome in early childhood from the TEDDY study*. Nature. 2018;562(7728):583-588. [DOI](https://doi.org/10.1038/s41586-018-0617-x)

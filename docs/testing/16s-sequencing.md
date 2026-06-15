---
title: "16S rRNA Sequencing"
tags:
  - 16S
  - amplicon
  - sequencing
  - microbiome
  - testing-methods
---

# 16S rRNA Sequencing

!!! info "Page status"
    **Level:** Intermediate &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Explain how 16S amplicon sequencing identifies bacteria, where it shines, and where its resolution and biases fall short — so the team can position it honestly against shotgun.

## In one sentence

16S sequencing reads one specific bacterial "barcode" gene to identify which bacteria are present, usually down to the genus level — a cheap, well-established method with real resolution limits.

## Key points

- **It targets one gene:** the 16S rRNA gene, found in all bacteria.
- **That gene has conserved and variable regions.** Conserved parts let us grab the gene across species; variable parts let us tell species apart.[^johnson2019]
- **Workflow:** PCR-amplify the variable region, sequence it, match to a reference database.
- **Strengths:** cheap, robust, established, well-supported by reference databases.
- **Limits:** typically genus-level resolution; species/strain ID is limited; PCR amplification can introduce bias.[^johnson2019] [^ziesemer2015]

## The detail

**The core idea.** Every bacterium carries a gene called 16S rRNA. Think of it as a barcode: it's present in all bacteria, but its exact sequence varies between species. The gene is a mix of **conserved regions** (nearly identical across all bacteria) and **hypervariable regions** (which differ from species to species).[^johnson2019]

**How the method works.** Because the conserved regions are shared, we can design PCR primers that latch onto them and copy ("amplify") the variable region in between, across whatever bacteria are in the sample. We then sequence those amplified fragments — the "amplicons" — and compare them against a reference database to assign a name. This is why 16S is called an *amplicon* method: we read one targeted, amplified gene region rather than everything in the sample.

**Why it's popular.** 16S is inexpensive, robust, and decades-established, with mature reference databases and analysis pipelines. For surveying *who is roughly there* across many samples, it's a practical workhorse, and best-practice guidance for microbiome studies is well developed.[^knight2018]

**The limits — be honest about these.** Targeting a short variable region cannot match the taxonomic resolution you'd get from the full-length gene, so species- and strain-level identification is limited; in practice 16S often resolves only to genus.[^johnson2019] Intragenomic variation in 16S copies further complicates fine resolution.[^johnson2019] Separately, the PCR amplification step itself can introduce bias: primers amplify some taxa more efficiently than others, distorting the apparent community — a documented problem that has led researchers to favor shotgun approaches in some settings.[^ziesemer2015]

For a direct, side-by-side comparison of when to choose 16S versus shotgun, see the [16S vs Shotgun](../testing/16s-vs-shotgun.md) page.

!!! tip "So what?"
    16S is a great low-cost screen for "which broad groups of bacteria are here," especially across many samples. But when a customer needs confident species/strain calls or unbiased abundance, its genus-level ceiling and PCR bias are real constraints to flag up front — and a natural bridge to a shotgun conversation.[^johnson2019] [^ziesemer2015]

## Why it matters for Dayhoff / DHealth

16S is often the customer's entry point: familiar, affordable, and "good enough" for broad surveys. Knowing exactly what it can and cannot deliver lets the team recommend it where it fits and upsell to shotgun where resolution or accuracy matters — without overpromising. Framing the limits as inherent to the method (not to us) builds trust.

## Common questions

**Q: Can 16S tell me the exact species or strain?**
Usually not. Short variable regions limit resolution, and results often land at the genus level.[^johnson2019]

**Q: Why might two labs get different 16S abundance results?**
PCR primers amplify some taxa more than others, which can bias the apparent community composition.[^ziesemer2015]

**Q: If 16S has limits, why use it at all?**
It's cheap, robust, well-established, and supported by mature best-practice workflows — ideal for broad surveys across many samples.[^knight2018]

### References

[^johnson2019]: Johnson JS, Spakowicz DJ, Hong BY, et al. *Evaluation of 16S rRNA gene sequencing for species and strain-level microbiome analysis*. Nat Commun. 2019;10(1):5029. [DOI](https://doi.org/10.1038/s41467-019-13036-1)
[^ziesemer2015]: Ziesemer KA, Mann AE, Sankaranarayanan K, et al. *Intrinsic challenges in ancient microbiome reconstruction using 16S rRNA gene amplification*. Sci Rep. 2015;5:16498. [DOI](https://doi.org/10.1038/srep16498)
[^knight2018]: Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [DOI](https://doi.org/10.1038/s41579-018-0029-9)

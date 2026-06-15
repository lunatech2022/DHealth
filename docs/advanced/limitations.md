---
title: "Limitations & Caveats"
tags:
  - advanced
  - limitations
  - caveats
---

# Limitations & Caveats

!!! info "Page status"
    **Level:** Advanced &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Set out, honestly, what microbiome methods cannot tell you, so the team can represent the science with integrity and field tough questions well.

## In one sentence

Microbiome testing is powerful but bounded: it measures relative composition rather than absolute amounts, detects DNA rather than activity, and is shaped by reference gaps, technical bias, and the difference between correlation and causation.

## Key points

- Results are **compositional**: relative proportions, not absolute counts.
- **DNA presence is not activity**: detecting a microbe does not prove it is doing anything.
- **Database gaps** mean some microbes cannot be identified.
- **Correlation is not causation**: associations are not proof of cause.
- **Primer / amplification bias** and **batch effects** can distort or confound results.

!!! abstract "In simple terms"
    Microbiome testing is genuinely useful, but it has honest limits. It tells you the proportions of microbes, like slices of a pie, not the actual head count, so one slice growing can just make others look smaller. It spots a microbe's DNA but can't tell if that microbe is alive and active or long dead. And because it finds patterns, it can show that two things tend to occur together without proving one caused the other. Knowing these limits is what keeps the results honest.

## The detail

**Compositional data (relative, not absolute).** Sequencing tells you the *proportions* of microbes in a sample, not how many cells there are. If one group rises, others appear to fall simply because percentages sum to 100, even if their true numbers are unchanged. Best-practice guidance treats this compositional nature as a core analytical caveat that must be handled deliberately.[^knight2018]

**DNA presence ≠ activity.** Sequencing detects DNA, which is present whether a microbe is thriving, dormant, or dead. Shotgun data reveals *functional potential*, the genes a community carries, but not whether those genes are being used.[^quince2017] Confirming activity requires additional layers such as transcriptomics, beyond standard DNA profiling.

**Database gaps.** Identification depends on reference databases, which are incomplete. Microbes absent from a database may be missed or misassigned to a nearest known relative.[^knight2018] Results are best matches against a known catalogue, not absolute truth.

**Correlation vs. causation.** Many headline findings link microbial patterns to health outcomes, but the microbiome's role in metabolic health is complex and bidirectional, with cause and effect often unclear.[^fan2020] An association observed in a population does not mean a given microbe caused a given outcome in an individual.

**Primer and amplification bias.** 16S methods amplify a marker gene using primers, and those primers do not bind all taxa equally, so some microbes are over- or under-represented before sequencing even begins.[^johnson2019] Amplification can also distort low-biomass samples; intrinsic challenges in amplifying and reconstructing 16S profiles are well documented, especially where DNA is scarce or degraded.[^ziesemer2015]

**Batch effects.** Differences in collection, extraction, reagents, sequencing run, or pipeline version can introduce systematic, non-biological variation. Without careful study design and controls, these batch effects can be mistaken for real signal.[^knight2018]

| Limitation | What it means | Practical guard |
|---|---|---|
| Compositional | Relative, not absolute[^knight2018] | Interpret proportions carefully |
| DNA ≠ activity | Presence isn't function[^quince2017] | Don't claim activity from DNA |
| Database gaps | Some taxa unidentifiable[^knight2018] | Acknowledge "best match" |
| Correlation | Not causation[^fan2020] | Avoid causal language |
| Primer bias | Uneven amplification[^johnson2019][^ziesemer2015] | Note method limits |
| Batch effects | Technical confounding[^knight2018] | Controls, consistent protocols |

!!! tip "So what?"
    Volunteering limitations is a sales strength, not a weakness. A buyer who hears "here's what this can't tell you" trusts your claims about what it *can*. Honesty is the most durable form of credibility in this field.

## Why it matters for Dayhoff / DHealth

Representing the science honestly protects the company's reputation and the customer relationship. Knowing these caveats lets the team avoid overclaiming, answer skeptical experts credibly, and frame results as genuine insight within clear, well-understood bounds.

## Common questions

- **If a microbe shows up, is it active?** Not necessarily, DNA can come from dormant or dead cells; activity needs further testing.[^quince2017]
- **Does a higher percentage mean there's more of it?** Not on its own, results are relative, so proportions shift even when absolute numbers don't.[^knight2018]
- **Can the test prove a microbe caused my symptom?** No, it shows associations, not causation.[^fan2020]

### References

[^knight2018]: Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [DOI](https://doi.org/10.1038/s41579-018-0029-9)
[^quince2017]: Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [DOI](https://doi.org/10.1038/nbt.3935)
[^johnson2019]: Johnson JS, Spakowicz DJ, Hong BY, et al. *Evaluation of 16S rRNA gene sequencing for species and strain-level microbiome analysis*. Nat Commun. 2019;10(1):5029. [DOI](https://doi.org/10.1038/s41467-019-13036-1)
[^ziesemer2015]: Ziesemer KA, Mann AE, Sankaranarayanan K, et al. *Intrinsic challenges in ancient microbiome reconstruction using 16S rRNA gene amplification*. Sci Rep. 2015;5:16498. [DOI](https://doi.org/10.1038/srep16498)
[^fan2020]: Fan Y, Pedersen O. *Gut microbiota in human metabolic health and disease*. Nat Rev Microbiol. 2021;19(1):55-71. [DOI](https://doi.org/10.1038/s41579-020-0433-9)

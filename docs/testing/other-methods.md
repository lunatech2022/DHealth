---
title: "Other Methods (qPCR, Metatranscriptomics, Culture)"
tags:
  - culture
  - qPCR
  - metagenomics
  - testing-methods
  - sales
---

# Other Methods (qPCR, Metatranscriptomics, Culture)

!!! info "Page status"
    **Level:** Intermediate &nbsp;·&nbsp; **Status:** :material-circle: Drafted &nbsp;·&nbsp; **Last reviewed:** 2026-06-14

> **Purpose:** Map the adjacent technologies — culture, targeted PCR/qPCR, and metatranscriptomics — so the team knows when each is used and how they contrast with untargeted sequencing.

## In one sentence

Culture grows microbes in the lab, targeted PCR/qPCR hunts for organisms you already suspect, and metatranscriptomics measures activity rather than mere presence — each useful, but all narrower than untargeted sequencing in different ways.

## Key points

- **Culture** grows organisms on media, but misses microbes that are hard or impossible to culture.[^quince2017]
- **Targeted PCR/qPCR** is fast and sensitive but only finds the specific targets you design it to look for.
- **Untargeted sequencing** detects organisms conventional, culture-based diagnostics miss — no prior guess required.[^gu2019]
- **Metatranscriptomics** (background): reads RNA to gauge which genes are *active*, not just present.
- **Method choice depends on the question;** best-practice guidance helps match approach to goal.[^knight2018]

## The detail

**Traditional culture.** The classic approach: take a sample, grow microbes on nutrient media, then identify what grew. It remains valuable — it yields live isolates and antibiotic-susceptibility testing. But its central weakness is well documented: *many microbes are hard or impossible to culture*, so a culture-only view systematically misses much of a community.[^quince2017] (That difficulty is one of the main reasons sequencing-based methods exist.)

**Targeted PCR and qPCR.** PCR amplifies a specific DNA sequence; quantitative PCR (qPCR) also measures *how much* of it is present. These methods are fast, sensitive, and inexpensive — excellent when you already know what you're looking for, such as confirming a single suspected pathogen. The catch is structural: a targeted assay only finds the targets it was designed for. If the organism isn't on your list, the test can't see it. By contrast, untargeted sequencing detects organisms that conventional, culture-based diagnostics miss, because it doesn't require naming the suspect in advance.[^gu2019]

**Metatranscriptomics (general background).** The methods above mostly ask *who is present*. Metatranscriptomics asks a different question: *who is active?* It reads RNA — the working transcripts cells produce — rather than DNA, giving a read-out of gene activity rather than mere presence. This is useful background context for understanding the testing landscape; treat it here as a general orientation rather than a specific product claim.

**Choosing a method.** None of these is universally "best." The right choice depends on the clinical or research question — speed, cost, breadth, whether you need live isolates, and whether you need activity vs presence. Established best-practice guidance exists to help match method to goal.[^knight2018]

| Method | Finds | Key limit |
| --- | --- | --- |
| Culture | What grows on media | Misses hard-to-culture organisms[^quince2017] |
| Targeted PCR/qPCR | Pre-specified targets | Blind to anything not on the list |
| Untargeted sequencing | Whatever DNA is present | Higher cost/compute[^gu2019] |
| Metatranscriptomics | Active genes (RNA) | Reflects activity, not just presence *(general background)* |

!!! tip "So what?"
    The deciding question is usually *do you already know what you're looking for?* If yes, fast targeted PCR/qPCR or culture may suffice. If no — or if you want the full picture — untargeted sequencing finds organisms the older methods miss, with no need to guess in advance.[^gu2019] [^quince2017]

## Why it matters for Dayhoff / DHealth

Customers rarely start from a blank slate — they often already use culture or PCR. Knowing exactly where those methods fall short lets the team position untargeted sequencing as complementary, not just competitive: it catches what targeted tests can't anticipate and what culture can't grow. That framing turns "why switch?" into "why settle for a partial view?"

## Common questions

**Q: If we already run PCR for a pathogen, why add sequencing?**
PCR only finds what you target. Untargeted sequencing detects organisms conventional and targeted methods miss.[^gu2019]

**Q: Is culture obsolete?**
No — it gives live isolates and susceptibility data. But it misses the many microbes that won't grow in the lab.[^quince2017]

**Q: What's the difference between "present" and "active"?**
DNA-based methods show what's present; metatranscriptomics reads RNA to indicate which genes are active *(general background)*.

### References

[^quince2017]: Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [DOI](https://doi.org/10.1038/nbt.3935)
[^gu2019]: Gu W, Miller S, Chiu CY. *Clinical Metagenomic Next-Generation Sequencing for Pathogen Detection*. Annu Rev Pathol. 2019;14:319-338. [DOI](https://doi.org/10.1146/annurev-pathmechdis-012418-012751)
[^knight2018]: Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [DOI](https://doi.org/10.1038/s41579-018-0029-9)

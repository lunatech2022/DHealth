---
title: References
---

# Master Reference List

This is the **single source of truth** for citations used across the wiki. The goal: every scientific claim on every page traces back to a real, checkable source.

## How citations work here

We use **Markdown footnotes**. On any page:

```markdown
Shotgun sequencing can resolve organisms to the species or strain level.[^franzosa2015]

[^franzosa2015]: Franzosa EA, et al. *Sequencing and beyond: integrating molecular omics
    microbiome analyses*. Nat Rev Microbiol. 2015;13(6):360-372. doi:10.1038/nrmicro3451
```

The footnote renders as a clickable number that jumps to a formatted reference at the bottom of the page. Material for MkDocs styles this automatically — no plugins needed.

### Rules
1. **One claim, one citation.** If you state a fact, cite it inline at the point of the claim.
2. **Use a stable key.** Format: `firstauthorYYYY` (e.g. `franzosa2015`). If two clash, add a letter: `smith2020a`.
3. **Prefer primary literature and authoritative reviews.** Peer-reviewed > preprint > reputable org page > vendor page.
4. **Always include a DOI or stable URL** so anyone can verify it.
5. **Add the source here too** if it's used on more than one page (see canonical list below), so we have one bibliography.

## Citation format (Vancouver style)

> Author AA, Author BB, et al. *Title of article*. Journal Abbrev. Year;Volume(Issue):Pages. doi:XXXX

---

## Canonical bibliography

_Add sources alphabetically by key as the wiki grows. Each entry should be copy-pasteable as a footnote._

All entries below were retrieved and verified against **PubMed** metadata (real DOIs). Cited on the [16S vs Shotgun](../testing/16s-vs-shotgun.md) page.

- **quince2017** — Quince C, Walker AW, Simpson JT, Loman NJ, Segata N. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017;35(9):833-844. [doi:10.1038/nbt.3935](https://doi.org/10.1038/nbt.3935)
- **johnson2019** — Johnson JS, Spakowicz DJ, Hong BY, et al. *Evaluation of 16S rRNA gene sequencing for species and strain-level microbiome analysis*. Nat Commun. 2019;10(1):5029. [doi:10.1038/s41467-019-13036-1](https://doi.org/10.1038/s41467-019-13036-1)
- **laudadio2018** — Laudadio I, Fulci V, Palone F, Stronati L, Cucchiara S, Carissimi C. *Quantitative Assessment of Shotgun Metagenomics and 16S rDNA Amplicon Sequencing in the Study of Human Gut Microbiome*. OMICS. 2018;22(4):248-254. [doi:10.1089/omi.2018.0013](https://doi.org/10.1089/omi.2018.0013)
- **ziesemer2015** — Ziesemer KA, Mann AE, Sankaranarayanan K, et al. *Intrinsic challenges in ancient microbiome reconstruction using 16S rRNA gene amplification*. Sci Rep. 2015;5:16498. [doi:10.1038/srep16498](https://doi.org/10.1038/srep16498)
- **knight2018** — Knight R, Vrbanac A, Taylor BC, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018;16(7):410-422. [doi:10.1038/s41579-018-0029-9](https://doi.org/10.1038/s41579-018-0029-9)
- **fan2020** — Fan Y, Pedersen O. *Gut microbiota in human metabolic health and disease*. Nat Rev Microbiol. 2021;19(1):55-71. [doi:10.1038/s41579-020-0433-9](https://doi.org/10.1038/s41579-020-0433-9)
- **sorboni2022** — Sorboni SG, Moghaddam HS, Jafarzadeh-Esfehani R, Soleimanpour S. *A Comprehensive Review on the Role of the Gut Microbiome in Human Neurological Disorders*. Clin Microbiol Rev. 2022;35(1):e0033820. [doi:10.1128/CMR.00338-20](https://doi.org/10.1128/CMR.00338-20)
- **gu2019** — Gu W, Miller S, Chiu CY. *Clinical Metagenomic Next-Generation Sequencing for Pathogen Detection*. Annu Rev Pathol. 2019;14:319-338. [doi:10.1146/annurev-pathmechdis-012418-012751](https://doi.org/10.1146/annurev-pathmechdis-012418-012751)
- **goodwin2016** — Goodwin S, McPherson JD, McCombie WR. *Coming of age: ten years of next-generation sequencing technologies*. Nat Rev Genet. 2016;17(6):333-351. [doi:10.1038/nrg.2016.49](https://doi.org/10.1038/nrg.2016.49)
- **rinninella2019** — Rinninella E, Raoul P, Cintoni M, et al. *What is the Healthy Gut Microbiota Composition? A Changing Ecosystem across Age, Environment, Diet, and Diseases*. Microorganisms. 2019;7(1):14. [doi:10.3390/microorganisms7010014](https://doi.org/10.3390/microorganisms7010014)
- **moore2012** — Moore LD, Le T, Fan G. *DNA methylation and its basic function*. Neuropsychopharmacology. 2013;38(1):23-38. [doi:10.1038/npp.2012.112](https://doi.org/10.1038/npp.2012.112)
- **dawson2012** — Dawson MA, Kouzarides T. *Cancer epigenetics: from mechanism to therapy*. Cell. 2012;150(1):12-27. [doi:10.1016/j.cell.2012.06.013](https://doi.org/10.1016/j.cell.2012.06.013)
- **han2021** — Han Y, Zheleznyakova GY, Marincevic-Zuniga Y, et al. *Comparison of EM-seq and PBAT methylome library methods for low-input DNA*. Epigenetics. 2021;17(10):1195-1204. [doi:10.1080/15592294.2021.1997406](https://doi.org/10.1080/15592294.2021.1997406)
- **caspani2019** — Caspani G, Kennedy S, Foster JA, Swann J. *Gut microbial metabolites in depression: understanding the biochemical mechanisms*. Microb Cell. 2019;6(10):454-481. [doi:10.15698/mic2019.10.693](https://doi.org/10.15698/mic2019.10.693)
- **alsharairi2023** — Alsharairi NA. *Therapeutic Potential of Gut Microbiota and Its Metabolite Short-Chain Fatty Acids in Neonatal Necrotizing Enterocolitis*. Life (Basel). 2023;13(2):561. [doi:10.3390/life13020561](https://doi.org/10.3390/life13020561)

_Grows as pages are written. Every page's footnotes should resolve to an entry here._

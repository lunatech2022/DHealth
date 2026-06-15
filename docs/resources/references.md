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

## Primary source library

Verified primary literature from our internal evidence collection. Each title links to its DOI (the canonical, checkable record). Grouped by theme; these are being woven into the relevant pages.

### Healthy microbiome, development & variation
- **hmp2012** — *Structure, function and diversity of the healthy human microbiome*. Nature. 2012. [doi:10.1038/nature11234](https://doi.org/10.1038/nature11234)
- **yatsunenko2012** — *Human gut microbiome viewed across age and geography*. Nature. 2012. [doi:10.1038/nature11053](https://doi.org/10.1038/nature11053)
- **koenig2011** — *Succession of microbial consortia in the developing infant gut microbiome*. PNAS. 2011. [doi:10.1073/pnas.1000081107](https://doi.org/10.1073/pnas.1000081107)
- **stewart2018** — *Temporal development of the gut microbiome in early childhood (TEDDY)*. Nature. 2018. [doi:10.1038/s41586-018-0617-x](https://doi.org/10.1038/s41586-018-0617-x)
- **xie2016** — *Shotgun metagenomics of 250 adult twins reveals genetic and environmental impacts on the gut microbiome*. Cell Syst. 2016. [doi:10.1016/j.cels.2016.10.004](https://doi.org/10.1016/j.cels.2016.10.004)
- **gutmeta2022** — *Gut metagenome associations*. Nat Commun. 2022. [doi:10.1038/s41467-022-28464-9](https://doi.org/10.1038/s41467-022-28464-9)
- **birthmode2018** — *Birth mode and infant gut microbiota in intergenerational transmission of overweight/obesity*. JAMA Pediatr. 2018. [doi:10.1001/jamapediatrics.2017.5535](https://doi.org/10.1001/jamapediatrics.2017.5535)
- **antibiotics2021** — *Neonatal antibiotic exposure impairs child growth*. Nat Commun. 2021. [doi:10.1038/s41467-020-20495-4](https://doi.org/10.1038/s41467-020-20495-4)
- **hygiene2017** — *The hygiene hypothesis in the age of the microbiome*. Ann Am Thorac Soc. 2017. [doi:10.1513/AnnalsATS.201702-139AW](https://doi.org/10.1513/AnnalsATS.201702-139AW)

### Disease associations & function
- **t1d2018** — *The human gut microbiome in early-onset type 1 diabetes (TEDDY)*. Nature. 2018. [doi:10.1038/s41586-018-0620-2](https://doi.org/10.1038/s41586-018-0620-2)
- **akkermansia2021** — *Association between gut Akkermansia and metabolic syndrome*. Diabetes Metab Syndr Obes. 2021. [doi:10.2147/DMSO.S311388](https://doi.org/10.2147/DMSO.S311388)
- **bilophila2019** — *A glycyl radical enzyme enables hydrogen sulfide production by Bilophila wadsworthia*. PNAS. 2019. [doi:10.1073/pnas.1815661116](https://doi.org/10.1073/pnas.1815661116)
- **frailty2016** — *Signatures of early frailty in the gut microbiota*. Genome Med. 2016. [doi:10.1186/s13073-016-0262-7](https://doi.org/10.1186/s13073-016-0262-7)
- **uc2021** — *Ecological and network analyses identify four microbial species relevant to ulcerative colitis*. BMC Microbiol. 2021. [doi:10.1186/s12866-021-02201-6](https://doi.org/10.1186/s12866-021-02201-6)

### Methods, aging & biomarkers
- **metaomics2019** — *Advancing functional and translational microbiome research using meta-omics approaches*. Microbiome. 2019. [doi:10.1186/s40168-019-0767-6](https://doi.org/10.1186/s40168-019-0767-6)
- **microbiomeage2025** — *Chronological age estimation from human microbiomes with transformer-based robust PCA*. Commun Biol. 2025. [doi:10.1038/s42003-025-08590-y](https://doi.org/10.1038/s42003-025-08590-y)

_Some entries are listed by title + DOI; author lists and exact volumes are being completed as each source is integrated into a page._

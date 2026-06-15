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

Verified primary literature from our internal evidence collection, with full citations (authors, journal, volume, year) confirmed against PubMed. Grouped by theme.

### Healthy microbiome, development & variation
- **hmp2012** — Human Microbiome Project Consortium. *Structure, function and diversity of the healthy human microbiome*. Nature. 2012;486(7402):207-214. [doi:10.1038/nature11234](https://doi.org/10.1038/nature11234)
- **yatsunenko2012** — Yatsunenko T, Rey FE, Manary MJ, et al. *Human gut microbiome viewed across age and geography*. Nature. 2012;486(7402):222-227. [doi:10.1038/nature11053](https://doi.org/10.1038/nature11053)
- **koenig2011** — Koenig JE, Spor A, Scalfone N, et al. *Succession of microbial consortia in the developing infant gut microbiome*. Proc Natl Acad Sci U S A. 2011;108(Suppl 1):4578-4585. [doi:10.1073/pnas.1000081107](https://doi.org/10.1073/pnas.1000081107)
- **stewart2018** — Stewart CJ, Ajami NJ, O'Brien JL, et al. *Temporal development of the gut microbiome in early childhood from the TEDDY study*. Nature. 2018;562(7728):583-588. [doi:10.1038/s41586-018-0617-x](https://doi.org/10.1038/s41586-018-0617-x)
- **xie2016** — Xie H, Guo R, Zhong H, et al. *Shotgun metagenomics of 250 adult twins reveals genetic and environmental impacts on the gut microbiome*. Cell Syst. 2016;3(6):572-584. [doi:10.1016/j.cels.2016.10.004](https://doi.org/10.1016/j.cels.2016.10.004)
- **gutmeta2022** — Aasmets O, Krigul KL, Lüll K, Metspalu A, Org E. *Gut metagenome associations with extensive digital health data in a volunteer-based Estonian microbiome cohort*. Nat Commun. 2022;13(1):869. [doi:10.1038/s41467-022-28464-9](https://doi.org/10.1038/s41467-022-28464-9)
- **birthmode2018** — Tun HM, Bridgman SL, Chari R, et al. *Roles of birth mode and infant gut microbiota in intergenerational transmission of overweight and obesity from mother to offspring*. JAMA Pediatr. 2018;172(4):368-377. [doi:10.1001/jamapediatrics.2017.5535](https://doi.org/10.1001/jamapediatrics.2017.5535)
- **antibiotics2021** — Uzan-Yulzari A, Turta O, Belogolovski A, et al. *Neonatal antibiotic exposure impairs child growth during the first six years of life by perturbing intestinal microbial colonization*. Nat Commun. 2021;12(1):443. [doi:10.1038/s41467-020-20495-4](https://doi.org/10.1038/s41467-020-20495-4)
- **hygiene2017** — Ege MJ. *The hygiene hypothesis in the age of the microbiome*. Ann Am Thorac Soc. 2017;14(Suppl 5):S348-S353. [doi:10.1513/AnnalsATS.201702-139AW](https://doi.org/10.1513/AnnalsATS.201702-139AW)

### Disease associations & function
- **t1d2018** — Vatanen T, Franzosa EA, Schwager R, et al. *The human gut microbiome in early-onset type 1 diabetes from the TEDDY study*. Nature. 2018;562(7728):589-594. [doi:10.1038/s41586-018-0620-2](https://doi.org/10.1038/s41586-018-0620-2)
- **akkermansia2021** — Zhou Q, Pang G, Zhang Z, et al. *Association between gut Akkermansia and metabolic syndrome is dose-dependent and affected by microbial interactions*. Diabetes Metab Syndr Obes. 2021;14:2177-2188. [doi:10.2147/DMSO.S311388](https://doi.org/10.2147/DMSO.S311388)
- **bilophila2019** — Peck SC, Denger K, Burrichter A, Irwin SM, Balskus EP, Schleheck D. *A glycyl radical enzyme enables hydrogen sulfide production by the human intestinal bacterium Bilophila wadsworthia*. Proc Natl Acad Sci U S A. 2019;116(8):3171-3176. [doi:10.1073/pnas.1815661116](https://doi.org/10.1073/pnas.1815661116)
- **frailty2016** — Jackson MA, Jeffery IB, Beaumont M, et al. *Signatures of early frailty in the gut microbiota*. Genome Med. 2016;8(1):8. [doi:10.1186/s13073-016-0262-7](https://doi.org/10.1186/s13073-016-0262-7)
- **uc2021** — Li W, Sun Y, Dai L, et al. *Ecological and network analyses identify four microbial species with potential significance for the diagnosis/treatment of ulcerative colitis*. BMC Microbiol. 2021;21(1):138. [doi:10.1186/s12866-021-02201-6](https://doi.org/10.1186/s12866-021-02201-6)

### Disease associations & function (continued)
- **henke2019** — Henke MT, Kenny DJ, Cassilly CD, Vlamakis H, Xavier RJ, Clardy J. *Ruminococcus gnavus, a member of the human gut microbiome associated with Crohn's disease, produces an inflammatory polysaccharide*. Proc Natl Acad Sci U S A. 2019;116(26):12672-12677. [doi:10.1073/pnas.1904099116](https://doi.org/10.1073/pnas.1904099116)
- **glp1micro2023** — Zeng Y, Wu Y, Zhang Q, Xiao X. *Crosstalk between glucagon-like peptide 1 and gut microbiota in metabolic diseases*. mBio. 2023;15(1):e0203223. [doi:10.1128/mbio.02032-23](https://doi.org/10.1128/mbio.02032-23)
- **scfa2023** — Zhang D, Jian YP, Zhang YN, et al. *Short-chain fatty acids in diseases*. Cell Commun Signal. 2023;21(1):212. [doi:10.1186/s12964-023-01219-9](https://doi.org/10.1186/s12964-023-01219-9)

### Sports, nutrition & recovery
- **athletemicro2022** — O'Brien MT, O'Sullivan O, Claesson MJ, Cotter PD. *The Athlete Gut Microbiome and its Relevance to Health and Performance: A Review*. Sports Med. 2022;52(Suppl 1):119-128. [doi:10.1007/s40279-022-01785-x](https://doi.org/10.1007/s40279-022-01785-x)
- **athleteperf2024** — Patel BK, Patel KH, Lee CN, Moochhala S. *Intestinal Microbiota Interventions to Enhance Athletic Performance — A Review*. Int J Mol Sci. 2024;25(18):10076. [doi:10.3390/ijms251810076](https://doi.org/10.3390/ijms251810076)
- **bioactivepeptides2024** — Wijesekara T, Abeyrathne EDNS, Ahn DU. *Effect of Bioactive Peptides on Gut Microbiota and Their Relations to Human Health*. Foods. 2024;13(12):1853. [doi:10.3390/foods13121853](https://doi.org/10.3390/foods13121853)

### Methods, aging & biomarkers
- **metaomics2019** — Zhang X, Li L, Butcher J, Stintzi A, Figeys D. *Advancing functional and translational microbiome research using meta-omics approaches*. Microbiome. 2019;7(1):154. [doi:10.1186/s40168-019-0767-6](https://doi.org/10.1186/s40168-019-0767-6)
- **microbiomeage2025** — Myers T, Song SJ, Chen Y, et al. *Chronological age estimation from human microbiomes with transformer-based robust principal component analysis*. Commun Biol. 2025;8(1):1159. [doi:10.1038/s42003-025-08590-y](https://doi.org/10.1038/s42003-025-08590-y)

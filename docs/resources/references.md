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

!!! example "Starter entries (replace/verify before relying on these)"
    These illustrate the format and are commonly cited foundational works. **Verify the details against the DOI before using in customer-facing material.**

- **franzosa2015** — Franzosa EA, et al. *Sequencing and beyond: integrating molecular omics microbiome analyses*. Nat Rev Microbiol. 2015. doi:10.1038/nrmicro3451
- **quince2017** — Quince C, et al. *Shotgun metagenomics, from sampling to analysis*. Nat Biotechnol. 2017. doi:10.1038/nbt.3935
- **johnson2019** — Johnson JS, et al. *Evaluation of 16S rRNA gene sequencing for species and strain-level microbiome analysis*. Nat Commun. 2019. doi:10.1038/s41467-019-13036-1
- **knight2018** — Knight R, et al. *Best practices for analysing microbiomes*. Nat Rev Microbiol. 2018. doi:10.1038/s41579-018-0029-9

_TODO: build this out as pages are written. Aim for every page's footnotes to resolve to an entry here._

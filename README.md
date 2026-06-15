# DHealth Knowledge Base

Internal wiki for Dayhoff / DHealth covering **microbiome science, NGS testing, methylation, and epigenomics** — structured simple → advanced, fully referenced, for the sales team and new employees.

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and published via GitHub Pages.

## Live site
Once GitHub Pages is enabled: **https://lunatech2022.github.io/DHealth/** _(update if the repo or org changes)_

## Editing
- Quick edits: click the **pencil** icon on any page of the live site.
- New pages: copy `docs/templates/page-template.md`, place it in the right section under `docs/`, and add it to `nav:` in `mkdocs.yml`.
- See [`docs/contributing.md`](docs/contributing.md) for the full guide and quality bar.

## Run locally (optional)
```bash
pip install -r requirements.txt
mkdocs serve
# open http://127.0.0.1:8000
```

## How publishing works
Every push to `main` triggers `.github/workflows/deploy.yml`, which builds the site and deploys it to GitHub Pages. No manual steps after the one-time Pages setup (Settings → Pages → Source: **GitHub Actions**).

## Structure
```
docs/
├── index.md            # Home + learning paths
├── foundations/        # Microbiome 101
├── testing/            # NGS, 16S, shotgun, workflow
├── epigenetics/        # Methylation & epigenomics
├── interpreting/       # Reading results
├── clinical/           # Use cases, competitors, sales FAQs
├── advanced/           # Pipelines, databases, limitations
├── resources/          # References + further reading
└── templates/          # page-template.md
```
Pages marked **Stub** are placeholders to be filled over time.

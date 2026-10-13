
# DATA 712 Midterm Project - Roni Pitkowsky
## Persistence of Racial Disparities in Debt Burden

### Project Structure

- **manuscript/** - Paper files (Rmd, PDF, template)
- **presentations/** - Presentation slides and visualizations
- **data/** - Survey data and processed objects
- **results/** - Cached analysis results (regression, bivariate)
- **scripts/** - R scripts for data processing
- **resources/** - Codebooks, reference PDFs
- **references/** - Bibliographic files (.bib, .csl)
- **archive/** - Old drafts and iterations

### Key Files

- `manuscript/paper.Rmd` - Main paper
- `DATA 712 20260430 Roni Pitkowsky SCF.Rmd` - Analysis script
- `data/scf_filtered.rds` - Processed SCF data
- `references/references.bib` - Citations

### Reproduction

1. Load data: `source('scripts/SCF_filter_load.R')`
2. Run analysis: Open and knit `DATA 712 20260430 Roni Pitkowsky SCF.Rmd`
3. Generate paper: Knit `manuscript/paper.Rmd`

### Data Source

2022 Survey of Consumer Finances (SCF)
Federal Reserve Board of Governors
https://www.federalreserve.gov/econres/scfindex.htm


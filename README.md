# Stronger fertile island patterns enhance plant facilitation in drylands, regardless of ecosystem fertility

## Authors: Giachetti, V., Decunta, F.A., Druille, M., Aguiar, M.

This repository contains the code, data, and results for the meta-analyses. The analysis includes sensitivity analyses, meta-regressions, and multilevel meta-analytic models.

## Directory Structure

### Key Directories and Files

- **data/**: Contains raw, processed, and coordinate data used in the analysis.
  - `Giachetti_2025_raw.csv`: Raw data collected for the study.
    - Metadata: `Giachetti_2025_raw_metadata.md`
  - `Giachetti_2025_processed.csv`: Processed data ready for analysis.
    - Metadata: `Giachetti_2025_processed_metadata.md`
  - `Giachetti_2025_coordinates.csv`: Geographical coordinates of experiments.
    - Metadata: `Giachetti_2025_coordinates_metadata.md`

- **figures/**: Contains plots and visualizations generated during the analysis.
  - `Map.jpeg`: Map of study sites.
  - `Overall_plot.jpeg`: Overall effects size plot.
  - `Overall_plot_onlyField.jpeg`: Effect size plot using only field data.
  - `nutrients_plot.pdf`: Meta-regressions with nutrients.
  - `nutrients_plot.jpeg`: Meta-regressions with nutrients.
  - `nutrients_plot_onlyField.jpeg`: Meta-regressions but using only field data.
  - `Fig3_Overall_plot.pdf`: PDF version of the overall effect size plot.
  - `Fig4_meta_regressions.pdf`: Meta-regression results.
  - `Whittaker.jpeg`: Whittaker diagram for study classification.

- **R/**: Contains R scripts and R Markdown files for data processing and analysis.
  - `0_Data_processing.Rmd`: Prepares raw data for analysis.
  - `0b_Database_overview.Rmd`: Some descriptive statistics of the data.
  - `1_Mean_effects.Rmd`: Analyzes overall effects of nurse plants.
  - `2_Meta-regressions.Rmd`: Conducts meta-regressions.
  - `3_SensitivityAnalysis_lnRR.Rmd`: Sensitivity analysis using log response ratios.
  - `4_SensitivityAnalysis_MeanEffects_onlyField.Rmd`: Sensitivity analysis using only field experiments.
  - `5_SensitivityAnalysis_MetaRegressions_onlyField.Rmd`: Sensitivity analysis for meta-regressions using only field experiments.

## Analysis Overview

1. **Data Processing**: Raw data is cleaned, merged with geographical and environmental data, and prepared for analysis.
2. **Meta-Analysis**: Multilevel models are used to estimate overall effects. Includes bias test and sensitivity analysis.
3. **Meta-Regressions**: Relationships between nurse plant effects and soil nutrients are explored. Includes bias test and sensitivity analysis.
4. **Sensitivity Analyses**: Robustness of results is assessed by using log of response ratio and re-running the analyses only with field data.

## Metadata Files

Each dataset in the `data/` directory is accompanied by a metadata file that provides detailed descriptions of the columns, data collection methods, and usage notes:
- `Giachetti_2025_raw_metadata.md`: Metadata for the raw dataset.
- `Giachetti_2025_processed_metadata.md`: Metadata for the processed dataset.
- `Giachetti_2025_coordinates_metadata.md`: Metadata for the geographical coordinates dataset.

## Dependencies

The analysis requires the following R packages:
- `tidyverse`
- `metafor`
- `ape`
- `orchaRd`
- `patchwork`
- `rotl`
- `terra`
- `geodata`# MA_Giachetti
# MA_Giachetti_2025

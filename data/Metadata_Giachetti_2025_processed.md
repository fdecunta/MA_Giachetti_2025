# Metadata for `Giachetti_2025_processed.csv`

## Description

This file contains processed data for the meta-analysis. The dataset includes calculated effect sizes, relative interaction indices (RII), and additional environmental and experimental variables. It is derived from the raw data and includes geolocation and environmental context for each study.

## File Structure

The dataset is organized into the following columns:

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `id_paper`          | Unique identifier for each paper                                           |
| `id_site`           | Unique identifier for each study site within a paper                      |
| `title`             | Title of the study                                                        |
| `authors`           | Shortened list of authors                                                 |
| `authors_full`      | Full list of authors                                                      |
| `year`              | Year of publication                                                       |
| `nurse_species`     | Name of the nurse plant species                                           |
| `exp_type`          | Type of experiment (e.g., field, glasshouse, chamber)                     |
| `umbrella`          | Broad category of the variable (e.g., emergence, survival, abundance)     |
| `n_rii`             | Sample size for the relative interaction index (if available)             |
| `id_es`             | Unique identifier for each effect size                                    |
| `orig_RII`          | Original relative interaction index (RII)                                 |
| `orig_RIIV`         | Variance of the original RII                                              |
| `RII`               | Processed relative interaction index (RII)                                |
| `RIIV`              | Variance of the processed RII                                             |
| `nit.RII`           | RII for nitrogen levels                                                   |
| `nit.RIIV`          | Variance of nitrogen RII                                                  |
| `p.RII`             | RII for phosphorus levels                                                 |
| `p.RIIV`            | Variance of phosphorus RII                                                |
| `lat`               | Latitude of the study site (in decimal degrees)                           |
| `long`              | Longitude of the study site (in decimal degrees)                          |
| `soil_n`            | Soil nitrogen content                                                     |
| `soil_phosphorus`   | Soil phosphorus content                                                   |
| `aridity_index`     | Aridity index of the study site                                            |
| `tavg`              | Average temperature (°C) at the study site                                |
| `prec`              | Average precipitation (mm) at the study site                              |
| `n_island`          | Sample size under the nurse plant                                         |
| `n_bs`              | Sample size in the bare soil                                              |
| `n_island_fi`       | Sample size for fertility island measurements under the nurse plant       |
| `n_bs_fi`           | Sample size for fertility island measurements in the bare soil            |
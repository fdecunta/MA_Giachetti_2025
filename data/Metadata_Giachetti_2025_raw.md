# Metadata for `Giachetti_2025_raw.csv`

## Description

This file contains raw data collected for the meta-analysis. The dataset includes information on study sites, experimental conditions, and measured outcomes, such as plant emergence, survival, biomass, and soil nutrient levels.

## File Structure

The dataset is organized into the following columns:

| Column Name          | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `id_paper`           | Unique identifier for each paper                                           |
| `id_site`            | Unique identifier for each study site within a paper                      |
| `title`              | Title of the study                                                        |
| `authors`            | Shortened list of authors                                                 |
| `authors_full`       | Full list of authors                                                      |
| `year`               | Year of publication                                                       |
| `nurse_species`      | Name of the nurse plant species                                           |
| `exp_type`           | Type of experiment (e.g., field, glasshouse, chamber)                     |
| `variable`           | Variable measured (e.g., emergence, survival, biomass)                    |
| `umbrella`           | Broad category of the variable                                            |
| `unidad`             | Unit of measurement (e.g., %, g, number/m²)                               |
| `mean_island`        | Mean value of the variable under the nurse plant                          |
| `mean_bs`            | Mean value of the variable in the bare soil                               |
| `sd_island`          | Standard deviation of the variable under the nurse plant                 |
| `sd_bs`              | Standard deviation of the variable in the bare soil                      |
| `n_island`           | Sample size under the nurse plant                                         |
| `n_bs`               | Sample size in the bare soil                                              |
| `rii`                | Relative interaction index (if available)                                 |
| `sd_rii`             | Standard deviation of the relative interaction index                     |
| `n_rii`              | Sample size for the relative interaction index                           |
| `mean_island_nit`    | Mean nitrogen level under the nurse plant                                 |
| `mean_bs_nit`        | Mean nitrogen level in the bare soil                                      |
| `sd_island_nit`      | Standard deviation of nitrogen level under the nurse plant               |
| `sd_bs_nit`          | Standard deviation of nitrogen level in the bare soil                    |
| `mean_island_p`      | Mean phosphorus level under the nurse plant                              |
| `mean_bs_p`          | Mean phosphorus level in the bare soil                                   |
| `sd_island_p`        | Standard deviation of phosphorus level under the nurse plant             |
| `sd_bs_p`            | Standard deviation of phosphorus level in the bare soil                  |
| `n_island_fi`        | Sample size for fertility island measurements under the nurse plant      |
| `n_bs_fi`            | Sample size for fertility island measurements in the bare soil           |
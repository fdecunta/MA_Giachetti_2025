# Metadata for `Giachetti_2025_coordinates.csv`

## Description

This file contains geographical coordinates and metadata for studies included in the meta-analysis. Each row corresponds to a study site, providing the latitude and longitude of the location where the study was conducted, along with the study title and a unique identifier.

## File Structure

The dataset is organized into the following columns:

| Column Name | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `id_paper`  | Unique identifier for each paper                                           |
| `title`     | Title of the study                                                         |
| `lat`       | Latitude of the study site (in decimal degrees)                            |
| `long`      | Longitude of the study site (in decimal degrees)                           |

## Usage Notes

- The `id_paper` column can be used to link this dataset with other datasets (e.g., `Giachetti_2025_raw.csv`) for further analysis.
- Some studies may have multiple entries if they were conducted at multiple locations or sites.
- Missing or unavailable coordinates are not included in the dataset.
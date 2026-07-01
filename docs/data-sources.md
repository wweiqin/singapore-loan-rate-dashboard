# Data Sources

This document will record every dataset used in the project.

## Planned Data Requirements

### Interest-Rate Data

Required fields:

- Date
- Interest-rate type
- Interest rate
- Data frequency

### Bank-Lending Data

Required fields:

- Quarter or month
- Industry
- Lending amount
- Data frequency

## Source Requirements

Datasets should preferably come from:

- Monetary Authority of Singapore
- Singapore Department of Statistics
- Data.gov.sg
- Other official Singapore government sources

## Data-Handling Notes

- Original files will be stored in `data/raw/`.
- Cleaned files will be stored in `data/processed/`.
- Raw data should not be manually altered.
- All cleaning steps should be documented in SQL or Python.
- Dataset URLs and download dates will be added once the sources are selected.
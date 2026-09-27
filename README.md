# Peripheral Insecurity in Nigeria

## Examining the relationship between conflict exposure, socioeconomic deprivation and settlement characteristics

This repository contains the reproducibility materials for an exploratory quantitative study of recorded insecurity across Nigeria's 36 states and the Federal Capital Territory (FCT).

### Research questions

1. How is recorded insecurity geographically distributed across Nigerian states?
2. Is higher socioeconomic deprivation associated with greater recorded insecurity exposure?
3. Is settlement structure associated with differences in recorded insecurity?
4. To what extent do household-reported security-related shocks correspond with recorded insecurity?
5. What do the observed patterns imply for understanding security planning?

### Data and methods

The analysis integrates:

- 2025 Armed Conflict Location & Event Data (ACLED) recorded events and fatalities.
- Nigeria Multidimensional Poverty Index (2021/22) state-level poverty incidence and household-reported security-related shocks from the National Bureau of Statistics (NBS).
- WorldPop 2025 Degree of Urbanisation settlement data, using urban-cluster footprint as a geographical settlement-structure measure.
- 2022 state population projections used as denominators for standardized 2025 ACLED rates.

The primary unit of analysis is the 37 state/FCT units. The statistical analysis includes descriptive statistics, Pearson and Spearman correlations, multiple linear regression, regression diagnostics, and sensitivity analyses.

The study is observational and state-level. It does not make causal claims.

### Reproducibility

The main reproducibility notebook is in `notebooks/01_data_validation_cleaned.ipynb`. It is designed to run from the project's `notebooks/` directory and expects the project data directories described in the notebook.

Raw source datasets are **not redistributed in this repository**. Users should obtain source data directly from the relevant providers and comply with their access and use conditions.

### Source-data access

- ACLED: https://acleddata.com/
- National Bureau of Statistics Nigeria: https://microdata.nigerianstat.gov.ng/
- WorldPop: https://hub.worldpop.org/

### Repository status

This repository contains the public research and reproducibility materials. Restricted or non-redistributable source data, credentials, and private working files are excluded.

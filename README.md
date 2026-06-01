# GEFS Heavy Precipitation Verification

This repository is a developing project focused on using NOAA GEFS ensemble forecast data for heavy precipitation analysis and verification.

## Workflow

- Open GEFS precipitation forecast files from Amazon S3
- Read GRIB2 files using `xarray` and `cfgrib`
- Create an example precipitation forecast map over the United States
- Load multiple GEFS ensemble members
- Compute ensemble probability of heavy precipitation
- Compare GEFS forecasts with observed precipitation datasets (Brier score)
- Repeat Brier Score calculation across several forecast dates


## Repository Structure

```text
gefs-heavy-precip-verification/
├── README.md
├── notebooks/
│   └── 01_open_gefs_precipitation.ipynb
│   └── 02_probability_of_heavy_precipitation.ipynb
│   └── 03_brier_score_verification.ipynb
│   └── 04_multi_case_brier_score_workflow.ipynb
└── figures/
    └── 1_gefs_precip_example_24h.png
    └── 2_gefs_precip_ensemble_mean_24h.png
    └── 3_gefs_probability_precip_10mm_24h.png
    └── 4_gefs_probability_precip_25mm_24h.png
    └── 5_obs_heavy_precip_25mm.png
    └── 6_gefs_brier_score_heavy_precip_25mm_24h.png
    └── 7_multi_case_brier_score_25mm.png

## Note on AI-Assisted Work

AI tools were used to support code drafting, debugging, code understanding, and discussion of scientific methods. I reviewed, modified, and tested the code myself.

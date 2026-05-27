# GEFS Heavy Precipitation Verification

This repository is a developing project focused on using NOAA GEFS ensemble forecast data for heavy precipitation analysis and verification.

At the current stage, the repository contains the first workflow notebook for accessing and opening GEFS accumulated precipitation forecast files from the public NOAA Amazon S3 archive using Python in Google Colab.

## Current Status

Completed:

- Open GEFS precipitation forecast files from Amazon S3
- Read GRIB2 files using `xarray` and `cfgrib`
- Create an example precipitation forecast map over the United States
- Load multiple GEFS ensemble members
- Compute ensemble probability of heavy precipitation

Planned:

- Compare GEFS forecasts with observed precipitation datasets

## Repository Structure

```text
gefs-heavy-precip-verification/
├── README.md
├── notebooks/
│   └── 01_open_gefs_precipitation.ipynb
│   └── 02_probability_of_heavy_precipitation.ipynb
└── figures/
    └── gefs_precip_example_24h.png
    └── gefs_precip_ensemble_mean_24h.png
    └── gefs_probability_precip_10mm_24h.png
    └── gefs_probability_precip_25mm_24.png
```

## AI Assistance Disclosure
Parts of this project were developed with AI assistance for code organization, README drafting, and workflow refinement. All scientific choices, code execution, debugging, and final review were completed by the author.

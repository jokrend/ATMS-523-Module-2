# ATMS-523-Module-2 Project 2

This project analyzes daily total precipitation from around the Asheville, NC area
using ECMWF ERA5 Reanlysis data from Google Cloud.

## Dataset
- **ARCO ERA5** hourly at 0.25° resolution (Zarr) on GCS  
- Store: `gs://gcp-public-data-arco-era5/ar/full_37-1h-0p25deg-chunk-1.zarr-v3`
- Variable used: `total_precipitation` (precipitation, m) at surface level.

## Attribution
- ERA5 data © ECMWF, distributed via Google Cloud (ARCO).
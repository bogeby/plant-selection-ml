# Data

`sample_plants.csv` is a small sample from the supplied final CSV, intended for structure exploration and quick notebook checks. It is **not** the dataset used for the published notebook metrics.

The full provided CSV uncompresses to about **412 MB**, exceeding GitHub's normal 100 MB per-file limit. Do not push it as a regular Git object. Store it privately, via Git LFS if appropriate, or provide a permitted external download.

The original raw records are attributed in the data-collection notebook to [Dryad DOI: 10.5061/dryad.2jm63xsrf](https://doi.org/10.5061/dryad.2jm63xsrf). Other features were added using Open-Meteo, SoilGrids and NC State Plant Toolbox. The *final enriched CSV is not identical to the raw Dryad download*.

To run on the full data, place `my_plants_data.csv` locally and set `PLANTS_DATA_PATH` to that file before launching Jupyter. See the root README.

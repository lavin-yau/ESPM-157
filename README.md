# Climate Module

[![Reproducibility Check](https://github.com/lavin-yau/ESPM-157/actions/workflows/main.yml/badge.svg)](https://github.com/lavin-yau/ESPM-157/actions/workflows/main.yml)


## Team Members

Lavin Yau. I worked on this assignment myself due to joining the class late (week 4). I followed instructions present in this repository and guidance from a GSI during class. I used AI to help draft code for analysis and wrote explanations and reasonins myself.

## Running the Jupyter Notebook
Use the course's Linux Jupyter environment with Python 3.11+.

Install requirements with this command:
python -m pip install -r requirements.txt

Open climate.ipynb in dataHub, select the installed Python environment as the kernel, and run the notebook from top to bottom.

The notebook downloads the climate datasets directly from their public sources. Because the benchmarking code uses Linux resource measurements, run the notebook in the course Linux environment or another Linux environment.

## Files

| File | Purpose |
|---|---|
| `climate.ipynb` | Climate data analysis, figures, verification blocks, and reflection |
| `requirements.txt` | Python packages needed to run the notebook and course checks |
| `rubric.md` | Assignment grading rubric |
| `.github/workflows/main.yml` | Automated notebook reproducibility check |

The notebook downloads the climate datasets directly from their public sources, so no local `data/` directory is required.

## Files

- NOAA Mauna Loa CO2 record — <https://gml.noaa.gov/webdata/ccgg/trends/co2/co2_mm_mlo.txt>
- NSIDC Arctic sea ice extent (G02135) — <https://nsidc.org/data/G02135>
- EXIOBASE 3, cloud-optimized Parquet — <https://source.coop/youssef-harby/exiobase-3>
- Our World in Data CO2 — <https://github.com/owid/co2-data>
- Vostok ice core — <https://doi.org/10.3334/CDIAC/ATG.009>

[🌐 Course Website](https://espm-157.carlboettiger.info/)

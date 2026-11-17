# NHANES food security and anemia: reproducibility materials

Analysis scripts and aggregate reference outputs for **Household food security and anemia by cancer history in adults: a cross-sectional study** (NHANES 2003–March 2020).

## Contents and usage

1. Download [06_Reproducibility_code.zip](06_Reproducibility_code.zip) and verify its SHA-256 checksum against `SHA256SUMS.txt`.
2. Extract the archive (`06_Code_and_data/`, 245 files, including 44 R and Python analysis and plotting scripts, configuration manifests, aggregate CSV/JSON outputs, and per-file checksums in `06_Code_and_data/SHA256SUMS.json`).
3. Follow `06_Code_and_data/README.md` for software dependencies, public NHANES data download, statistical execution order, and figure generation.

No raw or participant-level records are included in this repository; public-use source datasets are available directly from [CDC/NHANES](https://www.cdc.gov/nchs/nhanes/).

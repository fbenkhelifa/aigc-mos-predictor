# Data layout

This repository uses a structured data workspace for AIGC quality research.

## Target dataset

- **AGIQA-3K** (AI-generated image quality assessment)

## Local structure

- `data/raw/agiqa3k/` for original dataset assets and metadata
- `data/processed/` for cleaned splits and derived features

## Notes

Because AGIQA-3K distribution terms may vary by source mirror, keep the repository compliant by:

1. Storing only metadata and preprocessing scripts in Git.
2. Downloading raw assets locally from official/authorized sources.
3. Avoiding direct redistribution of restricted files.

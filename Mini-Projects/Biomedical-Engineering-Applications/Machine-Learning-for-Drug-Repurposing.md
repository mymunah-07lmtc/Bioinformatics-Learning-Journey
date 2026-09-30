# Biomedical Engineering Applications

## Machine Learning for Drug Repurposing
- **BME problem**: Finding new therapeutic uses for existing FDA‑approved drugs is faster and cheaper than de novo development.
- **Bioinformatics foundation**:
  - **Databases**: Use **NCBI GEO** (gene expression data), **UniProt** (protein targets), and **DrugBank** (drug‑target interactions).
  - **Approach**:
    1. Download gene expression signatures from drug‑treated cells (GEO).
    2. Compare signatures of a disease (e.g., Alzheimer’s) with drug‑induced signatures – drugs that reverse the disease signature are candidates.
    3. **Machine learning** (e.g., random forest, neural networks) predicts novel drug‑target interactions using features from PDB structures (pocket shape, electrostatics).
- **BME product**:
  - Computational platform that clinicians can use to recommend off‑label drugs for rare cancers – an example of **precision medicine**.
- **My learning path**: I plan to learn Python libraries (scikit‑learn, pandas) to replicate a small‑scale repurposing pipeline using public data.

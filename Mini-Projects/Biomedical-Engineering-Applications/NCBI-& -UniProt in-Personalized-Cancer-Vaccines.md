# Biomedical Engineering Applications

## Month 3: NCBI & UniProt in Personalized Cancer Vaccines
- **BME problem**: Solid tumors like melanoma can be treated with patient‑specific vaccines.
- **Workflow**:
  1. **NCBI**: Download tumor exome sequencing data and matched normal DNA.
  2. Identify somatic mutations (non‑synonymous) that create **neoantigens**.
  3. **UniProt**: Check if the mutated peptide is likely to be presented by MHC molecules (look for known motifs).
  4. **BLAST**: Ensure the neoantigen is not present in the normal human proteome (avoid autoimmunity).
- **BME implementation**:
  - **mRNA vaccine** (like Moderna’s personal cancer vaccine) – encode up to 20 neoantigens per patient.
  - **Manufacturing** within 6‑8 weeks.
- **Relevance**: Combines genomics, immunology, and nano‑delivery systems – a true BME challenge.

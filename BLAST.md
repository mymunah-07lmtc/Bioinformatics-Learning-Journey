# BLAST (Basic Local Alignment Search Tool)

## What is BLAST?
BLAST is a tool that finds regions of similarity between biological sequences (nucleotide or protein). It compares a query sequence to a database of known sequences and returns results ranked by statistical significance.

## Why Researchers Use It
- Identify an unknown DNA or protein sequence.  
- Find homologous genes across different species.  
- Discover conserved domains and motifs.  
- Predict function of a new gene based on similar known genes.

## How Sequence Comparison Works
BLAST breaks the query sequence into small “words” and searches for matches in the database. Then it extends those matches to form alignments. It uses statistical scores to determine if a match is likely due to common ancestry or just chance.

## Example Use Case
Imagine a researcher sequences DNA from a soil bacterium and gets a 500‑base pair fragment. They don’t know what gene it is. By running BLAST against the NCBI nucleotide database, the tool returns a hit with 98% identity to a known gene for an antibiotic‑resistance enzyme. This quickly suggests the bacterium might be resistant to that antibiotic, guiding further lab experiments.

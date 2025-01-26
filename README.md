# Comprehensive Genomic Analysis of SARS-CoV-2 (Wuhan-Hu-1 Isolate)

This repository contains the code, data, and analysis for a detailed genomic study of the Severe Acute Respiratory Syndrome Coronavirus 2 (SARS-CoV-2) isolate Wuhan-Hu-1. The project leverages various computational methods to extract meaningful insights from the reference genome ([NC_045512.2](https://www.ncbi.nlm.nih.gov/nuccore/NC_045512.2)).

## **Overview**
The goal of this analysis is to explore key genomic features of SARS-CoV-2, including nucleotide composition, sequence diversity, and structural variability. These insights provide a deeper understanding of the virus's genomic properties and contribute to research in viral replication, mutation, and evolution.

## **Key Features**
This repository includes the following analyses:
1. **GC Skew Analysis**:
   - Examines the asymmetry in guanine (G) and cytosine (C) distribution across the genome to identify potential replication origins, strand biases, or functional regions.

2. **GC Content**:
   - Measures the proportion of guanine and cytosine in sequence windows, providing insights into sequence stability and structural features.

3. **k-mer Diversity**:
   - Calculates the diversity of k-mers (subsequences of length k) to evaluate sequence complexity.

4. **Nucleotide Distribution**:
   - Analyzes the relative frequencies of nucleotides (A, T, G, C) to characterize composition patterns.

5. **Entropy**:
   - Computes Shannon entropy to quantify randomness and variability in nucleotide distributions.

6. **CpG Metrics**:
   - Includes CpG density, observed vs. expected CpG counts, and CpG ratios to explore methylation hotspots and their biological implications.

7. **Correlation Analysis**:
   - Examines relationships among computed metrics to uncover interdependencies and meaningful patterns.

8. **Principal Component Analysis (PCA)**:
   - Performs dimensionality reduction to visualize dominant trends and patterns across computed metrics.

## **Dataset**
The genomic sequence analyzed in this project was sourced from the NCBI database ([NC_045512.2](https://www.ncbi.nlm.nih.gov/nuccore/NC_045512.2)), representing the SARS-CoV-2 isolate Wuhan-Hu-1 complete genome.

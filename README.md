# Bakhouri 2023 Analysis

My final project for CMM 523 "Crash Course in Single-cell Genomics Analysis for Biologists" at the University of Arizona (taken in Fall 2024) was to run my own analysis on a publicly available single-cell RNA sequencing dataset. 

I'm deeply interested in T cell immunology and clinical research. I chose Bakhouri et al, "Single-cell RNA sequencing reveals distinct T cell populations in immune-related adverse events of checkpoint inhibitors" (published in January 2023 in Cell Reports Medicine). The authors isolated T cells from patients before starting them on anti-PD1 checkpoint inhibitors (to develop a baseline, or "treatment naive" phenotype), and after patients developed immune-related adverse events (irAEs) such as arthritis, colitis or neurotoxicity (considered a "post-treatment" phenotype).

I used Seurat, SingleR, edgeR and Monocle3 (all through RStudio) to discover which immune cells and which genes were expressed differently between patients who developed irAEs and those who did not. As of November 1 2024, I have completed a rough initial analysis, and have pushed my work onto this GitHub repository. I have self-identified areas of improvement, and intend to continue developing my analysis over the next few weeks.

# Computational Molecular Oncology

Research software and reproducible analyses developed and maintained
by **[Nicholas Moir](https://orcid.org/0000-0001-6957-932X)**.

My research focuses on molecular heterogeneity in breast cancer and its
implications for the analysis and interpretation of transcriptomic data.
I investigate how molecular subtype, cohort composition and technical
variation affect dataset integration and biological inference.

I develop software and reproducible workflows for evaluating batch correction, 
comparing analytical configurations and tracking their effects
on biologically meaningful variation.

This page brings together my reusable software and the analysis
code supporting my publications. All projects are developed and maintained
by me.

## Software

### [BatchVaria](https://github.com/cmpmolonc/BatchVaria)

An R package for evaluating batch correction through variance profiling,
comparison of correction configurations and provenance tracking.
BatchVaria operates directly on SummarizedExperiment objects and retains
the information needed to interpret changes in variance attribution.

**Start here to install and use the package.**

## Code accompanying publications

### [The significance of molecular heterogeneity in breast cancer batch correction and dataset integration](https://github.com/cmpmolonc/BC)

Analysis code to support the 2025 Breast Cancer Research publication (https://link.springer.com/article/10.1186/s13058-025-02159-7).


### [BatchVaria Application Note](https://github.com/cmpmolonc/BatchVaria-AppNote)

Analysis scripts for reproducing analysis results and figure in the
BatchVaria Application Note preprint (https://www.biorxiv.org/content/10.64898/2026.05.07.721996v2). Utility of BatchVaria is demonstrated using TCGA breast cancer
RNA-seq data.


## Reproducibility and citation

Individual repositories provide their own documentation, software
requirements, licensing information and associated publication links.
Please consult each repository's README for instructions and citation
details.

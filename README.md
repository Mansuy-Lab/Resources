# omics_pipelines

This repository contains reproducible bioinformatic workflows for processing omics datasets across multiple data modalities.

Each modality is organised in a dedicated subfolder and includes the components required to run the corresponding processing workflow, including:

Snakemake workflows (Snakefile)
Workflow-specific configuration files
Conda environment definitions for software dependencies
Custom R and other helper scripts required by individual Snakemake rules

The workflows are intended to provide a consistent and reproducible framework for processing omics datasets and can be adapted to different datasets by modifying the corresponding configuration files.

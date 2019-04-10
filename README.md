# Constanza pipelines

This repo contains three
[slurm-pipeline](https://github.com/acorg/slurm-pipeline) specification
files (`specification.json`) and associated scripts for processing the Constanza's data from April 2019.

The three pipelines run DIAMOND against the refseq database (`refseq-diamond`), bwa against the hbv database (`hbv-bwa`), and collects the output (`hbv-collect`).

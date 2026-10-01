# Lab: Visualize Plastid Genome Structure

**Name:** Isabella Tuble
**Course/Section:** Cell and Molecular Biology, A
**Plant:** *Hibiscus syriacus* L. (Malvaceae)
**NCBI accession:** NC_026909.1 (RefSeq)
**Plastid genome length:** 161,019 bp
**Genome file source:** NCBI Nucleotide, downloaded as GenBank (full) from https://www.ncbi.nlm.nih.gov/nuccore/NC_026909.1
**Software:** OGDRAW (OrganellarGenomeDRAW), https://chlorobox.mpimp-golm.mpg.de/OGDraw.html
**Date:** 1 October 2026

## OGDRAW settings
Standard mode; uploaded `Hibiscus_syriacus_NC_026909.1.gb`; circular map; plastid sequence source; inverted repeats on Auto; GC content graph on; transcription direction shown; full legend; intron-containing genes labelled with * (no asterisks appeared); PNG output at superfine resolution; all gene categories selected except "introns"; "Tidy up annotation" off.

## Plastid genome map
![Plastid genome map](figures/Hibiscus_syriacus_plastid_map.png)

## Main structural features
The plastome has the typical quadripartite structure: a large single-copy region (LSC) across the top, a small single-copy region (SSC) at the bottom, and two inverted repeats (IR) between them. The LSC carries photosystem, ATP synthase and RNA polymerase genes, and the SSC carries the *ndh* genes. Genes are encoded on both strands. The GC graph varies along the genome. In this RefSeq record no rRNA genes are annotated, most IR genes appear only once, and *rps12* is trans-spliced, so the map is less complete than a fully annotated plastome.

## Files
- `data/Hibiscus_syriacus_NC_026909.1.gb`: original GenBank file (unchanged)
- `figures/Hibiscus_syriacus_plastid_map.png`: OGDRAW map
- `answers/Lab_plastid_genome_answers.md`: answers to the lab questions

## Reference
Greiner S, Lehwark P, Bock R. 2019. OrganellarGenomeDRAW (OGDRAW) version 1.3.1: expanded toolkit for the graphical visualization of organellar genomes. Nucleic Acids Research 47: W59-W64.

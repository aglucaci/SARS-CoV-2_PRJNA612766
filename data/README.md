# Manually downloaded input data

## GISAID sequences
Due to [GISAID data sharing terms](https://www.gisaid.org/help/faq/), the actual FASTA sequences are not tracked in this repo.
However, the subdirectories with GISAID sequences contain `*.tsv.xz` files that list the accessions, as well as acknowledging the originating and submitting labs.
These are tracked.

- [comparator_genomes_gisaid](comparator_genomes_gisaid) contains bat virus comparator genomes as downloaded from GISAID on May-16-2021.

## Mutations extracted from GISAID data by Richard Neher

The [gisaid_mutations](gisaid_mutations) subdirectory contains data on mutations relative to Wuhan-Hu-1 for all full-length sequences in GISAID, compiled and provided to me by Richard Neher on May-17-2021 (not sure when he scraped GISAID for it).
I'm not sure if I'm allowed to track the mutations file on GitHub, so for now I just track the metadata file with information on the originating and submitting labs, accessions, etc.
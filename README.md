# mtdna-kal
Probabilistic assignment of mtDNA sequencing data to the tips of an mtDNA phylogeny, using kallisto, treetime, and simulated DNA.

mt-kal structure

2-3 snakemake pipelines? separate files, or not?

0: fasta / tree
 - MSA w/ no Ns? what about gaps?
 - internal names on tree
 - "fixed" names, whatever that means
 - how much can be done automatically?

1: setup / simulations / make threshold table

2: process a dataset [w/ kallisto only? and add thresholds, I think]

3: plot examples? make basic plots? make an R file that can be modified?  

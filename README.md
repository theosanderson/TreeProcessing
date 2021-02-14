# TreeProcessing

We take a kind of inane hacked-together approach in which we take an alignment to ref as a multi-fasta, split it into a series of files where each column represents a nucleotide position, call `pastml` on these in parallel to infer ancestral states using maximum parsimony with DELTRAN.

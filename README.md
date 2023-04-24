# biotree_tools
Collection of bioinformatics tools related to alignments and phylogenetic trees

## Installation

Temporary way:
conda create -y -n btt
conda activate btt
conda install -y -c etetoolkit ete3==3.1.1 ete_toolchain
conda install -y -c mmariotti -c conda-forge -c etetoolkit easyterm gawk blast mafft trimal brewer2mpl ncbi_db
conda install -y -c mmariotti biotree_tools

## Tools
- **alignment_tools**  utility to manipulate (reformat, subset, trim...) multiple sequence alignments
- **tree_tools**       utility to manipulate (rename, prune, set output...) trees in newick format
- **phylo_context**    given protein sequences, build and draw a tree to identify phylogenetic (sub)families
- **show_tree**        flexible tool to visualize an input protein tree in newick format

Run any tool with option -h to display its usage.
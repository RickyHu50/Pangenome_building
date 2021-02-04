# Pangenome_building pipeline

This handy pipeline is a reference-based pangenome building pipeline, which developed based on the publication of "The pangenome of an agronomically important crop plant Brassica oleracea". It will be expected to be used to construct the pangenome and explore the genetic variations in the plant/crop species.

Usage: runPanGenome [group] [trim] [map] [extract] [assemble]\n

group      group sequence files based on the phylogenetic tree.
trim       trim adapters and remove reads with Ns for the input sequences.
map        map reads back to the reference.
extract    extract unmapped reads.
assemble   assemble those unmapped reads.

Please select one of the given options and continue

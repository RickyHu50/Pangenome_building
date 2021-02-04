# Pangenome building pipeline

This handy pipeline is a reference-based pangenome building pipeline, which developed based on the publication of "The pangenome of an agronomically important crop plant Brassica oleracea". It will be expected to be used to construct the pangenome and explore the genetic variations in the plant/crop species.

There are five main steps in these pipeline:

```
Usage: runPanGenome [group] [trim] [map] [extract] [assemble]

group      group sequence files based on the phylogenetic tree.\n
trim       trim adapters and remove reads with Ns for the input sequences.\n
map        map reads back to the reference.\n
extract    extract unmapped reads.\n
assemble   assemble those unmapped reads.\n

Please select one of the given options and continue
```

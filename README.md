# HLA Modeller

This script builds three-dimensional models of the most [common and well-documented](https://www.ihiw18.org/component-immunogenetics/download-common-and-well-documented-alleles-3-0) HLA alleles. Sequences are taken from the latest [IPD-IMGT/HLA](https://www.ebi.ac.uk/ipd/imgt/hla) release and folded with [Meta's ESMFold](https://esmatlas.com) via the ESM Atlas API.

## Instructions

Pre-built structures are in the repository [`output`](https://github.com/mariomarroquim/hla-modeller/tree/main/output) folder. To regenerate models after a new IPD-IMGT/HLA release, run `ruby run.rb`.

To view a model, download its PDB file from `output` and open it in a molecular viewer such as [Mol*](https://molstar.org/viewer).

## Support

You can contact me at: mariomarroquim@gmail.com.

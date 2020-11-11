Exhaustive benchmarking of de novo assembly methods for eukaryotic genomes
====

Paper coming!


Packages benchmarked
--------------------

This benchmarking study includes 20 different assembly packages, run in a total of 30 different ways, as well as 8 different polishers across data types. Below is a list of all assembly packages used. For more details on the settings used for each assembler, these details are available in the various snakemake rule files in the Code folder. 

### Assemblers

#### Oxford Nanopore

| Assembly Package                                   | Version |
| -------------------------------------------------- | ------- | 
| [Canu](https://github.com/marbl/canu)              | v 1.9   | 
| [Flye](https://github.com/fenderglass/flye)        | v 2.8   |
| [Miniasm](https://github.com/lh3/miniasm)          | v 0.3-r179   |
| [NECAT](https://github.com/xiaochuanle/NECAT)      | v 0.0.1_update20200803     |
| [Raven](https://github.com/lbcb-sci/raven)         | v 0.0.5     |
| [Shasta](https://github.com/chanzuckerberg/shasta) | v 0.3.0     |
| [Wtdbg2](https://github.com/ruanjue/wtdbg2)        | v 2.5     |

#### Pacbio (CLR)

| Assembly Package                                       | Version | 
| ------------------------------------------------------ | ------- |
| [Canu](https://github.com/marbl/canu)                  | v 1.9   |
| [FALCON](https://github.com/PacificBiosciences/FALCON) | v 0.3.0   | 
| [Flye](https://github.com/fenderglass/flye)            | v 2.8   |
| [MECAT2](https://github.com/xiaochuanle/MECAT2)        | v 20190314     |
| [Miniasm](https://github.com/lh3/miniasm)              | v 0.3-r179   |
| [Raven](https://github.com/lbcb-sci/raven)             | v 0.0.5     |
| [Wtdbg2](https://github.com/ruanjue/wtdbg2)            | v 2.5     |

#### Illumina Paired-End

| Assembly Package                                                               | Version |
| ------------------------------------------------------------------------------ | ------- |
| [ABySS](https://github.com/bcgsc/abyss)                                        | v 2.1.0   |
| [MaSuRCA](https://github.com/alekseyzimin/masurca)                             | v 3.4.1   |
| [Meraculous](https://jgi.doe.gov/data-and-tools/meraculous/)                   | v 2.2.5.1  |
| [Platanus](http://platanus.bio.titech.ac.jp/platanus-assembler/platanus-1-2-4) | v 1.2.4    | 
| [Ray](https://github.com/sebhtml/ray)                                          | v 2.3.1     |
| [SOAPdenovo2](https://github.com/aquaskyline/SOAPdenovo2)                      | v r240     |
| [SPAdes](https://github.com/ablab/spades)                                      | v 3.12.0     |
| [SparseAssembler](https://github.com/yechengxi/SparseAssembler)                | v 20160920     |
| [w2rap](https://github.com/bioinfologics/w2rap-contigger)                      | v 20180828     |

#### Hybrid

| Assembly Package                                                               | Version |
| ------------------------------------------------------------------------------ | ------- |
| [DBG2OLC](https://github.com/yechengxi/DBG2OLC)                                        | v 20160920   |
| [HASLR](https://github.com/vpc-ccg/haslr)                             | v 0.8a1   |
| [MaSuRCA](https://github.com/alekseyzimin/masurca)                   | v 3.4.1  |
| [SPAdes](https://github.com/ablab/spades) | v 3.12.0    | 

### Polishers

#### Illumina Paired-End

| Polishing Package                                   | Version |
| -------------------------------------------------- | ------- | 
| [GATK](https://gatk.broadinstitute.org/hc/en-us)            | v 4.1.3.0  | 
| [HyPo](https://github.com/kensung-lab/hypo)        | v 1.0.3  |
| [NextPolish](https://github.com/nextomics/nextpolish)         | v 1.3.0  |
| [ntEdit](https://github.com/bcgsc/ntedit)      | v 1.3.2     |
| [Pilon](https://github.com/broadinstitute/pilon/)         | v 1.23     |
| [POLCA](https://github.com/alekseyzimin/masurca) | v 3.4.1     |
| [Racon](https://github.com/lbcb-sci/racon)      | v 1.4.13     |

#### Oxford Nanopore
| Polishing Package                                   | Version |
| -------------------------------------------------- | ------- | 
| [Medaka](https://github.com/nanoporetech/medaka)            | v 4.1.3.0  | 
| [NextPolish](https://github.com/nextomics/nextpolish)         | v 1.3.0  |
| [Racon](https://github.com/lbcb-sci/racon)      | v 1.4.13     |

#### PacBio (CLR)
| Polishing Package                                   | Version |
| -------------------------------------------------- | ------- | 
| [NextPolish](https://github.com/nextomics/nextpolish)         | v 1.3.0  |
| [Racon](https://github.com/lbcb-sci/racon)      | v 1.4.13     |

#### Hybrid 
| Polishing Package                                   | Version |
| -------------------------------------------------- | ------- | 
| [HyPo](https://github.com/kensung-lab/hypo)        | v 1.0.3  |



Need Help?
----------

If you want to get in contact about something one-on-one, please contact Dean at dean.c.southwood@gmail.com. 
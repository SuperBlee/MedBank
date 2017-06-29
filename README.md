MedBank
====

Yichao Zhou (joey1993@gmail.com)

Zeyu Li (zyli@cs.ucla.edu)

Yunsheng Bai (yba@cs.ucla.edu)


### Introduction
__MedBank__ is a medical related knowledge base used from *Entity Typing*. It is generated from a series from public accessible databases in different sub medical domains. This repo contains pre-processing code scripts for each knowledge source.

### What's included MedBank?

- Bioportal hierarchy ontology. [BioPortal](http://bioportal.bioontology.org/ontologies/MESH?p=classes&conceptid=root)
- DrugBank. [Page](https://www.drugbank.ca)
- _Please add other sources in this format_ `<source name>. [Page](<link>)`

### What's in this repo?
- `src/` source code from processing
- `example/` an example of the target knowledge base
- _<Add something if needed_

### How to run?
Please see `src/run.sh` to download, process, and generate MedBank from sources listed above.



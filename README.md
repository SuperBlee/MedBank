MedBank
====

Yichao Zhou (yz@cs.ucla.edu)

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
- _Add something if needed_

### How to run?
Please see `src/run.sh` to download, process, and generate MedBank from sources listed above.

### Format

- `medbank-id-name.map`
Records the entity `id` and entity `name` in a format of `id    <name>`

```
0    <aspirin>
1    <blood>
2    <carboxylic acid>
...
```

- `medbank-id-type.map`
Records the entity `id` and entity `type` in a format of `id    <type>`

```
100    <drug>
101    <body fluid>
102    <chemical>
...
```

- `medbank-facts.txt`
Records the facts mentioned in MedBank in a format of `id_1    <fact>    id_2`
```
77    <symptom_of>    23
...
```

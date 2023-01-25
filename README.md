# INSEE-Alignment
Aligning INSEE SKOS concepts with relevant datasets.

# Structure of the repository

```
project
│   README.md
│      
│
└───configs
│   └───unix
│   │   │   limesconfig-xxx.xml
│   │   │   limesconfig-yyy.xml
│   │   │   ...
│   │
│   └───windows
│       │   limesconfig-xxx.xml
│       │   limesconfig-xxx.xml
│       │   ...
│   
└───dataset
│      └───source
│         │  concepts-local.ttl
│        
│   
└───alignments
│       │   accepted-xxx.nt
│       │   ...
└───candidates
│       │   reviewme-xxx.nt
│       │   ...
│
└───void
│       │   void-insee.ttl
│
└───query
│       │   metadataConstruct_closeMatch.rq
│       │   metadataConstruct_exactMatch.rq
│
│


```

# How to use LIMES
## Install Instructions
Please, follow the instructions available in the Website at https://dice-group.github.io/LIMES/#/getting_started/installation

## On Windows
```
java -jar limes-core-1.7.9-SNAPSHOT.jar myconfigFiles.xml > logFile.txt

```

## On Unix/Mac

```
java -jar limes-core-1.7.9-SNAPSHOT.jar myconfigFiles.xml 

```

# Target Datasets
The datasets used for the alignments are availabe in Zenodo. See the reference below:

``` Atemezing Auguste Ghislain, & Daneau Caroline. (2023). SKOS Datasets for Aligning INSEE Concepts [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7568355
```

# License
Creative Commons Attribution 4.0 International (CC-BY 4.0)

# Data Management Plan for computational research

Author: [Dr. Ravindra Shinde](https://www.ravindrashinde.com)

License: [MIT License](https://opensource.org/licenses/MIT)

This repository contains a template for a Data Management Plan (DMP) for computational research. The DMP is a document that outlines how data will be managed during a research project and after it is completed. It is a living document that should be updated as the project progresses and as new data management needs arise.

This DMP follows the FAIR principles for data management: data should be Findable, Accessible, Interoperable, and Reusable. The DMP includes information about the data that will be generated during the project, how it will be organized, stored, and backed up, and how it will be shared with others.


## Organization of the data

This overview describes how data will be organized during the project. Data will be organized into directories based on the type of data and the stage of the project. Each directory will contain a README file that describes the contents of the directory and how the data is organized.

``` yaml
/home/user/
.
├── audios
│   ├── dataA
│   │   ├── annotations
│   │   ├── features
│   │   ├── processed
│   │   └── raw
│   └── README.md
├── authoring
│   ├── book-chapters
│   │   └── README.md
│   ├── books
│   │   └── README.md
│   ├── dissertation
│   │   ├── final_dissertation.pdf
│   │   ├── README.md
│   │   ├── references
│   │   └── source
│   ├── manuscripts
│   │   ├── README.md
│   │   ├── references
│   │   ├── title-A
│   │   ├── title-B
│   │   └── title-C
│   ├── papers
│   │   ├── 001-YYYY-Journal-Title
│   │   ├── 002-YYYY-Journal-Title
│   │   ├── 003-YYYY-Journal-Title
│   │   └── README.md
│   ├── presentations
│   │   └── README.md
│   ├── proposals
│   │   └── README.md
│   ├── README.md
│   ├── reports
│   │   └── README.md
│   ├── teaching
│   │   └── README.md
│   ├── thesis
│   │   ├── final_thesis.pdf
│   │   ├── README.md
│   │   ├── references
│   │   └── source
│   └── tutorials
│       ├── blogs
│       ├── HandsOnVASP
│       ├── QuantumEspresso
│       └── README.md
├── calculations
│   ├── collaborations
│   │   ├── Amsterdam
│   │   │   ├── 000000-silicon -> ../../materials/000000-silicon/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   ├── Berkeley
│   │   │   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   ├── Oxford
│   │   │   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   └── README.md
│   ├── grants
│   │   ├── Horizon-Europe
│   │   │   ├── 000000-silicon -> ../../materials/000000-silicon/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   ├── Marie-Curie
│   │   │   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   ├── NWO
│   │   │   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   │   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   │   └── README.md
│   ├── materials
│   │   ├── 000000-silicon
│   │   │   ├── 00-relaxation
│   │   │   │   └── README.md
│   │   │   ├── 01-DFT
│   │   │   │   └── README.md
│   │   │   ├── 02-HSE
│   │   │   │   └── README.md
│   │   │   ├── 03-post-DFT
│   │   │   │   └── README.md
│   │   │   ├── common
│   │   │   │   └── README.md
│   │   │   └── README.md
│   │   ├── 000001-CdGeSb2
│   │   │   ├── 00-relaxation
│   │   │   │   └── README.md
│   │   │   ├── 01-DFT
│   │   │   │   └── README.md
│   │   │   ├── 02-HSE
│   │   │   │   └── README.md
│   │   │   ├── 03-post-DFT
│   │   │   │   └── README.md
│   │   │   ├── common
│   │   │   │   └── README.md
│   │   │   └── README.md
│   │   └── README.md
│   ├── molecules
│   │   ├── 000000-caffeine
│   │   │   ├── 00-HF
│   │   │   │   └── README.md
│   │   │   ├── 01-optimization
│   │   │   │   └── README.md
│   │   │   ├── 02-VMC
│   │   │   │   └── README.md
│   │   │   ├── 03-DMC
│   │   │   │   └── README.md
│   │   │   ├── common
│   │   │   │   └── README.md
│   │   │   └── README.md
│   │   ├── 000001-C13H18O2
│   │   │   ├── 00-HF
│   │   │   │   └── README.md
│   │   │   ├── 01-optimization
│   │   │   │   └── README.md
│   │   │   ├── 02-VMC
│   │   │   │   └── README.md
│   │   │   ├── 03-DMC
│   │   │   │   └── README.md
│   │   │   ├── common
│   │   │   │   └── README.md
│   │   │   └── README.md
│   │   └── README.md
│   └── README.md
├── codes
│   ├── devel
│   │   ├── champ
│   │   │   ├── 2.3.0
│   │   │   └── git
│   │   ├── quantum-espresso
│   │   │   ├── 7.3.1
│   │   │   └── git
│   │   └── README.md
│   ├── libraries
│   │   ├── hdf5
│   │   │   └── v1.14.2
│   │   ├── qmckl
│   │   │   └── v1.0.0
│   │   ├── README.md
│   │   └── trexio
│   │       └── v2.5.0
│   ├── packages
│   │   ├── berkeleyGW
│   │   ├── quantum-espresso
│   │   │   ├── 7.3.1
│   │   │   └── git
│   │   ├── README.md
│   │   └── vasp
│   │       └── 6.4.0
│   ├── README.md
│   ├── scripts
│   │   ├── python
│   │   │   ├── analysis
│   │   │   └── visualization
│   │   ├── README.md
│   │   └── shell
│   │       ├── compilation
│   │       └── slurm
│   └── tools
│       ├── cmake
│       ├── ninja
│       └── README.md
├── containers
│   ├── qmckl-intel-latest
│   ├── README.md
│   └── trexio-gnu-latest
├── datasets
│   ├── 4TU
│   │   ├── dataset-4tu-paper-001
│   │   │   └── README.md
│   │   └── dataset-4tu-paper-002
│   │       └── README.md
│   ├── materials-cloud
│   │   └── dataset-materials-cloud-paper-005
│   │       └── README.md
│   ├── README.md
│   └── zenodo
│       ├── dataset-zenodo-paper-003
│       │   └── README.md
│       └── dataset-zenodo-paper-004
│           └── README.md
├── editing
│   ├── book-chapters
│   │   └── README.md
│   ├── books
│   │   └── README.md
│   ├── journals
│   │   ├── 001-YYYY-Journal-Title
│   │   ├── 002-YYYY-Journal-Title
│   │   └── README.md
│   └── README.md
├── environments
│   └── README.md
├── graphics
├── README.md
├── reviewing
│   ├── book-chapters
│   │   └── README.md
│   ├── books
│   │   └── README.md
│   ├── dissertation
│   │   ├── final_dissertation.pdf
│   │   ├── README.md
│   │   ├── references
│   │   └── source
│   ├── grants
│   │   └── README.md
│   ├── papers
│   │   ├── 001-YYYY-Journal-Title
│   │   ├── 002-YYYY-Journal-Title
│   │   ├── 003-YYYY-Journal-Title
│   │   └── README.md
│   ├── README.md
│   ├── reports
│   │   └── README.md
│   └── thesis
│       ├── final_thesis.pdf
│       ├── README.md
│       ├── references
│       └── source
└── Videos
    └── README.md
```



## Installation

### with git

The skeleton structure can be directly used from [GitHub] by cloning the
repository into the home folder which might be useful if you
want to use the very latest version:

```
git clone https://github.com/neelravi/data-management.git
```

You may want to delete the `.git` and `documentation` folders if you are not planning to contribute to the project.


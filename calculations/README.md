# calculations

This directory contains a typical folder structure for physics/chemistry calculations.


## Organization

``` yaml
calculations/
├── collaborations
│   ├── Amsterdam
│   │   ├── 000000-silicon -> ../../materials/000000-silicon/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   ├── Berkeley
│   │   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   ├── Oxford
│   │   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   └── README.md
├── grants
│   ├── Horizon-Europe
│   │   ├── 000000-silicon -> ../../materials/000000-silicon/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   ├── Marie-Curie
│   │   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   ├── NWO
│   │   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   │   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
│   └── README.md
├── materials
│   ├── 000000-silicon
│   │   ├── 00-relaxation
│   │   │   └── README.md
│   │   ├── 01-DFT
│   │   │   └── README.md
│   │   ├── 02-HSE
│   │   │   └── README.md
│   │   ├── 03-post-DFT
│   │   │   └── README.md
│   │   ├── common
│   │   │   └── README.md
│   │   └── README.md
│   ├── 000001-CdGeSb2
│   │   ├── 00-relaxation
│   │   │   └── README.md
│   │   ├── 01-DFT
│   │   │   └── README.md
│   │   ├── 02-HSE
│   │   │   └── README.md
│   │   ├── 03-post-DFT
│   │   │   └── README.md
│   │   ├── common
│   │   │   └── README.md
│   │   └── README.md
│   └── README.md
├── molecules
│   ├── 000000-caffeine
│   │   ├── 00-HF
│   │   │   └── README.md
│   │   ├── 01-optimization
│   │   │   └── README.md
│   │   ├── 02-VMC
│   │   │   └── README.md
│   │   ├── 03-DMC
│   │   │   └── README.md
│   │   ├── common
│   │   │   └── README.md
│   │   └── README.md
│   ├── 000001-C13H18O2
│   │   ├── 00-HF
│   │   │   └── README.md
│   │   ├── 01-optimization
│   │   │   └── README.md
│   │   ├── 02-VMC
│   │   │   └── README.md
│   │   ├── 03-DMC
│   │   │   └── README.md
│   │   ├── common
│   │   │   └── README.md
│   │   └── README.md
│   └── README.md
└── README.md
```

!!! warning

    This is only an indicative structure and can be modified based on the project requirements.
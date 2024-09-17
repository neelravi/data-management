# molecules

This directory contains folders for each molecule being studied. Each molecule folder contains subfolders for different stages of the calculation workflow.

Here, molecule folders are named using a unique identifier, e.g., `000000-caffeine`, `000001-C13H18O2`, etc. This helps in searching the molecules and allows multiple calculations to be performed on the same molecule.


## Organization

``` yaml
molecules/
├── 000000-caffeine
│   ├── 00-HF
│   │   └── README.md
│   ├── 01-optimization
│   │   └── README.md
│   ├── 02-VMC
│   │   └── README.md
│   ├── 03-DMC
│   │   └── README.md
│   ├── common
│   │   └── README.md
│   └── README.md
├── 000001-C13H18O2
│   ├── 00-HF
│   │   └── README.md
│   ├── 01-optimization
│   │   └── README.md
│   ├── 02-VMC
│   │   └── README.md
│   ├── 03-DMC
│   │   └── README.md
│   ├── common
│   │   └── README.md
│   └── README.md
└── README.md
```

!!! warning

    This is only an indicative structure and can be modified based on the project requirements.
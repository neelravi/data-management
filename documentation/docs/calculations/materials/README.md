# materials

This directory contains folders for each material being studied. Each material folder contains subfolders for different stages of the calculation workflow.

Here, material folders are named using a unique identifier, e.g., `000000-silicon`, `000001-CdGeSb2`, etc. This helps in searching the materials and allows multiple calculations to be performed on the same material.


## Organization

``` yaml
materials/
├── 000000-silicon
│   ├── 00-relaxation
│   │   └── README.md
│   ├── 01-DFT
│   │   └── README.md
│   ├── 02-HSE
│   │   └── README.md
│   ├── 03-post-DFT
│   │   └── README.md
│   ├── common
│   │   └── README.md
│   └── README.md
├── 000001-CdGeSb2
│   ├── 00-relaxation
│   │   └── README.md
│   ├── 01-DFT
│   │   └── README.md
│   ├── 02-HSE
│   │   └── README.md
│   ├── 03-post-DFT
│   │   └── README.md
│   ├── common
│   │   └── README.md
│   └── README.md
└── README.md
```

!!! warning

    This is only an indicative structure and can be modified based on the project requirements.
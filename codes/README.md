# codes

This folder contains various software packages, libraries, tools used in the project:

If the software was developed in a project, then a version controller should be used (git, gitlab, github, svn etc.). If the software is a third-party software, then the software should be downloaded and stored in this directory.

Mention the git hash or the version of the software used to reproduce the results in the README.md file of the software directory.

## Ready to Install Software `packages`

- **berkeleyGW**: BerkeleyGW software for GW calculations.

- **champ**: CHAMP software for quantum Monte Carlo.

- **quantum-espresso**: Quantum Espresso for DFT calculations.

- **vasp**: VASP for first-principles calculations.


## Version Controlled Software `devel`

- **berkeleyGW**: BerkeleyGW software for GW calculations.

- **champ**: CHAMP software for quantum Monte Carlo.

- **quantum-espresso**: Quantum Espresso for DFT calculations.


## Organization of the codes directory

``` yaml
codes/
├── devel
│   ├── champ
│   │   ├── 2.3.0
│   │   └── git
│   └── quantum-espresso
│       ├── 7.3.1
│       └── git
├── libraries
│   ├── hdf5
│   │   └── v1.14.2
│   ├── qmckl
│   │   └── v1.0.0
│   ├── README.md
│   └── trexio
│       └── v2.5.0
├── packages
│   ├── berkeleyGW
│   ├── quantum-espresso
│   │   ├── 7.3.1
│   │   └── git
│   └── vasp
│       └── 6.4.0
├── README.md
├── scripts
│   ├── python
│   │   ├── analysis
│   │   └── visualization
│   ├── README.md
│   └── shell
│       ├── compilation
│       └── slurm
└── tools
    ├── cmake
    ├── ninja
    └── README.md
```
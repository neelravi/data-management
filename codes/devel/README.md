# devel

This folder contains various software packages that are under development:

If the software is being developed in a project, then a version controller should be used (git, gitlab, github, svn etc.). If the software is a third-party software, then the software should be downloaded and stored in this directory.

Mention the git hash or the version of the software used to reproduce the results in the README.md file of the software directory.

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
```
# collaborations

This directory organizes materials by different collaborations:

- **Amsterdam**: Contains links to materials being studied with collaborators from Amsterdam.

- **Berkeley**: Contains links to calculations related to the Berkeley collaboration.

- **Oxford**: Contains links to materials for the collaboration with Oxford.

Each symbolic link points to its respective directory within `/calculations`.

Use the following command to create a symbolic link from the collaboration directory to the materials directory:

In the **Oxford** directory:

``` bash
ln -sfn ../../materials/000001-CdGeSb2/ 000001-CdGeSb2
```

The directory structure should look like this:

``` yaml
/collaborations/
├── Amsterdam
│   ├── 000000-silicon -> ../../materials/000000-silicon/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
├── Berkeley
│   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
├── Oxford
│   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
└── README.md
```
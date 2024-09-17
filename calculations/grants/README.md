# grants

This directory organizes calculations by different grants under which they were performed:

- **Horizon-Europe**: Contains soft-links to materials being studied under the EU Horizon-Europe grant.

- **NWO**: Contains soft-links to materials being studied under the NL NWO grant.

- **Marie-Curie**: Contains soft-links to materials being studied under the Marie-Curie ITN grant.

Each symbolic link points to its respective directory within `/calculations`.

Use the following command to create a symbolic link from the collaboration directory to the materials directory:

In the **Oxford** directory:

``` bash
ln -sfn ../../materials/000001-CdGeSb2/ 000001-CdGeSb2
```

The directory structure should look like this:

``` yaml
/grants/
├── Horizon-Europe
│   ├── 000000-silicon -> ../../materials/000000-silicon/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
├── Marie-Curie
│   ├── 000000-caffeine -> ../../molecules/000000-caffeine/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
├── NWO
│   ├── 000001-C13H18O2 -> ../../molecules/000001-C13H18O2/
│   └── 000001-CdGeSb2 -> ../../materials/000001-CdGeSb2/
└── README.md
```
# projects

This directory organizes calculations by different projects under which they were performed:

- **fugaku-2024**: Contains soft-links to molecules studied under the project fugaku-2024.

- **andrea-zen**: Contains soft-links to molecules studied under andrea-zen project.


Each symbolic link points to its respective directory within `/calculations`.

Use the following command to create a symbolic link from the collaboration directory to the materials directory:

In the **fugaku-2024** directory:

``` bash
ln -sfn ../../molecules/000000-caffeine/ fugaku-2024
```

The directory structure should look like this:

``` yaml
projects/
├── andrea-zen -> ../molecules/000001-C13H18O2
├── fugaku-2024 -> ../molecules/000000-caffeine
└── README.md
```

## Catalog Directory

This directory serves to contain individual operator catalogs.  Each operator will be contained in 
a sub-directory named after it.  
For example, for the operator catalog for 'example-operator', we would anticipate the following directory structure:

catalog/
└── example-operator
    ├── catalog.yaml
    └── OWNERS

## NB:  
Because all levels of the catalog hierarchy need to be able to pass an opm validation attempt, it may be necessary to include `.indexignore` files to exclude non-catalog files from the attempt. 

[See the OpenShift documentation for more information on these files.](https://docs.openshift.com/container-platform/4.10/operators/understanding/olm-packaging-format.html)



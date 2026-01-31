# Major_Assignment_ccds documentation!

## Description

This is a major assignment project which purpose is to provide training on cloud service storage access, data science project templating, and version controlling.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://ccdp-project/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://ccdp-project/data/` to `data/`.



# CDS-API docker container

This is a container image for the [CDSAPI](https://pypi.org/project/cdsapi/) python package.
It is designed for use with [Common Workflow Language](https://www.commonwl.org/) 
(CWL) tool descriptors and workflows.

## Requirements

* Docker (version 18.09 or later)

## Usage

### Tool descriptors

Tool descriptors are available in the [Atmospheric Tool Library](https://github.com/UoMResearchIT/atmos-tools-library).

### Workflows

Workflows using these tools are available on [WorkflowHub](https://workflowhub.eu/) in
the [Air Quality Prediction](https://workflowhub.eu/projects/103) group.

### Container Information

The `cdsapi` library has been installed via pip. 
This can be loaded by python scripts run within the container in the usual manner. 
To use the tool you will need to register with the CDS portal, and provide a `.cdsapirc` file.
Instructions for doing this are available from [https://cds.climate.copernicus.eu/how-to-api](https://cds.climate.copernicus.eu/how-to-api).

## Pre-built images

Images are available on the GitHub Container Repository:

* [python-cdsapi](https://github.com/UoMResearchIT/cdsapi-docker/pkgs/container/python-cdsapi) provides the python CDS-API library.

## Copyright & Licensing

### CDS-API

The CDS-API library is developed at the European Centre for Medium-Range Weather Forecasts
(ECMWF) and is released under the [Apache v2 license](http://www.apache.org/licenses/LICENSE-2.0).

### Docker scripts

The docker build scripts have been developed by the [Research IT](https://research-it.manchester.ac.uk/) 
department at the [University of Manchester](https://www.manchester.ac.uk/).

Copyright 2023 [University of Manchester, UK](https://www.manchester.ac.uk/).

Licensed under the MIT license, see the LICENSE file for details.
# cdsapi-docker

This build system creates a docker container for the cdsapi package.

Main page: https://cds.climate.copernicus.eu

## Requirements

* Docker (version 18.09 or later)

## Usage

Building the main container:
* `DOCKER_BUILDKIT=1 docker build . -t 'cdsapi' -f Dockerfile`

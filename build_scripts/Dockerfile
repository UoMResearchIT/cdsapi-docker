# syntax=docker/dockerfile:1.4.2

FROM python:3.13-bullseye

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt 

LABEL version.cdsapi=0.7.6
LABEL org.opencontainers.image.description="CDS API tool"
LABEL org.opencontainers.image.source="https://cds.climate.copernicus.eu"

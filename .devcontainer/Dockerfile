FROM mcr.microsoft.com/devcontainers/python:3.11-bookworm

# Librairies système nécessaires à GeoDjango
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
    gdal-bin libgdal-dev \
    proj-bin libproj-dev \
    libgeos-dev \
    sqlite3 \
 && apt-get clean && rm -rf /var/lib/apt/lists/*

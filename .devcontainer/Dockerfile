FROM mcr.microsoft.com/devcontainers/python:3.11-bookworm

# Dépendances système pour GeoDjango (GDAL/GEOS/PROJ) + SpatiaLite, build tools, sqlite
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
    gdal-bin libgdal-dev libgeos-dev libproj-dev \
    libsqlite3-mod-spatialite \
    build-essential python3-dev sqlite3 \
 && apt-get clean && rm -rf /var/lib/apt/lists/*

# Image Python stable et reproductible
FROM mcr.microsoft.com/devcontainers/python:3.11-bookworm

# Paquets système utiles (sqlite3 pour tests locaux, build tools si besoin)
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
    sqlite3 \
    && apt-get clean && rm -rf /var/lib/apt/lists/*


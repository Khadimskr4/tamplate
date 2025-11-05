# tamplate
Démarrer
1. Use this template.
2. Open in Codespaces
3. Laissez la construction finir (devcontainer).

Pui executer ces lignes de commande pour activer l'env et vérifier les versions de python et django

source .venv/bin/activate
python --version
python -m django --version
gdalinfo --version
python -c "from osgeo import gdal; print('GDAL Python:', gdal.VersionInfo())"

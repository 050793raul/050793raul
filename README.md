# Clona tu repositorio raul si no lo tienes localmente:
git clone https://github.com/050793raul/raul.git
cd raul

# Descarga el README.md del otro repo (puedes hacerlo manualmente o con wget/curl si es público):
# Ejemplo usando curl:
curl -O https://raw.githubusercontent.com/050793raul/050793raul/main/README.md

# Añade, commitea y sube los cambios:
git add README.md
git commit -m "Actualiza README.md desde 050793raul/050793raul"
git push

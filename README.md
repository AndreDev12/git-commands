# Comandos:

- Establece la rama predeterminada en main en lugar de master

  git config --global init.defaultBranch main

- Crear un alias con el nombre tree, se utiliza con git tree

  git config --global alias.tree "log --graph --decorate --all --oneline"

- Moverme a un commit específico y "que desaparezca commits posteriores", o para volver al commit final

  git resert --hard (hash de commit)

- Crea un tag de ejemplo

  git tag clase_1

- Moverme a un tag

  git checkout tags/clase_1

- Empuja la rama login desde tu repositorio local al repositorio remoto origin. Establece la rama login del remoto como la rama upstream de la rama login local (esto significa que la rama local login estará vinculada a la rama remota login)

  git push --set-upstream origin login

- Eliminar rama

  git branch -d login

- Descarga el historial de todas las ramas de remoto en el repositorio local

  git fetch

- Descarga el historial e incorpora cambios en el espacio de trabajo

  git pull

- Restaurar archivo como estaba la última vez

  git checkout (nombre del archivo)

- Hace una copia de los commits de la rama seleccionada y los mueve a la rama actual

  git merge (rama seleccionada)

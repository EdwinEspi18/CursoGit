--BASICO--
Subir archivo a git hub
- git init
- git add "Nombre del archivo"  o git add . (añade todo)
- git status -s (para verificar si se agrego el archivo)
- git commint -m "Nombre con el que se sube respaldo"
Entrar a git hub -> nuevo repositorio
- git remote add origin "liga"
- git push origin master
Actualizar de local a git hub
- git add .
- git commit -m "comentartio"
- git push
Actualizar de git a local
- editar en github
- iniciar bash en carpeta
- git pull (direccion del repositorio)
Tags Especificar versiones
- git tag "Nombre de version" -m "comentario"
- git push --tags
Verificar los commit
- git log --oneline
Restaurar borra lo nuevo "forma local"
-git reset --hard ("aqui poner el codigo del commit al que queremos estar)

Modificar comentario de un commit
- git commit --amend 
- :i
- Editar nombre
- ESC
- :wq

--RAMAS--
crear rama
- git branch (nombre de la rama"No debe llevar ni parentesis ni corchetes")
- git log --oneline o git branch (confirma visualmente la creación de la rama) 
moverse de rama
- git checkout (nombre de la rama a la que se mueve"No debe llevar ni parentesis ni corchetes")
- git branch (para confirmar la ubicaciond e la rama )
APARTIR DE AQUI, SE PUEDEN UTILIZAR LOS COMANDOS PARA AGREGAR VERSIONES
Moverse a master
- git checkout master
Unir ramas
- git merge (nombre de la rama a unir "No debe llevar ni parentesis ni corchetes")
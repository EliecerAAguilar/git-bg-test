# Git Notebook

## - git init

inicializa un nuevo repositorio de git

## - git add

añade archivos o carpetas al stagging area de git
archivos que esperan ha ser commit

## - git commit -m "msg"
guarda los cambios realizados a los archivos que estan en la stagging area

## - git merge
combina dos ramas en una sola

# - git branch <branch-name>
crea una rama nueva de git, copia los archivos de la rama actual a la nueva

## - git checkout <branch-name> [<hash|commit-id>]
cambia a la rama especificada. si se especifica un hash se cambia al commit especificado de la rama introducida

## - git remote
maneja los repositorios remotos

## - git reverse <commit-id>
regresa a un punto anterior a la historia de commits de la rama actual. los cambios de los commits que estan despues del commit especificado se mueven a la stagging area

## - git reset [--soft | --hard]


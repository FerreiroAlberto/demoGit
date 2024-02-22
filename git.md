# GIT

Git: Sistema de control de versiones distribuido.

GitHub: Plataforma de desarrollo colaborativo - Un hosting de repos de GIT.

## Comandos básicos de GIT

- git init: convierte una carpeta en un repositorio de GIT; es recomendable no convertir en repo una carpeta dentro de otro repo
- git clone: crea una carpeta nueva ya con su repo; git clone + url.
- git add: agrega archivos al área de preparación
- git commit guarda los cambios en el repo (local)
- git remote add origin + url añade un remoto
- origin es el nombre (alias) que le ponemos al remoto, por convención el primero siempre se llama origin,pero puedo añadirle otro en GitLab con otro nombre, por ejemplo
- git push - origin main: el -u le dice que por defecto queremos que cada vez que hagamos push lo suba al origin desde la rama principal
- git pull descarga al repo local los cambios subidos al remoto por otros

## Elementos

Working directory > Staging Aea > Repository

## Etiquetas

- Head: una etiqueta de texto que apunta a la rama actual
- Branch: etiqueta de texto que apunta al commit actual (normalmente el último)

Ramas: se usan para pruebas, vamos a probar tirando por este lado; o trabajo en paralelo en distintas partes/features del proyecto

## Comandos para trabajar con ramas

- Git branch me dice qué ramas tengo
- Git branch nombre_rama:crea la etiqueta de la nueva rama
- Git checkout: le dice a head que se cambie de rama
- Git checkout - b combina git branch y git branch
- Git merge nombre_rama: fusiona la rama especificada con la actual

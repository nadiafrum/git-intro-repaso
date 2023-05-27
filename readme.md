# Clase 15, repaso de GIT

```sh
git config --global user.name "Nadia Fum"
git config --global user.name "nadiafrum@gmail.com"
```

## Inicializar un repositorio

```sh
git init
```

Nota: esto crea en la raiz del proyecto la carpeta .git

## Areas del repositorio de GIT

* WD Working Directory: directorio de trabajo donde se agrega oquita los archivos durante el desarrollo.
* SA Staging Area: area temporal, intermedia, de control de cambios.
* LR Local Repo: es una caja donde voy a ir teniendo todas las fotos que saco del codigo

## Estado de los archivos

* Untracked: estan en el WD pero GIT no les esta dando seguimiento. Sabe que existen pero no sabe lo que tienen adentro. (aparece una U al lado del nombre del archivo)
* Unmodified: Archivos que GIT ya esta siguiendo, pero respecto al WD no fueron modificados
* Modified: archivos que se encuentran en el repositorio (estan siendo seguidos por GIT) y difieren del WD
* Staged: archivos que estan en el area temporal/intemedia.

## Saber estado actual de los archivos

```sh
git status
```

## Voy a poder mover los archivos de WD al SA

## La historia de commits (caja de fotos)
```sh
git log # la historia de commit detallada
git log --oneline # historia resumida en una sola linea
```

## Si quiero ver los cambios que tengo entre WD y LR

```sh
git diff
```

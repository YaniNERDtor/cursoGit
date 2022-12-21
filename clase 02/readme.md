# Clase 02

## Estado de los archivos

*untracked

*unmodified

*modified

*staged

## GIT LOG
Me muestra las fotos que les fui sacando al proyecto que están dentro del LOCAL REPO

```sh
git log --oneline
```
## GIT DIFF
Me permite visualizar los cambios que hay entre el working directory y la última foto (commit) dentro de la caja de commits (local repo).

```sh
git diff
```

## GIT AMMEND
Me permite agregar cambios al último commit.
Coloco en el stage area los cambios que quiero sumar en el último commit ya sean líneas de código o archivos y luego hago el ammend.

El git commit suele abrir un editor de texto (Nano) para colocar el mensaje o editar el mensaje actual

Ctrl + O = Guardar
Ctrl + X = Salir
```sh
git ammend
```
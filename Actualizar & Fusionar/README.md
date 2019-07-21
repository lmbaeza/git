# Actualizar & Fusionar

### Actualizar

Para actualizar tu repositorio local al commit más nuevo, se debe ejecutar en tu directorio de trabajo para bajar y fusionar los cambios remotos.

```console
$ git pull
```

### Fusionar

Para fusionar otra rama a tu rama activa (por ejemplo master), utiliza.
En ambos casos git intentará fusionar automáticamente los cambios. Desafortunadamente, no siempre será posible y se podrán producir conflictos.

```console
$ git merge <branch>
```

Tú eres responsable de fusionar esos conflictos manualmente al editar los archivos mostrados por git. Después de modificarlos, necesitas marcarlos como fusionados con

```console
$ git add <filename>
```

Antes de fusionar los cambios, puedes revisarlos usando

```console
$ git diff <source_branch> <target_branch>
```

### Bibliografia

[[1] - git - La guía sencilla By rogerdudler](https://rogerdudler.github.io/git-guide/index.es.html)
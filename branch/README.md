# Branch

### Crear un Branch

Se crea un branch con el nombre `nombre-branch`

```python
$ git branch nombre-branch
$ git branch 
#  LuisMBaezCo
#* master
```

### Cambiarse de Branch

Cambiar al branch `nombre-branch`

```python
$ git checkout nombre-branch
```

### Merge - Pasar de un Branch al master

```python
$ git branch 
# *nombre-branch
# master

$ git checkout master 
$ git merge nombre-branch 
$ git push -u origin master 
```
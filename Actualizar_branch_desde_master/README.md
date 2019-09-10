# Actualizar branch desde master

Para actualizar un branch con el contenido del master se usa el siguiente comando:

```console
git checkout <branch>
git fetch origin        
git merge origin/master
```
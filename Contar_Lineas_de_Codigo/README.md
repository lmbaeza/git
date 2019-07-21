# Contar Lineas de Codigo

Este comando cuenta el numero de lineas de codigo de cada uno de los ficheros.

```console
$ git ls-files | xargs wc -l
```

```js
`
wc: '&': No such file or directory
wc: Fusionar/README.md: No such file or directory
  31 Branch/README.md
  24 Heroku/README.md
  38 Log/README.md
   3 README.md
  96 total
`
```
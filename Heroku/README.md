# Comandos git en Heroku

### Iniciar Sesión en Heroku

```console
$ heroku login
```

### Clonar el repositorio

Utilice Git para clonar el código fuente de los repositorios a su máquina local.

```console
$ heroku git:clone -a nombre-repositorio
$ cd nombre-repositorio
```

### Despliega tus cambios
Realice algunos cambios en el código que acaba de clonar y despliéguelos en Heroku utilizando Git.

```console
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```
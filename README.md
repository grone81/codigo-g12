# Primer dia con Git y Github

Lista de Comandos de git

* Para poder ver la version de git 
ejecutamos en nuestra terminal:

```bash
git --version
git -v
```

* Para configrar el correo y nombre(solo la primera vez en mi maquina)


```bash
git config --global user.mail "micrre@gmail.com"
git config --global user.name "Mi nombre"
```

* Para ver la configuracion de git

```bash
git config --list
```
* Para inicializar nuestro repositorio en git:

```bash
git init
```

* Para ver el estado de nuestro cambio:

```bash
git status
```

* Para preparar nuestros archivos para la zona de stage (prepararlos para commit)
```bash
git add .
git add nombreDelArchivo.extension
```

* Crear el registro de los cambios realizados:

```bash
git commit -m "Comentario corto y conciso"
```

* para ver una linea de tiempo de los commits que hems realizado:

```bash
git log
```
* Para poder ver el detalle de un commit especifico usamos:

```bash
git show id-de-commit
```


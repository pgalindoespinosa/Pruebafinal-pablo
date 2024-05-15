# GITHUB

## ¿Que es GitHub?

GitHub es una web utilizada como nube para guardar proyectos (repositorios) de codigo en versiones.

## ¿Porque elegir GitHub?

Github es una excelente manera de poder subir nuestros trabajos a la nube de manera sencilla.

## ¿Como utilizar GitHub en nuestros proyectos?

Necesitaremos primero de todo:

- Una cuenta de GitHub
- GitHub en nuestro dispositivo
- Un proyecto que guardar

## Maquina Local

En nuestra maquina local, descargaremos GitHub para posteriormente utilizarlo en nuestro proyecto.

```
sudo apt update
sudo apt install git
```

Una vez descargado, necesitaremos comprobar que esta listo, con el comando `git --version`.

Visto que tenemos una version de GitHub, es decir, que lo hemos descargado, empezaremos con el guardado del repositorio.

## Configuración global de GitHub (Local)

```
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@example.com"
git config --global init.defaultBranch main
```

## Guardar repositorio y crear Commit

Vamos a iniciarnos en el proyecto, y para guardar y crear un commit necesitaremos este bloque de comandos

```bash
git init
git status
git add . 
git commit -m 'Crear el mensaje que queramos'
```

## Crear Repo en nuestro GitHub

Crearemos una repo en nuestra web de GitHub para poder enlazar y subir nuestros proyectos y guardarlos en version (Commits).

Para ello iremos a nuestro y en repositorio, crearemos una nueva repo con un nombre nuevo.

## Subir nuestra repo de la maquina local a la web

Por ultimo, para poder subir nuestro proyecto a la web y que podamos visualizarlo también desde allí. Necesitaremos ejecutar dos ultimos comandos:

```bash
git remote add origin https://github.com/nuestroperfil/nombrerepo.git
git push origin main
```

`Git remote` enlaza nuestra repo con la web, y `git push` lanza nuestro trabajo y lo actualiza.

Después de realizar esto, ya tendriamos todo configurado. Solamente tendriamos que realizar `git add .` y `git commit -m ''` cada vez que actualizemos y añadamos nueva documentación en nuestra repo y `git push`. 

### Esta es la configuración de GitHub en nuestras maquinas locales para guardar nuestros proyectos más preciados.

*Pablo Galindo*
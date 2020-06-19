# Informe_Manual_C2000

## Resumen

Informe con documentación de uso para los microcontroladores de la familia C2000 de Texas Instruments.

## Sub-Carpetas
1. `Imagenes`: Imágenes añadidas.

## Software para modificar repositorio
* LaTeX

## Autores del repositorio y ramas
* [Alan Wilson](https://github.com/orgs/POWERLAB-UTFSM/people/Alan-H-Wilson-V) (master, ALL)
* [Sebastián Rivera](https://github.com/orgs/POWERLAB-UTFSM/people/sriverai) (master, ALL)
* [Matías Licanqueo](https://github.com/orgs/POWERLAB-UTFSM/people/mlicanqueo) (ml)
* Sebastián Toro (st)
* [José Figueroa](https://github.com/orgs/POWERLAB-UTFSM/people/joafce) (jf)

## Usar Git con este proyecto
Para descargar este proyecto al computador local:
1. Instalar [Git](https://git-scm.com/downloads).
1. Instalar [Git LFS](https://git-lfs.github.com/).
1. Abrir la consola de comandos de Git e inicializar Git LFS:<br />
`git lfs install`
1. (*Opcional*) Instalar [Git Extensions](http://gitextensions.github.io), [GitHub Desktop](https://desktop.github.com/), o algún otro GUI para Git.
1. Ir al directorio principal donde se quiere dejar el repositorio local, y clonar desde el repositorio remoto `https://remote.git`:<br />
`git clone https://remote.git` <br />
En este caso: <br />
`git clone https://github.com/Informe_Manual_C2000.git`

### Usar Git desde la línea de comandos (manual)
1. **Abrir Bash:** <br /> Una vez que se hayan hecho las actualizaciones, ve al directorio del proyecto, abre la ventana de comandos de Git (Git Bash, u otro) y ejecuta:
1. `git status` <br /> Muestra los cambios hechos.
1. `git add [path/file]` <br /> Prepara los archivos/carpetas efectivos para consolidar (**Commit**). Para añadir todos los archivos a la vez, ejecutar `git add .`.
1. `git commit -m "description"` <br /> Consolida los cambios hechos con su respectiva descripción, y agrega el comentario `description`.
1. `git push origin master` <br /> Sube los cambios desde el repositorio local `origin` y la rama `master`, al repositorio remoto. Cambiar el nombre del repositorio local y rama, de ser necesario.
1. `git pull origin master` <br /> Descarga los últimos cambios desde el repositorio remoto hacia el repositorio local `origin` y la rama `master`.
1. `git checkout <branch>` <br /> Cambia a la rama `<branch>`.

Para más información: https://git-scm.com/doc
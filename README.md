# Portfolio de Álvaro

## Descripción

Este repositorio contiene mi portfolio personal, realizado como parte del proyecto intermodular de DAW.

Actualmente es una versión inicial que se irá ampliando con nuevos contenidos y proyectos.

## Portfolio

El portfolio está publicado mediante GitHub Pages:

https://alvarochp.github.io/portfolio/

## Despliegue

El despliegue se realiza automáticamente mediante GitHub Actions.

El workflow se encuentra en:

`.github/workflows/static.yml`

Cuando se hace un `push` en la rama `main`, GitHub Actions ejecuta el workflow y publica el contenido del repositorio en GitHub Pages.

También se ha realizado una prueba provocando un error en el workflow y otra modificando el nombre de `index.html`, para comprobar la diferencia entre un error del proceso de despliegue y un error en el contenido publicado.

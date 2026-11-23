# Blue Light · Página web

Página de presentación de **Blue Light**, un proyecto universitario de Yarvis Entertainment (Universidad del Norte). Es una sola página estática: `index.html` más las doce capturas `01.jpg` a `12.jpg`, sin dependencias ni paso de compilación.

Se despliega en Vercel con cada push a `main`.

## Parte de un repositorio mayor

Este repo es un submódulo de [BlueLight_Yarbis](https://github.com/AndresLizcano-Gjthub/BlueLight_Yarbis), que contiene el código fuente del juego. Ahí aparece como la carpeta `web`.

El archivo `.gdignore` hace que Godot ignore esta carpeta cuando se abre el proyecto principal. No lo borres.

## Cómo editarla

1. Cambia `index.html` o las imágenes y haz push a `main` en este repo.
2. En `BlueLight_Yarbis`, actualiza el puntero del submódulo: `git add web`, `git commit` y `git push`.

Si te saltas el segundo paso, el repo principal sigue apuntando a la versión anterior.

## Jugar

[webbluelight.netlify.app](https://webbluelight.netlify.app/)

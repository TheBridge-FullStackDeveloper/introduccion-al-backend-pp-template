![logotipo de The Bridge](https://user-images.githubusercontent.com/27650532/77754601-e8365180-702b-11ea-8bed-5bc14a43f869.png "logotipo de The Bridge")

# :crossed_swords: Backend Template #

## Introducción ##

![pic1]

Esta plantilla será la base para cualquier ejercicio de la semana de backend y para el proyecto de esta semana. Habrás de seguir actualizándola con una base de datos en un futuro.

Consiste en una aplicación de backend con una parte pública que sirva los estáticos **index.html**, **style.css** y **scripts.js**. Dicho archivo **scripts.js** hará una llamada a una ruta en backend al inicio y traerá un mensaje en formato *JSON*, para adjuntarlo al *HTML*.

## Requisitos ##

- Conocer Javascript

![pic2]

## Iteraciones ##

### Backend ###

Puedes seguir las instrucciones empleadas en la guía inicial de [Hello World example] y [Serving static files]

1. Crea un "hola mundo!", donde imprimirás por consola el mensaje, una vez inicie el servidor.

2. Configura una carpeta, llámese `public`, donde poner tus archivos estáticos.

3. Pon la "santísima trinidad", **index.html**, **style.css** y **scripts.js** en la carpeta `public`.

4. Haz que al inicio, cuando se cargue **index.html**, se haga una llamada a una ruta de backend, donde dicha ruta devolverá un mensaje en formato JSON, que **scripts.js** pintará en pantalla, a través de HTML.

### Herramientas ###

Configura las siguientes herrmaientas, utilizadas anteriormente en [Template HTML5 linter]:

- [Commitlint] y/o [Commitizen]
- [Husky]
- [Lint staged]
- [Eslint]

Han de funcionar tanto para el código backend como para frontend, y no olvides ignorar la carpeta `node_modules` y similares.

![pic3]

[Hello World example]: https://expressjs.com/en/starter/hello-world.html "Hello world"
[Serving static files]: https://expressjs.com/en/starter/static-files.html "Serving static files"

[Template HTML5 linter]: https://github.com/TheBridge-FullStackDeveloper/template-html5-linter "Template HTML5"
[Commitlint]: https://commitlint.js.org "Commitlint"
[Commitizen]: https://github.com/commitizen/cz-cli "Commitizen"
[Husky]: https://www.npmjs.com/package/husky "Husky"
[Lint staged]: https://github.com/okonet/lint-staged "Lint-staged"
[Eslint]: https://eslint.org "Eslint"

[pic1]: https://media.giphy.com/media/xTiTnxpQ3ghPiB2Hp6/giphy.gif "pic1"
[pic2]: https://media.giphy.com/media/xT4uQF7h39mlsF5czK/giphy.gif "pic2"
[pic3]: https://media.giphy.com/media/3oKIPpFhwsMNrRIjN6/giphy.gif "pic3"

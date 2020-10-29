# Clase 1

## Propósito del curso

Aprender a maquetar una página web utilizando [Pug](https://pugjs.org/api/getting-started.html) para describir el HTML y [SASS](https://sass-lang.com/) para describir el CSS.

## Introducción
Un navegador web (Chrome, Firefox, Safari, etc) para mostrar una página web, interpreta código escrito en 3 diferentes lenguajes de programación: [HTML](https://es.wikipedia.org/wiki/HTML), [CSS](https://es.wikipedia.org/wiki/Hoja_de_estilos_en_cascada) y [Javascript](https://es.wikipedia.org/wiki/JavaScript).

- **HTML** se utiliza para definir la estructura y los elementos de la página.
- **CSS** se utiliza para definir el estilo visual de estos elementos.
- **JavaScript** se utiliza para darle comportamiento lógico a los elementos y a la página en general.

En este curso vamos a enforcarnos en el aprendizaje de HTML y CSS.

## Pug y SASS
Tanto HTML como CSS son lenguajes antiguos (para la historia de la programación) y a pesar de que están en constante crecimiento, su sintaxis (la forma de escribir el código) no ha cambiado desde sus inicios. Esto significa que no son muy agradables de ver y entender. Tanto para aprender como para trabajar, escribir código HTML y CSS de forma directa se vuelve tedioso y frustrante.

Para solucionar este problema, existen `motores de plantilla` (template engine) que te ofrecen una sintaxis mucho mas agradable e intuitiva (además de otras funcionalidades). Utilizando estos `motores de plantilla`, el maquetador escribe un código mas simple, entendible y organizado, y luego los motores construyen el HTML y CSS resultante a partir de ese código.

- **Pug** es el `motor de plantilla` para construir HTML a partir de un código mas simple.
- **SASS** es el `motor de plantilla` para construir CSS a partir de un código mas simple.

## Codepen
[Codepen](https://codepen.io/) es una página web que nos permite escribir código `pug` y `sass` en una interfaz simple y nos permite ver el resultado en tiempo real. Al comienzo del curso vamos a utilizar **Codepen** para ver ejemplos y hacer prácticas.

## Primeros elementos HTML
**div**: Es uno de los elementos mas simples y a la vez mas importantes que tiene HTML. Si se quiere, se podría construir una página web completa solo con elementos div. Sirve para hacer una división dentro de la página.
  - Hereda pocas propiedades CSS de forma predeterminada.
  - Se puede utilizar tanto como **elemento de estructura** como **elemento visual**.
  - Se pueden poner un `div` adentro de otro `div`.
  - Sintaxis: 
    ```pug
    div Hola curso!
    ```

**a**: Elemento para definir un link hacia algo externo (otra pagina, un mail, un teléfono).
  - Tiene una propiedad única llamada `href` donde se define la url externa.
  - Es un **elemento visual**.
  - Sintaxis: 
    ```pug
    a(href='https://ohzi.io') Ir a OHZI
    ```

**img**: Elemento para cargar una imagen.
  - Tiene una propiedad única llamada `src` donde se define la url de la imagen.
  - Es un **elemento visual**,
  - Sintaxis:
  ```pug
  img(src='https://ohzi.io/img/team/5.jpg')
  ```
  
  

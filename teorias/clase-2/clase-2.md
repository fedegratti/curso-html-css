# Clase 2

## HTML

### Elementos estructurales
Elementos HTML que sirven para definir la estructura del sitio.
  - Generalmente son elementos `div`.
  - Generalmente son invisibles.
  - Generalmente **tiene** elementos hijos.

### HTML: Elementos visuales o de contenido
Elementos HTML que representan el contenido en si del sitio.
  - Pueden ser tanto elementos `div`, como `a`, `img`, `video`, etc.
  - Generalmente son visibles.
  - Generalmente **no tiene** elementos hijos.

### Clases
El atributo [`class`](https://developer.mozilla.org/es/docs/Web/HTML/Atributos_Globales/class) es una lista de palabras separadas por espacios que se le asigna a un elemento HTML y sirve para identificar a este elemento, ya sea de manera general (clases compartidas) o de manera particular (clase individual). Las clases permiten a CSS y Javascript seleccionar y acceder a elementos específicos.
Ejemplos de uso:
  - `div.boton`: *boton* es la clase del elemento.
  -  `div(class='boton')`: *boton* es la clase del elemento.
  - `.boton`: *boton* es la clase del elemento. En este caso, al no definir el nombre del elemento, `pug` asume que es un `div`.

## CSS

### Propiedades estructurales
  - [**display**](https://developer.mozilla.org/es/docs/Web/CSS/display): Especifica el comportamiento de presentación de un elemento. Los valores posibles que vamos a ver en el curso son: `block`, `flex` y `none`.
  - [**position**](https://developer.mozilla.org/es/docs/Web/CSS/position): Establece cómo se coloca un elemento dentro de su espacio disponible (el espacio del padre o del sitio). Los valores posibles son: `static`, `relative`, `absolute`, `fixed` y `sticky`.

### Propiedades de estilo
  - [**border**](https://developer.mozilla.org/es/docs/Web/CSS/border): Define el borde de un elemento. Elemplo: `border: 1px solid black`.
  - [**font-family**](https://developer.mozilla.org/es/docs/Web/CSS/font-family): Define una lista de fuentes con un orden de prioridad (de mas importante a menos importante). Elemplo: `font-family: Arial, sans-serif`.

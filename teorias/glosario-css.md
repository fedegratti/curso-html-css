# Glosario CSS

## Propiedades estructurales

[**display**](https://developer.mozilla.org/es/docs/Web/CSS/display): Especifica el comportamiento de presentación de un elemento. Los valores posibles que vamos a ver en el curso son:
  - `block`: El elemento genera un cuadro de elemento de bloque. (Valor predeterminado en un `div`).
  - `flex`: El elemento se comporta como un elemento de bloque y establece su contenido de acuerdo con el [modelo de flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout)
  - `none`: Desaparece la visualización de un elemento para que no tenga ningún efecto en el diseño (el documento se representa como si el elemento no existiera). Todos los elementos hijos tambien desaparecen.

[**flex-direction**](https://developer.mozilla.org/es/docs/Web/CSS/flex-direction): Especifica cómo colocar los objetos en el contenedor flexible definiendo el eje principal y la dirección. Valores posibles:
  - `row`: Se colocan los elementos de la manera que están definidos, de forma horizontal.
  - `row-reverse`: Se colocan los elementos de la manera inversa a la que están definidos, de forma horizontal.
  - `column`: Se colocan los elementos de la manera que están definidos, de forma vertical.
  - `column-reverse`: Se colocan los elementos de la manera inversa a la que están definidos, de forma vertical.

[**justify-content**](https://developer.mozilla.org/es/docs/Web/CSS/justify-content): define cómo el navegador distribuye el espacio entre los elementos flex, a lo largo del eje principal de su contenedor. Valores posibles:
  - `flex-start`: Los elementos se colocan bien a la izquierda del contenedor. O bien en la cima, si `flex-direction` tiene el valor `column`.
  - `flex-end`: Los elementos se colocan bien a la derecha del contenedor. O bien en el fondo, si `flex-direction` tiene el valor `column`.
  - `center`: Los elementos se colocan en el centro del contenedor horizontalmente. O verticalmente, si `flex-direction` tiene el valor `column`.
  - `space-evenly`: Los elementos se distribuyen de forma equitativa para ocupar todo el espacio disponible del elemento padre.
  - `space-around`: Parecido a `space-evenly` pero priorizando la separacion entre elementos.
  - `space-between`: Parecido a `space-around` pero el primer y ultimo elemento van a posicionarse en los extremos del elemento padre.

[**align-items**](https://developer.mozilla.org/es/docs/Web/CSS/align-items): define cómo el navegador distribuye el espacio entre y alrededor de los items flex, a lo largo del eje principal de su contenedor. Valores posibles:
  - `flex-start`: Los elementos se colocan bien en la cima del contenedor. O bien a la izquierda, si `flex-direction` tiene el valor `column`.
  - `flex-end`: Los elementos se colocan bien en el fondo del contenedor. O bien a la derecha, si `flex-direction` tiene el valor `column`.
  - `center`: Los elementos se colocan en el centro del contenedor verticalmente. U horizontalmente, si `flex-direction` tiene el valor `column`.

## Propiedades de estilo
  - [**border**](https://developer.mozilla.org/es/docs/Web/CSS/border): Define el borde de un elemento. Elemplo: `border: 1px solid black`.
  - [**font-family**](https://developer.mozilla.org/es/docs/Web/CSS/font-family): Define una lista de fuentes con un orden de prioridad (de mas importante a menos importante). Elemplo: `font-family: Arial, sans-serif`.

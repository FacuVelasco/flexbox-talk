# CATS AND FLEXBOX

## Problema

Quiero ordenar las fotos de mis gatos, pero el posicionarlos para todas las pantallas es muy dificil.

[Fotos de los gatos]

## Que herramientas conociamos?

Metodos como _float_ o _position_, pero son poco reliables para distintos tamaños de pantallas.

[float]

## Una posible solución

Flexbox

[sponge-bob rainbow]

## Que es flexbox?

Se le llama flexbox a un set de propiedades css que nos permiter ordenar un grupo de elementos HTML.

El objetivo es darle a los elementos la capacidad de ajustarse automaticamente dependiendo del espacio que tengan disponibles

## Donde se puede usar?

Logicamente al trabajar sobre HTML, lo vamos a usar en el browser, native apps, o hasta en aplicaciones de escritorio

## Compatibilidad

https://caniuse.com/#feat=flexbox

## Terminologia

Mayoritariamente usa propiedades con nombre autoexplicativo (?)
Cuando un elemento es flex, lo que va a ordenarse son los elementos que tenga adentro. Por eso vamos a llamar a este "Container" y a sus hijos "Childrens"

- Containers
- Childrens

Flexbox va a darle una direccion en la que los elementos pueden fluir, asi que siempre vamos a trabajar en Direcciones o Axis

- Direccion (Ejes)

## Ejes

Va a poder fluir en dos direcciones, vertical (como columna) o horizontal(como fila). Para settear la dirección usamos la propiedad _flex-direction_

- row
- column
- column-reverse
- row-reverse

**DEMO BASIC FLEX (row/columns)**

### Desde el container

No solo vamos a hacer que fluja, tambien podemos decirle como queremos que lo haga.

La propiedad _justify-content_ nos va a permitir decirle como fluye la data en el eje elegido. Y _align-items_ en el eje prependicular.

- center
- flex-start
- flex-end
- space-between
- space-around

### Desde los hijos

Tambien podemos ordenar como va a ordenarse un hijo en particular, con la propiedad _align-self_ podemos cambiar la ubicación en el eje perpendicular

**DEMO JC & AI**

## Advance properties

flex-wrap
flex-grow
flex-shrink

[flexbox-everywhere]

**FULL DEMO** (capaz podria ya tener algo listo)

## GRACIAS POR TODO

https://flexboxfroggy.com/

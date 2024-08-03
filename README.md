# Estilos CSS

Este documento describe el propósito y funcionamiento de cada atributo CSS utilizado en el archivo de estilos.

## Variables CSS

- `--color-primario`: Define el color de fondo principal de la página en `rgb(86, 86, 23)`.
- `--color-secundario`: Establece el color de texto principal en `#F6F6F6`.
- `--color-terciario`: Se usa para resaltar elementos, definido como `#22D4FD`.
- `--color-hover`: Es el color utilizado al pasar el cursor sobre ciertos elementos, definido como `#272727`.
- `--color-negro`: Define el color negro `#000`, usado en elementos como el texto del pie de página.
- `--fuente-montserrat`: Define la fuente 'Montserrat' para texto regular.
- `--fuente-krona`: Define la fuente 'Krona One' para títulos destacados.

## Estilos Generales

- `*`: 
  - `padding: 0`: Elimina el relleno predeterminado de todos los elementos para un control más preciso del espacio.
  - `margin: 0`: Elimina el margen predeterminado de todos los elementos para evitar espacios no deseados.

- `body`: 
  - `background-color`: Establece el color de fondo de la página utilizando `var(--color-primario)`.
  - `color`: Establece el color del texto utilizando `var(--color-secundario)`.
  - `box-sizing: border-box`: Cambia el modelo de caja CSS para incluir padding y border en el ancho y alto total de los elementos, asegurando que los elementos se dimensionen de manera más predecible.

## Header

- `.header`:
  - `padding: 2% 0% 0% 15%`: Añade espacio alrededor del contenido del encabezado, con un relleno de 2% en la parte superior y 15% a la izquierda para crear un diseño equilibrado.

- `.header__menu`:
  - `display: flex`: Utiliza el modelo de caja flexible para organizar los elementos en fila, permitiendo una alineación y distribución flexible.
  - `gap: 80px`: Espacio entre los elementos del menú, asegurando una separación clara y consistente.

- `.header__menu__link`:
  - `font-family`: Utiliza la fuente Montserrat para los enlaces del menú, asegurando consistencia tipográfica.
  - `font-size: 1.5rem`: Tamaño de fuente de 1.5 veces el tamaño base, lo que proporciona un texto claro y legible.
  - `font-weight: 600`: Define un grosor de fuente semi-negrita para mayor énfasis.
  - `color`: Establece el color del texto utilizando `var(--color-terciario)` para resaltar los enlaces.
  - `text-decoration: none`: Elimina el subrayado predeterminado de los enlaces para un diseño más limpio.

## Presentación

- `.presentacion`:
  - `display: flex`: Utiliza el modelo de caja flexible para organizar los elementos, facilitando una estructura responsiva.
  - `align-items: center`: Alinea verticalmente los elementos al centro, creando un diseño equilibrado.
  - `padding: 7% 15%`: Añade espacio alrededor del contenido de presentación para mayor claridad y separación.
  - `justify-content: space-between`: Distribuye los elementos equitativamente con espacio entre ellos, optimizando el uso del espacio.
  - `gap: 80px`: Espacio entre los elementos dentro de la presentación para asegurar una separación clara.

- `.presentacion__contenido`:
  - `width: 50%`: Establece el ancho al 50% del contenedor padre, creando un diseño equilibrado.
  - `display: flex`: Utiliza el modelo de caja flexible para organizar los elementos.
  - `flex-direction: column`: Organiza los elementos verticalmente para un diseño en formato de columna.
  - `gap: 40px`: Espacio entre los elementos para asegurar una separación clara y consistente.

- `.presentacion__contenido__titulo`:
  - `font-family`: Utiliza la fuente Krona One para los títulos, proporcionando un diseño distintivo.
  - `font-size: 2.25rem`: Tamaño de fuente de 2.25 veces el tamaño base, asegurando que los títulos sean prominentes.

- `.titulo-destaque`:
  - `color`: Establece el color de los elementos destacados utilizando `var(--color-terciario)` para resaltarlos.

- `.presentacion__conteniedo__texto` (note el error tipográfico en `conteniedo`, debería ser `contenido`):
  - `font-family`: Utiliza la fuente Montserrat para el texto, asegurando consistencia tipográfica.
  - `font-size: 1.5rem`: Tamaño de fuente de 1.5 veces el tamaño base para un texto claro y legible.

- `.presentacion__enlaces`:
  - `display: flex`: Utiliza el modelo de caja flexible para organizar los elementos.
  - `justify-content: space-between`: Distribuye los elementos equitativamente con espacio entre ellos.
  - `flex-direction: column`: Organiza los elementos verticalmente.
  - `gap: 32px`: Espacio entre los elementos para asegurar una separación clara.
  - `align-items: center`: Alinea horizontalmente los elementos al centro.

- `.presentacion__enlace__link`:
  - `width: 50%`: Ancho del enlace al 50% del contenedor padre, asegurando un diseño equilibrado.
  - `text-align: center`: Centra el texto horizontalmente dentro del enlace.
  - `padding: 21.5px 0`: Espacio vertical dentro del enlace para mayor comodidad al hacer clic.
  - `border-radius: 16px`: Bordes redondeados con un radio de 16px para un diseño más suave.
  - `font-family`: Utiliza la fuente Montserrat para los enlaces.
  - `font-size: 1.5rem`: Tamaño de fuente de 1.5 veces el tamaño base.
  - `font-weight: 600`: Grosor de fuente semi-negrita para mayor énfasis.
  - `text-decoration: none`: Elimina el subrayado predeterminado de los enlaces.
  - `color`: Establece el color del texto utilizando `var(--color-secundario)`.
  - `border: 8px solid var(--color-terciario)`: Bordes de 8px sólidos en el color terciario para un diseño destacado.
  - `display: flex`: Utiliza el modelo de caja flexible para organizar el contenido.
  - `justify-content: center`: Centra el contenido horizontalmente.
  - `gap: 16px`: Espacio entre los elementos dentro del enlace.

- `.presentacion__enlace__link:hover`:
  - `background-color`: Cambia el color de fondo cuando el enlace es seleccionado con el cursor para proporcionar retroalimentación visual al usuario.

- `.img`:
  - `width: 50%`: Establece el ancho al 50% del contenedor padre, permitiendo que las imágenes se escalen proporcionalmente.

- `.container`:
  - `width: 700px`: Establece el ancho fijo del contenedor para un diseño controlado.
  - `margin-left: auto`: Centra el contenedor horizontalmente en la página.
  - `margin-right: auto`: Centra el contenedor horizontalmente en la página.

- `.presentacion__contenido__subtitulo`:
  - `font-family`: Utiliza la fuente Montserrat para los subtítulos.
  - `font-size: 1.5rem`: Tamaño de fuente de 1.5 veces el tamaño base para asegurar legibilidad.
  - `font-weight: 400`: Grosor de fuente normal para un subtítulo más discreto.

## Footer

- `.footer`:
  - `background-color`: Establece el color de fondo del pie de página utilizando `var(--color-terciario)`.
  - `padding: 24px`: Añade espacio alrededor del contenido del pie de página para mejorar la legibilidad.
  - `color`: Establece el color del texto utilizando `var(--color-negro)`.
  - `text-align: center`: Centra el texto horizontalmente dentro del pie de página.
  - `font-family`: Utiliza la fuente Montserrat para el texto del pie de página.
  - `font-size: 1.5rem`: Tamaño de fuente de 1.5 veces el tamaño base para asegurar claridad.
  - `font-weight: 400`: Grosor de fuente normal para un texto informativo.

## Media Queries

- `@media (max-width: 1200px)`: Define estilos para pantallas con un ancho máximo de 1200px para asegurar que el diseño sea responsivo y adaptativo.

  - `.header`:
    - `padding: 10%`: Ajusta el relleno del encabezado para pantallas más pequeñas.

  - `.header__menu`:
    - `justify-content: center`: Centra los elementos del menú en pantallas pequeñas.

  - `.presentacion`:
    - `padding: 5%`: Ajusta el relleno de la presentación para mantener una buena proporción en pantallas pequeñas.
    - `flex-direction: column-reverse`: Cambia la dirección de los elementos a vertical y en orden inverso para una mejor disposición en pantallas pequeñas.

  - `.presentacion__contenido`:
    - `width: auto`: Ajusta automáticamente el ancho al tamaño del contenedor para flexibilidad en pantallas pequeñas.



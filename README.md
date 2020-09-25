# Evaluacion final - Módulo 1 - martreyz

Ejercicio de evaluación final del Módulo 1: HTML y CSS, en Adalab.
El ejercicio consiste en desarrollar una página web de acuerdo a un diseño dado, resolviendo los siguientes puntos:

- Uso de Sass.
- Uso de flexbox y CSS Grid.
- Uso de media queries.
- Resolución de algunas interacciones usando transiciones.
- Uso de animaciones CSS.

El desarrollo del ejercicio se ha llevado a cabo utilizando el [Adalab Starter Kit](https://github.com/Adalab/adalab-web-starter-kit), creado en node y gulp. Este Kit incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local; además de otras herramientas, como por ejemplo Gulp para la automatización de tareas o motor de plantillas.

## Composición de estilos según indicaciones:

- Header de la página, maquetado con Flexbox.
- Main de la página, dividido en dos secciones:
  - Una primera sección maquetada con estilo libre siguiendo un diseño.
  - Segunda sección maquetada con Grid.
- Footer de la página, maquetado con Flexbox.

- Otros requisitos:
  - Enlace de los botones de header y footer para la redirección a partes concretas de la página.
  - Transiciones en los botones del main para actuar con :hover.
  - Animación en el botón del footer.

## Composición del código:

- HTML: Dividido en tres partials base: header, main y footer; estando main subdividido con motivo de repetición del código en la sección 2, a vistas de optimizar el mismo.
- CSS: Dividido en partials:
  - Components: Contiene los partials referentes a estilos de botones y tipografía con carácter repetitivo en el diseño.
  - Core: Conotiene los partials referentes a la hoja de Reset y variables de valores con carácter repetitivo en el diseño.
  - Layout: Contiene los partials referentes a las particiones HTML, conteniendo los estilos de cada una de ellas.
  - Pages: Contiene los partials generales a toda la página.

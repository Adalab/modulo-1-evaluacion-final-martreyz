# Evaluación final módulo 1 [Adalab](www.adalab.es)
## Ejercicio de evaluación final del módulo 1 de Adalab: Maquetación de una web utilizando HTML y CSS

El ejercicio consiste en desarrollar una página web de acuerdo a un diseño dado, resolviendo los siguientes puntos:

- Uso de Sass.
- Uso de flexbox y CSS Grid.
- Uso de media queries.
- Resolución de algunas interacciones usando transiciones.
- Uso de animaciones CSS.

El desarrollo del ejercicio se ha llevado a cabo utilizando el [Adalab Starter Kit](https://github.com/Adalab/adalab-web-starter-kit), creado en node y gulp. Este Kit incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local; además de otras herramientas, como por ejemplo Gulp para la automatización de tareas o motor de plantillas.

![FireShot Capture 003 - Anonymous proxy - martreyz github io](https://user-images.githubusercontent.com/69849664/101142372-cf982580-3615-11eb-9eef-3bb580872b3e.png)


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

## Arranque del proyecto:

- npm install: Para instalar las dependencias
<img width="624" alt="install" src="https://user-images.githubusercontent.com/69849664/101142786-61a02e00-3616-11eb-877a-cff3666ceee5.PNG">

- npm start: Para arrancar el proyecto y probarlo en desarrollo a través de la URL '//localhost:3000/#/'
<img width="625" alt="start" src="https://user-images.githubusercontent.com/69849664/101142795-649b1e80-3616-11eb-9c46-ea5a31cef5a2.PNG">

- npm run docs: Para publicar el proyecto a producción
<img width="628" alt="docs" src="https://user-images.githubusercontent.com/69849664/101142807-66fd7880-3616-11eb-9b84-2c1ecd7a9672.PNG">

Hecho con :cat2: por @martreyz



# Final evaluation of module 1 [Adalab](www.adalab.es)
## Final evaluation exercise of module 1 in Adalab: Layout of a simple website using HTML and CSS.

The exercise consists in developing a webside as per a given design, solving the following bullets:

- Use Sass.
- Use flexbox and CSS Grid.
- Use media queries.
- Resolution of some user interactions using transitions.
- Use CSS animations.

The development of the exercise has been done using [Adalab Starter Kit](https://github.com/Adalab/adalab-web-starter-kit), created in node and gulp. This Kit includes a HTML template engine, SASS as preprocessor and a local server; it also includes other tools as, for example, Gulp for tasks automation. 

![FireShot Capture 003 - Anonymous proxy - martreyz github io](https://user-images.githubusercontent.com/69849664/101142372-cf982580-3615-11eb-9eef-3bb580872b3e.png)


## Styles composition as per indications:

- Website's Header section using Flexbox. 
- Website's Main section must be divided in two subsections:
  - First section can be mock-up with free style, always respecting the given design.
  - Second section mock-up with grid.
- Website's Footer section, must be mock-up with Flexbox.

- Other requirements:
  - Internal links of header and footer buttons must redirect to concrete areas in the website.
  - Main buttons must have transitions on :hover.
  - Footer button must have an animation. 

## Code composition:

- HTML: Dividided in three base partials: header, main and footer; being main subdivided in order to optimize repetitive code. 
- CSS: Divided in partials:
  - Components: Contents partials related to repetitive buttons and typography styles.
  - Core: Contents partials or created variables and Reset. 
  - Layout: Contents partials related to each of the HTML partials. 
  - Pages: Contents a partial related to the complete website.

## How to start the proyect:

- npm install: To install dependencies
<img width="624" alt="install" src="https://user-images.githubusercontent.com/69849664/101142786-61a02e00-3616-11eb-877a-cff3666ceee5.PNG">

- npm start: To start the project and try it in development server through URL '//localhost:3000/#/'
<img width="625" alt="start" src="https://user-images.githubusercontent.com/69849664/101142795-649b1e80-3616-11eb-9c46-ea5a31cef5a2.PNG">

- npm run docs: To publish project to production
<img width="628" alt="docs" src="https://user-images.githubusercontent.com/69849664/101142807-66fd7880-3616-11eb-9b84-2c1ecd7a9672.PNG">

Made with :cat2: by @martreyz

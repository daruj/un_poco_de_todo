un_poco_de_todo
===============

Un poco de todo es una App que pretende servir de aprendizaje de nuevas tecnologías.
La idea es tener una app que muestre direferentes categorías de mensajes: [chistes, jodas, excusas, piropos]

Tecnologías a utilizar:

- NodeJs (Para servir de servidor y proveer la lista de servicios)
- AngularJs (Para manejar el front-end de la app)
- SASS (Para tener un código css más limpio y escalable)
- MongoDB (Para utilizar como Base de Datos)

Comencemos
===============

PRIMERA ETAPA!

1) Primero tenemos que levantar nuestros servidor con NodeJs. Para eso vamos a bajarnos node y a instalarle express.js.
- Toda la documentación sobre node la podemos encontrar acá: http://nodejs.org/documentation/
- Toda la documentación de express la podemos encontrar acá: http://expressjs.com/guide.html

2) Especificar una carpeta de estáticos para nuestro proyecto desde el lado de front-end (fijarse como se hace en express)

3) Por medio de Express vamos a levantar nuestro index.html

4) Nuestro index.html tiene que incluir Angular.js

5) Crear un main.js que tenga las configuraciones de angular como por ejemplo: Nombre del módulo, y routers (los que dicen cuando la url es / mostrame esta vista con este controlador..)

6) Crear al menos 3 páginas diferentes que muestren una lista de su correspondiente categoría [chistes, jodas, excusas, piropos].

7) El index.html tiene que tener un header con un título de presentación, un nav (donde van a ir los links a las diferentes páginas), y un tag main que es donde se va a cargar las diferentes vistas cuando cambiemos la url.

8) Cada controlador tiene que tener un array de elementos de su categoría, el mismo se va a pasar a angular poer medio del $scope a su vista y luego se va a iterar usando el ng-repeat.

9) Cada vista tiene que tener un input text al principio que permita cargar nuevos datos a la lista de su categoría!

10) Darle estilos al sitio.


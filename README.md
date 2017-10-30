# Lyft

* **Unidad:** _Maquetado web con HTML & CSS_
* **Autora:** _Tatiana Tudela Hernández_

***

## Contenido del repositorio

1. Archivo `index.html`.

2. Carpeta **ccs** que contiene el archivo `main.css`.

3. Carpeta **docs** que contiene los archivos `footer.gif` y `fullpage.png` en los que se muestra la apariencia que deberá tener la pagina web a diseñar con HTML y CSS.

4. Carpeta **assets** que a su vez contiene la carpeta **images** cuyo contenido esta conformado por los archivos de las imagenes que se utilizaron en el diseño de la página: `apple-store.svg`, `google-play.png`, `hero.gif`, `logo-pink.png`, `logo-white.png`, `microsoft.png` y `phone.png`.

5. Archivo `README.txt`.  

## Explicación de los archivos `index.html` y `main.css`.

El archivo HTML esta conformado por las siguientes partes:

* **Encabezado delimitado por la etiqueta `<header>`:**
	En el archivo CSS se fijó el encabezado con un efecto transparente que muestra de fondo la imagen `hero.gif` y en el que se sobreponen el logo de Lyft con estilo de imagen `logo-white.png` y nombres de opciones de menú de color blanco, pero que al apuntar con el mouse cambia a un fondo de color blanco en el que el logo de Lyft cambia de color al estilo de la imagen `logo-pink.png` y nombres de opciones de menú color rosa `#FF00BF`. 

* **Bajo el encabezado se dividió el diseño en las siguientes secciones (delimitados por la etiqueta `<section>`):**

  - Sección "inicio" (formulario de registro del usuario a Lyft de fondo blanco que se sobrepone a la imagen de fondo).
	En el archivo CSS se utilizó el color `#352384` para el título del formulario, `#728099` para texto del formulario, un espaciado de 2 px en la etiqueta  `<p id="subtitulo">` y un color de fondo rosa al boton izquierdo del formulario de etiqueta `<a id="izq" href="">`.

  - Sección "imagen" (fondo degradado con títulos y detalles publicitario y la imagen de un celular en el que se muestra la aplicación Lyft).
	En el archivo CSS se aplicó un gradiente morado con `linear-gradient(#76278F, #2B1E66)` de fondo, a la izquierda texto publicitario de color blanco etiquetado como `<div class="ladoizq">` y en  el lado derecho se posicionó la imagen `phone.png` etiquetada como `<div class="ladoder">`.

  - Sección "amplify", "june" y "good" (fondo blanco con títulos, descripciones y videos publicitarios de Lyft).
	En el archivo CSS se posicionaron mediante `/embed/` los tres videos de youtube cuyas direcciones url fueron invocadas mediante la etiqueta `<iframe></iframe>`. Los titulos y descripciones publicitarias se presentan en color negro y fondo blanco.

* **Pie de página web delimitado por la etiqueta `<footer>`:**
	En el archivo CSS se aplicó un fondo color: `#333447` y texto blanco presentado en tres columnas, en la cuarta columna se muestran las imagenes proporcionadas: `microsoft.png` y `google-play.png` y en la parte inferior los iconos de `Icomoon` separados por una línea blanca del texto "© 2017 Lyft, Inc. Terms Privacy".
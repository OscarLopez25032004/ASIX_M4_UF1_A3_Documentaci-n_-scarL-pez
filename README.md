# ASIX_M4_UF1_A3_Documentaci-n_-scarL-pez

###### Primer capítulo: GITHUB
GitHub es una forja para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador.

Consultar el siguiente link para más documentación sobre GitHub:
(https://www.xataka.com/basics/que-github-que-que-le-ofrece-a-desarrolladores)

Consultar el siguiente link para mas documentación sobre Git:
(https://git-scm.com/docs/git/es#:~:text=Git%20es%20un%20sistema%20de,útil%20conjunto%20de%20comandos%20mínimo.)

**Git**
*¿Que es?*
Git es un sistema de control de versiones distribuido que permite el seguimiento de cambios en el código fuente durante el desarrollo de software.

**Repositorio**
Un repositorio es un espacio donde se almacena el código fuente de un proyecto y su historial de versiones o pushes.

**Commit**
Un commit es un conjunto de cambios confirmados en el repositorio. Cada commit tiene un mensaje que describe los cambios realizados.

**Branch**
Una rama (branch) es una línea de desarrollo independiente que permite trabajar en características nuevas sin afectar la rama principal.

**Como clonar un Repositorio**
```
git clone <URL del repositorio>
```

**Como añadir y confirmar cambios**
```
git add <nombre de archivo>
git commit -m "Mensaje descriptivo del commit"
```

**Como subir los cambios**
```
git push origin main
```

###### Segundo capítulo: MARKDOWN
Markdown es un lenguaje de marcas que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida.

Consultar el siguiente link para más documentación:
(https://markdown.es)

Primeramente hemos visto como poner titulos y subtitulos (añadiendo o quitando #).

Además como poner texto en cursiva (poner una 1 _ o 1 *) y en negrita (poner 2 ** o 2 __).
Texto en *Cursiva*.
Texto en _Cursiva_.
Texto en **Negrita**.
Texto en __Negrita__.

Como poner texto en negrita y cursiva.
Texto en *__negrita y cursiva__*.

Además hemos visto como hacer listas ordenadas.
1. Primera opcion de menú
2. Segunda opción de menú
3. Tercera opción de menú

Y también listas desordenadas
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primera opcion de submenú
    2. Segunda opcion de submenú
- Cuarta opción de lista desordenada
    * Primera opcion de submenú
    * Segunda opcion de submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

Como separar dos párrafos entre sí (como si le diesemos un "enter").
ahwbdawbdbawhdbhawbdawb
awdbaz
daw


dawbdawbdwaidabwidb
iwbdawbdiawbdibwdabaiwbdaiwbdiawba

Como poner código y que no se represente tal cual, sino que muestre el código.
```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un parrafo</p>
    </body>
</html>
```

Como poner enlaces, con descripción.
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

Además de ver como poner imagenes con sus descripciones.
![Esto es una imagen del Conde y de José Mourinho](https://github.com/OscarLopez25032004/ASIX1M4UF1-A3Apuntes/blob/main/image.png "Titulo opcional de la imagen")

Por último, hemos visto como hacer tablas, haciendo el encabezado y como se alinea el texto inferior (Según la disposición de los guiones).
|Primera Col.|Segunda Col.|Tercera Col|
|---------------|:----------|----------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha| 135€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ] Opción A
-[X] Opción B
-[ ] Opción C

###### Tercer capítulo: HTML
HTML es el lenguaje que se utiliza para crear una página web. Este lenguaje tiene cierta estructura (head, body...) y además tiene ciertas etiquetas que sirven para introducir elementos
a la página web.

Consultar el siguiente link para mas documentación sobre html:
(https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

<p>contenido visible</p>
en la etiqueta de apertura se ponen las clases.

Ejemplo:
<p class="valor">Contenido </p>

ANIDAR: Poner contenido dentro de contenido.
Ejemplo: <p>Hola <strong>que</strong> tal?</p>

Equivalente a 2 ENTER en Markdown= <br> (espacio entre parrafos).

###Creación de un documento html (extensión .html):

**html:5** para generar la estructura básica de un documento html*
*__4 Partes importantes en la estructura:__*
1. Tipo de documento:
 - *DOCTYPE*. En este caso **html**

2. Etiqueta html para especificar el idioma del archivo:
 - <html lang="en">
 - Todos el archivo se terminan con </html>.
 - Head y Body van dentro de esta etiqueta.

3. Etiqueta <head>:
 - Parte donde definimos las *0caract.* de la pagina y el contenido *no visible* por los visitantes a la página.
 - Aqui se añade la ruta de enlace con el archivo css de la página (El archivo que da estilo a la página web).
 - **Etiqueta <meta>**: Especifica un metadato. Por ejemplo el tipo de idioma de teclado (*UTF-8*= Teclado europeo, conñ y ç por ejemplo).
 - **Etiqueta <title>**: Titulo de la página, en la ventana, al lado del icono de la página (*favicon*).

 4. Etiqueta <body>:
 - Donde se ponen las etiquetas *visibles* de la página web.
 - *Etiquetas de bloque*:
   * Titulos, parrafos, listas, tablas...
 - *Etiquetas de linea*:
   * Enlaces, estilos, imagen...

Ejemplos Teoria HTML en archivo "Teoria6/10/23": [Enlace a la teoria del 6/10/23](https://github.com/OscarLopez25032004/ASIX_M4_UF1_A3_Documentaci-n_-scarL-pez/blob/main/Teoria6-10-23.html "Enlace a la teoria del 6/10/23")

**Etiqueta ol**
Creación de listas ordenadas.
Cada elemento de la lista empieza con la etiqueta <li>.


**Etiqueta ul**
Creación de listas desordenadas.
Cada elemento de la lista empieza con la etiqueta <li>.


**Etiqueta br**
Salto de linea.
Se cierra en la misma etiqueta.


**Etiqueta a**
Insertar un enlace.
Seguido de href (Para poner la ruta).


**Comentar SIEMPRE**
```
<!-- -->
```
 para poner comentarios.


**Etiqueta img**
Insertar una imagen.
Seguido de src (Para poner la ruta).
*Ejemplo de imagen*
```
<img src="ruta o url de la imagen" alt="Descripcion de la imagen">
```

**Etiqueta a**
Enlace a otro destino.
El destino se especifica con href.
Este destino puede ser en otra página o en la misma página.
    - *Misma página*: En el encabezado hay que poner un id y en el href superior añadir el # y el id que hayamos puesto.
    - *Otra página*: Enlazar con una ruta relativa.
*Ejemplo de a*
```
<a href="Url del enlace">texto a mostrar</a>
```

**Tablas en html**
Para mas teoria y ejemplos mirar tablas.html

**Como cambiar un icono de la pagina html**
Añadimos la siguiente linea en el head:
```
<link rel="icon" href="ruta del icono">
```
Consultar la siguiente pagina web para mas documentación:
(https://www.delftstack.com/es/howto/html/html-tab-icon/#utilice-y-una-imagen-png-para-agregar-favicon-para-el-sitio-web-en-html)

**Como cambiar el titulo de la pagina web**
Añadiremos o cambiaremos la siguiente linea en el head:
```
<title>Nuevo Título de la Página</title>
```
Consultar la siguiente web para mas documentación:
(https://developer.mozilla.org/es/docs/Web/HTML/Element/title)

###### Cuarto capítulo: CSS
CSS es el lenguaje que se utiliza para personalizar a tu gusto una página web.
Existen dos formas de enlazar el css. **Interno** o in-line (en la propia etiqueta) y **Externo** (en otro archivo enlazado en el head).

Consultar el siguiente link para mas documentación:
(https://www.hostinger.es/tutoriales/tipos-de-estilos-css)

Ejemplo de css interno:
```<table border="1" style="color:red;"```

Ejemplo de css externo:
```
h1 {
    color:red;
}
```
Haciendo referencia a todos los h1 que hay en el documento html.

Como declarar un id y enlazarlo.
 1. En la propia etiqueta, poner id="nombre"
 2. En el sitio a enlazar (interno o externo) poner #id que hayamos puesto antes.
 3. Poner las declaraciones css a elegir.

Ejemplos de declaraciones css:
*background-color* = rgb(0, 0, 255): para declarar el color de fondo.
*color: red* = para dar color a la letra.

###### Quinto capítulo: Mediaqueries
Las mediaqueries se utilizan para que la página web se vea de forma equitativa en cualquier altura y anchura en la que se ponga el navegador.

Ejemplo de media query:
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}

Se suelen utilizar para pedidas de mobiles (768px) y otras medidas como: 600px, 768px, 992px o 1200px...

Consulta el siguiente link para más documentación:
(https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
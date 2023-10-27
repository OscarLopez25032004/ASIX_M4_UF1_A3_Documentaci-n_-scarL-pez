# ASIX_M4_UF1_A3_Documentaci-n_-scarL-pez

Primeramente hemos visto como poner titulos y subitulos (añadiendo o quitando #).
###### Primer capítulo: MARKDOWN

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

##HTML
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

**Etiqueta a**
Enlace a otro destino.
El destino se especifica con href.
Este destino puede ser en otra página o en la misma página.
    - *Misma página*: En el encabezado hay que poner un id y en el href superior añadir el # y el id que hayamos puesto.
    - *Otra página*: Enlazar con una ruta relativa.

**Tablas en html**

Para mas teoria y ejemplos mirar tablas.html
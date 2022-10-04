# TUTORIAL DE MARKDON.
## SECCIONES DEL MARKDOWN`
[PARRAFOS](# PARRAFOS) 

    CABECERAS.

    CITAS.

    ESTILOS DE TEXTO.

[ENLACES.](#ENLACES.)

    IMAGENES.
    
    CODIGO.

[TABLAS.](#TABLAS)





## PARRAFOS.<a name="PARRAFOS">PARRAFO</a>

Para crear un nuevo párrafo en Markdown basta con que dejes una línea en blanco entre una o más líneas de texto.
Debes tener en cuenta una única recomendaicón, y es que no debes agregar sangrías o espacios a los párrafos al inicio
de los mismos salvo que los párrafos estén en una lista.

## ENCABEZADOS
Los encabezados se crean usando el carácter sostenido # delante de la oración que quieras que se formatee como un encabezado. 
Los encabezados pueden ser de diferentes niveles, organizándose jerárquicamente. 
Para crear encabezados de diferentes niveles debes agregar tantos símbolos # seguidos como el nivel del encabezado.

Ejemplo:

## Encabezado nivel 1

## Encabezado nivel 2

### Encabezado nivel 3

#### Encabezado nivel 4

##### Encabezado nivel 5

###### Encabezado nivel 6




## CITAS.

Para agregar citas en Markdown debes agregar el signo mayor > justo delante de una línea o de un párrafo:

> Ejemplo de citas

## ESTILOS DE TEXTO.

* **NEGRITA**.

    Para agregar texto resaltado en negrita tendrás que usar dos asteriscos ** y al final de lo oración que quieres resaltar. En caso de que quieras resaltar un texto que está en medio de una palabra, tedrás que agregar dos asteriscos **, antes y después de las letras deseadas

    Ejemplo:
        Esto es un **texto en negrita**.
        Esto es un texto parcialmente en ne**gri**ta.

       

* **CURSIVA**

Para agregar texto en cursiva debes usar un solo guión bajo _ tanto al inicio como al final de lo oración que quieres marcar como cursiva. Si quieres poner en cursiva ciertas letras que estén en la mitad de una palabra, deberás un guión bajo _, sin espacios, al comienzo y al final de las letras deseadas:

            Esto es un texto _cursiva_ 

## LISTAS ORDEADANDAS Y NO ORDENASA.
### LISTAS ORDENADAS.
Para agregar listas ordenadas en Markdown debes agregar un número seguido de un punto, un espacio y el elemento de la lista. La lista no debe estar ordenada numéricamente, pero debe comenzar por el número 1:

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

Aunque agregues los índices en un orden diferente al secuencial, cuando se represente la lista, los índices comenzarán por el número 1 y crecerán en una unidad por cada elemento de la lista.

### LISTAS NO ORDENAS.
Para agregar listas no ordenadas en Markdown debes agregar un guion -, un signo más + o un asterisco * delante de los elementos de la lista:

* UNO
* DOS
* TRES

### ANIDACION DE LISTAS.
Puedes anidar las listas de diferentes tipos, incluyendo listas dentro de otras listas, ya sean odenadas o no ordenadas. Para ello, los elementos de la lista anidada tendrán que tener una sangría de al menos cuatro espacios o una tabulación:

1. Primer elemento
2. Segundo elemento
    * Segundo elemento
    * Segundo elemento
3. Tercer elemento

## ENLACES.
Para crear un enlace en Markdown debes situar entre corchetes el texto que quieres enlazar, también conocido como anchor. Seguidamente, debes usar paréntesis para definir la URL a la que debe enlazar en texto del enlace:

Ejemplo: [Voy a google](https://www.google.es)

también podrás enlazar a puntos ancla de la página actual o de otras páginas postponiendo el carácter sostenido # y el id de la sección a enlazar:
Enlace a la sección [Encabezados](#ENLACES)

Además, también puedes crear enlaces rápidamente a una URL usando únicamente un enlace, sin necesidad de definir un texto de enlace o anchor. Para ello deberás escribir un símbolo mayor > seguido del enlace y un símbolo menor <:

<https://www.google.es>

Del mismo modo, también podrás crear enlaces mailto a direcciones de email mediante la misma sintaxis que los enlaces a URLs:

<email@edulazaro.com>

## IMAGENES
Para agregar imágenes con Markdown debes agregar un signo de exclamación ! seguido del texto alternativo o alt de la imagen entre corchetes y de la URL de la imagen entre paréntesis:

![Imagen ](/img)


### TITULO DE LA IMAGEN
Es posible agregar un título a la imagen, que se correpsonderá con el atributo HTML title. Para ello, basta con que agregues el título del enlace entre comillas después del enlace, en el interior de los paréntesis:

![Imagen](/img/ "Título del enlace")

### IMAGEN CON ENLACE.
Para agrear un enlace a una imagen, rodea todo el código Markdown de la imagen con corchetes y tras ellos, agrega el enlace entre paréntesis:

[![Imagen de unas nubes](/img/tutorial/imagen-markdown.webp)](/img/tutorial/imagen-markdown.webp)

## CODIGO.

### CODIGO EN LINEA.
Para agregar código en línea en Markdown tendrás que usar comillas invertidas alrededor del texto que quieres que tengo formato de código.

### CODIGOS DE BLOQUE
Si el código que quieres agregar consta de más de una línea, puedes agregar un bloque de código. para ello basta con que uses al menos cuatro espacios o una tabulación al inicio de la línea.

## TABLAS <a name="TABLAS"></a>
Para agregar tablas Markdown debes definir las cabeceras de columna mediante al menos tres guiones --- que se situarán por debajo del texto de la cabecera. Para separar las diferentes cabeceras tendrás que usar un símbolo de tubería |:

| Cabecera 1 | Cabecera 2 |
| ---------- | ---------- |
| Elem 1, 1  | Elem 1, 2  |
| Elem 1, 2  | Elem 2, 2  |

### ALINEACION.
Puedes alinear los elementos de una tabla en el centro, a la derecha o a la izquirrda usando dos puntos : en uno de los lados que definen la cabecera de la tabla para alinear su contenido a la izquierda o a la derecha respectivamente. Para alinear el contenido de la tabla en el centro, debes usar un símbolo : a cada lado de los guiones.

La primera columna del siguiente ejemplo tendrá su contenido alineado a la izquierda, la segunda en el centro y al tercera a la derecha:

| Nombre  | Tipo    | Color |
| :---    |  :----: |  ---: |
| Manzana | Fruta   | Rojo  |
| Pera    | Fruta   | Verde |

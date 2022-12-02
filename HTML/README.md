# TRABAJOS REALIZADOS EN LA CAPACITACIÓN PARA EL TRABAJO: PROGRAMACIÓN EN JAVA

## **TIPOS DE LISTAS**

**Lista Desordenada** [Ver aquí](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/HTML/Tipo%20de%20Listas.html).

Las listas desordenadas en HTML nos sirven para mostrar los elementos sin ningún tipo de orden, simplemente precedidos por una viñeta que puede ser un punto, un cuadrado,…

Para definir una lista desordenada en HTML utilizamos el elemento  `<ul>` .


```html
<ul> ... </ul>

```
Para representar los elementos de la lista desordenada utilizamos el mismo elemento que con las listas ordenadas, es decir, el elemento li.

```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento N</li>
</ul>
```

De esa forma podríamos tener el siguiente código HTML:

```html
<ul>
	<li>azucar</li>
	<li>tomates</li>
	<li>aceite</li>
	<li>huevos</li>
</ul>
```
Que nos mostrará lo siguiente:
- azucar
- tomates
- aceite
- huevos

**Lista Ordenada**

Las listas ordenadas en HTML son aquellas que nos muestran los elementos de la lista en orden. Para representar el orden tendremos los elementos numerados. Es decir, cada uno de los elementos irá precedido de un número o letra que establezca su orden.

Las listas ordenadas en HTML se representan mediante el elemento `<ol>`

```html
<ol> ... </ol>

```
Cada uno de los elementos de la lista ordenada se representará mediante el elemento `<li>`

```html
<ol>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  ...
  <li>Elemento N</li>
</ol>
```
Un ejemplo de lista ordenada sería el siguiente:

```html
   <ol>
       <li>101</li>
       <li>102</li>
       <li>103</li>
   </ol>
```
Que nos mostrará lo siguiente:
1. 101
2. 102
3. 103

De igual manera podemos indicar el tipo de lista ordenada en HTML que queremos representar.

Entre los tipos de listas que podemos representar tenemos:

1 - Listas decimales
a - Listas alfabéticas en minúsculas
A - Listas alfabéticas en mayúsculas
i - Listas de números romanos en minúsculas
I - Listas de números romanos en mayúsculas

Los valores indicados al principio son los que le podemos asignar al atributo `type` de la lista ordenada en HTML, de la siguiente manera

```html
   <ol type="A">
       <li>101</li>
       <li>102</li>
       <li>103</li>
   </ol>

```
Que nos mostrará lo siguiente:
A. 101
B. 102
C. 103

** Listas Descriptivas**

Las listas de definiciones en HTML nos sirven para montar listas en las que tenemos la estructura valor y definición. Suelen ser listas para definir términos, como si fuese un diccionario, si bien pueden ser cualquier par valor-definición.

Las listas de definiciones en HTML se construyen mediante el elemento `<dl>`.
```html
<dl> ... </dl>

```
En este caso, dentro de las listas de definiciones en HTML tenemos dos elementos anidados: el que representa al valor `<dt>` y el que representa a la definición `<dd>`. De esta forma la estructura de las listas en HTML de definiciones es la siguiente:
```html
<dl>
  <dt>Término1</dt>
  <dd>Definición 1</dd>
  <dt>Término 2</dt>
  <dd>Definición 2</dd>
  ...
  <dt>Término N</dt>
  <dd>Definición N</dd>
</dl>
```
Si queremos crear una lista en HTML con definiciones de palabras, podemos escribir lo siguiente:
```html
<dl>
    <dt>Sirena</dt>
    <dd>Animal fabuloso que vive en el mar, con cabeza y torso de mujer y extremidades inferiores de pez o ave.</dd>
    <dd>Aparato que emite un sonido fuerte que se oye a mucha distancia y que sirve para avisar de alguna cosa.</dd>
    <dt>Vela</dt>
    <dd >Una vela, candela, espelma o bujía es una fuente de iluminación, consistente en una mecha que asciende por el interior de una barra de combustible sólido, ...</dd>
    <dd>La vela es un deporte náutico que consiste en controlar la dinámica de un barco propulsado solamente por el viento en sus velas.</dd>
</dl>
```
Que nos mostrará lo siguiente:

**Sirena**

Animal fabuloso que vive en el mar, con cabeza y torso de mujer y extremidades inferiores de pez o ave.

Aparato que emite un sonido fuerte que se oye a mucha distancia y que sirve para avisar de alguna cosa.

**Vela**

Una vela, candela, espelma o bujía es una fuente de iluminación, consistente en una mecha que asciende por el interior de una barra de combustible sólido, ...

La vela es un deporte náutico que consiste en controlar la dinámica de un barco propulsado solamente por el viento en sus velas.

## **TIPOS DE ENLACES**

**Hipervinculos** [Ver aquí](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/HTML/Hipervinculos.html).

El hipervinculo o hipertexto refiere a enlaces que conectan una página Web con otra, ya sea dentro de la misma página web o entre diferentes páginas del mismo o distintos sitios web. los vínculos son un aspecto fundamental de la Web.

Básicamente podemos dividir los enlaces o links en 3 tipos:

1. Enlaces internos: son los que se dan entre páginas web del mismo dominio.
1. Enlaces externos: son los que se dan entre páginas web de distinto dominio.
1. Enlaces de posición:
	- De un lugar a otro dentro de la misma página.
	- De un lugar a otro lugar concreto de distinta página del mismo dominio.
	- De un lugar a otro lugar concreto de una página de otro dominio.

**Etiqueta HTML para enlaces:**

El Elemento HTML anchor  `<a>` crea un enlace a otras páginas de internet, archivos o ubicaciones dentro de la misma página, direcciones de correo, o cualquier otra URL. Necesita obligatoriamente el atributo `<href>` que contiene una URL o un fragmento de URL al cual apunta el enlace.

Dentro del atributo  `<href>` la URL puede escribirse de forma **absoluta** (incluyendo el dominio) o **relativa** (sin incluir el dominio) solo para enlaces dentro del mismo dominio. Tanto de una forma u otra, la *ruta* de carpetas (path) debe especificarse.

Este atributo puede ser omitido (a partir de HTML5) para crear un enlace de marcador de posición. Un enlace de marcador de posición se parece a un enlace tradicional, pero que no dirige a algún lugar.

Puede ser utilizado
```html
href="#top"
```
o un fragmento vacío
```html
href="#"
```
 para enlazar a la parte superior de la página actual.
 
 Si queremos ser mas específicos:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplos de Hipervinculos</title>
</head>
<body>
    <!-- Enlace EXTERNO (a una página de otro dominio) -->
    <a href="https://developer.mozilla.org">ir a MDN</a>

<!-- Supongamos que estamos en el dominio www.3con14.pro -->

    <!-- Un enlace INTERNO ABSOLUTO sería:  -->
    <a href="http://3con14.pro/teoria/definicion.html">definición</a>

    <!-- Un enlace INTERNO RELATIVO sería:  -->
    <a href="./teoria/definicion.html">definición</a>

    <!-- Un enlace de POSICIÓN a otro lugar de la misma página:  -->
    <a href="./teoria/#ejemplo4">Ejemplo 4</a>

    <!-- Un enlace de POSICIÓN a otro lugar de distinta página:  -->
    <a href="./teoria/tipos.html#tipo3">Tipo 3</a>

    <!-- Un enlace de POSICIÓN a otro lugar de otro dominio:  -->
    <a href="http://www.w3c.es/noticias.html#premios">Tipo 3</a>
</body>
</html>
```

## **TIPOS DE TABLAS**

**TABLAS SIMPLES**  [Ver aquí](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/HTML/Tabla%20simple.html).

Una tabla no es otra cosa más que un medio de organizar datos en filas y columnas. Este concepto ha estado presente en nuestra sociedad por un largo período de tiempo y ha sido adoptado por HTML en sus etapas iniciales, como una forma de transmitir información que, de otro modo, no sería comprendida tan fácilmente.

En documentos HTML una tabla puede ser considerada, resumidamente, como un grupo de filas donde cada una contiene a un grupo de celdas. Esto es conceptualmente distinto a un grupo de columnas que contiene a un grupo de filas, y esta diferencia tendrá un impacto en la composición y comportamiento de la tabla.

***** *Las tablas NO deben usarse para maquetar una Web.*

La etiqueta `<table>`... `</table>` es el contenedor de la tabla y por tanto las filas y columnas de una tabla deben estar dentro de este par de etiquetas.
Mientras que `<tr>`... `</tr>`  es una fila y  `<td>`... `</td>` es una celda dentro de una fila.

![Estructura](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/Imagenes/tabla1.png)
***** *Las tablas NO deben usarse para maquetar una Web.*

**TABLAS AVANZADAS**

Tablas avanzadas `<table>`,  `<tr>` y `<td>` hay otras etiquetas y atributos que podemos utilizar al crear tablas en HTML:
- `<th>` : Se emplea para definir las celdas que son cabecera de una fila o de una columna de la tabla.
- `<caption>` : Se emplea para definir la leyenda o título de una tabla.

Y entre los atributos más comunes tenemos:

- `<colspan>` : "numero"  que es el número de columnas que ocupa esta celda.
- `<rowspan>` : "numero"  que es el número de filas que ocupa esta celda.

Para comprender mejor tenemos el siguiente ejemplo:

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla avanzada</title>
</head>
<body>
    <table>
        <caption>Resultados Globales</caption>
        <tr>
          <th colspan="4">Curso 2019/2010</th>
        </tr>
        <tr>
          <th colspan="2">1º ESO - A</th>
          <th colspan="2">1º ESO - A</th>
        </tr>
        <tr>
          <td>Aprobados</td>
          <td>Suspensos</td>
          <td>Aprobados</td>
          <td>Suspensos</td>
        </tr>
        <tr>
          <td>68%</td>
          <td>57%</td>
          <td>32%</td>
          <td>43%</td>
        </tr>
      </table>
</body>
</html>

```
En el navegador se vería así:
![Estructura](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/Imagenes/TbA.jpg)

Como he dicho anteriormente las tablas, por defecto, no muestran las líneas que dan forma a la tabla. Así que se crearon con este codigo css:

```css
td,th {
  padding: 0.5em;
  border: 1px solid rgba(0,0,0,0.2);
}
```

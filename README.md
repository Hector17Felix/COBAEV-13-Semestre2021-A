# COBAEV-13-Semestre2021-A
### TRABAJOS REALIZADOS EN LA CAPACITACIÓN PARA EL TRABAJO: PROGRAMACIÓN EN JAVA

#### **TIPOS DE LISTAS**

**Lista Desordenada**

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

Puedes visitar un ejemplo hecho en mi estadia en el COBAEV 13 => [Tipos de listas](http://https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/Tipos%20de%20Listas.html "Tipos de listas")

[Lista Desordenada](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/commit/9847bab0ac729be995f011d648bb7b37d1cb9f63).



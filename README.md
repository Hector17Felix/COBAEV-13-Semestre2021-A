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

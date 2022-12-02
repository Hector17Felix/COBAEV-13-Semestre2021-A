# COBAEV-13-Semestre2021-A

## CAPACITACIÓN PARA EL TRABAJO: Programacíon en Java

### HTML

**HTML** significa *“HyperText Markup Language”*, es un lenguaje de hipertexto para poder hacer estructuras de páginas y es el lenguaje estándar que utilizan todos los navegadores para interpretar la estructura de tu página, permitiéndole leer y saber los elementos que contiene, su posición, e incluso tu posicionamiento dentro de los buscadores, lo cuál esta estrictamente relacionado con la optimización de motores de búsqueda [(SEO)](https://www.cyberclick.es/inbound-marketing/seo "(SEO)") para que la información de tu sitio este bien posicionada dentro de internet, y las personas la encuentren con mayor facilidad, puesto que nos permite darle un esqueleto a nuestros sitios y organizar nuestra información de la manera adecuada, conforme vayamos avanzando en la misión puntualizaremos más en ello.

HTML existe desde hace un poco más de 20 años, el mismo tiempo de funcionamiento de los navegadores, conforme pasan los años este lenguaje ha ido evolucionando y actualmente nos encontramos en la versión HTML 5, que justamente será con la que trabajaremos a continuación. Esta versión es soportada por la gran mayoría de los navegadores, a excepción a veces de Internet Explorer que le cuesta interpretar el lenguaje, sin embargo, [Chrome](https://www.google.com/intl/es-419/chrome/ "Chrome"), [Safari](https://www.apple.com/mx/safari/ "Safari"), [Firefox](https://www.mozilla.org/es-MX/firefox/new/ "Firefox"), [Opera](https://www.opera.com/es "Opera"), [Brave](https://brave.com/es/ "Brave"), etc, logran interpretar de manera correcta HTML. No olviden que en la primera semana les deje una herramienta que les permite revisar si la tecnología que están usando se visualiza de forma correcta en los navegadores existentes.



Su estructura es la siguiente:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hola Mundo</title>
</head>
<body>
    Hola Mundo!
</body>
</html>

```
 Donde:

![Estructura](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/Imagenes/estructura-basica-de-una-pagina-web-en-html.jpg)

### CSS

**CSS** significa *Cascading Style Sheets* y parten de un concepto simple pero muy potente: aplicar estilos (colores, formas, márgenes, etc...) a uno o varios documentos (generalmente documentos **HTML**, páginas webs) de forma automática y masiva.

Se le denomina estilos en cascada porque se lee, procesa y aplica el código desde arriba hacia abajo (siguiendo un patrón denominado herencia que trataremos más adelante) y en el caso de existir ambigüedad (código que se contradice), se siguen una serie de normas para resolver dicha ambigüedad.

La idea de CSS es la de utilizar el concepto de separación de presentación y contenido. Este concepto se basa en que, como programadores, lo ideal es separar claramente el código que escribimos. ¿Por qué? Porque con el tiempo, esto hará que el código sea más fácil de modificar y mantener.

La idea es la siguiente:

    Los documentos HTML (contenido) incluirán sólo información y datotodo lo relativo a la información a transmitir.
    Los documentos CSS (presentación) inclurán sólo los aspectos relacionados con el estilo (diseño, colores, formas, etc...).

Se estructura de esta manera:
```css
P {color:red; 
   font-size:20px;
  }
```

Donde:

![Estructura](https://github.com/Hector17Felix/COBAEV-13-Semestre2021-A/blob/main/Imagenes/csses.jpg)


### JavaScript

**JavaScript** es un lenguaje de programación que los desarrolladores utilizan para hacer páginas web interactivas. Desde actualizar fuentes de redes sociales a mostrar animaciones y mapas interactivos, las funciones de JavaScript pueden mejorar la experiencia del usuario de un sitio web. Como lenguaje de scripting del lado del servidor, se trata de una de las principales tecnologías de la **World Wide Web**. Por ejemplo, al navegar por Internet, en cualquier momento en el que vea un carrusel de imágenes, un menú desplegable *“click-to-show”* (clic para mostrar), o cambien de manera dinámica los elementos de color en una página web, estará viendo los efectos de **JavaScript**.

Anteriormente, las páginas web eran estáticas, similares a las páginas de un libro. Una página estática mostraba principalmente información en un diseño fijo y no todo aquello que esperamos de un sitio web moderno.** JavaScript
JavaScript,** surgió como una tecnología del lado del navegador para hacer que las aplicaciones web fueran más dinámicas. Por medio de ** JavaScript
JavaScript**,los navegadores eran capaces de responder a la interacción de los usuarios y cambiar la distribución del contenido en la página web.

Su estructura es la siguiente:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hola Mundo</title>
</head>
<body>
    <script type="text/javascript">

        var nombre = "Reyli";

        window.alert(nombre);

        alert(nombre);

    </script>
</body>
</html>
```
La idea es la siguiente:

Progrma que dada la variable "nombre" la muestra en una ventana emergente
Donde:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hola Mundo</title>
</head>
<body>
    <script type="text/javascript">
        //1- Declaración de variables
        var nombre = "Reyli";

        //2- Funcion
        //3- Intrucciones
        window.alert(nombre);
        alert(nombre);

        //4- Devolver resultados
        //Se monstrara en pantalla dos recuadros con el nombre de la variable "nombre"

    </script>
</body>
</html>
```

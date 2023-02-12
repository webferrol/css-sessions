# <abbr title="Cascading Style Sheets">CSS</abbr>

## Sesión 1

## Terminar el último formulario pendiente

## Qué es CSS

__CSS__ es el _acrónimo_ o _abreviatura_ de "Hojas de estilo en Cascada". Se trata de

  un __lenguaje__ usado para definir la __presentación__ de un __documento estructurado__ escrito en __HTML__ o derivados.

Por tanto se trata de:

- [x] Un lenguaje
- [x] Nos permite diseñar o poner bonito un HTML

## Utilizar CSS en HTML

Existen tres formas de utilizar CSS en un __documento HTML__:

- __CSS inline__. Como su nombre indica dentro de la __etiqueta de apertura__ de un __elemento HTML__ colocar el atributo __style__. Se denomina "CSS interno" puesto que las reglas van dentro del mismo documento HTML. 

```html
<body style="margin: 0;color: #eee">
  <h1>Hello world!</h1>
</body>
```

- Utilizando etiquetas __style__ (normalmente dentro del elemento __head__). También se trata de "CSS interno".

```html
<style>
  body {
    margin: 0;
  }
</style>
```

- Utilizando un archivo externo donde poner nuestro CSS, por tanto, "CSS externo". Para ello existe una etiqueta html denominada "link" donde indicar donde se encuentra nuestro fichero CSS. También tiene que ir en el elemento __head__.

```html
<head>
  <link rel="stylesheet" type="text/css" href="style.css" />
</head>
```

En el fichero css es donde colocaríamos nuestras reglas. Veamos un poco de código en "style.css":

```css
body {
  margin: 0;
  color: #eee;
}
```

## Sintaxis

![Sintaxis CSS](./assets/selector.gif)

- El selector apunta al elemento HTML que desea diseñar.
- El bloque de declaración contiene una o más declaraciones separadas por punto y coma. Cada declaración incluye:
  - un nombre de propiedad CSS
  - un valor

Múltiples declaraciones CSS están separadas por punto y coma, y ​​los bloques de declaración están rodeados por llaves.

## Selectores

[Selectores](https://bluuweb.dev/02-css/#selectores)

## Ejercicios

1. Para realizar con el profesor:

  - Crearemos un html y escribiremos en el documento nuestro famoso "Hello World" dentro de un título de primer nivel (__h1__). Trabajaremos con el __color__ property
    - Utilizaremos un fichero externo llamado "style.css" para poner el __body__ del documento con color de fuente rojo
    - Utilizaremos una etiqueta __style__ para poner el color _tomato_ en la etiqueta __body__ 
    - Utilizaremos __CSS inline__ para poner el color de texto amarillo a la etiqueta body

2. Realizar los 4 primeros ejercicos propuestos por bluuweb

[CSS selectors](https://www.w3schools.com/css/exercise.asp?filename=exercise_selectors1)

3. Realizar el ejercicio de texto del siguiente [enlace](https://github.com/webferrol/css-simple-text)
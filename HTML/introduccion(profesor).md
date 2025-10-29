
# Introducción a HTML

HTML (HyperText Markup Language) es el lenguaje estándar para la creación de páginas web. A continuación, te proporcionamos una introducción completa a la estructura básica de un documento HTML y sus componentes principales.

## Estructura Básica de un Documento HTML

Cada documento HTML sigue una estructura básica, que comienza con una declaración de tipo de documento (`<!DOCTYPE html>`) para indicarle al navegador que está utilizando HTML5.

### Componentes Clave

- **`<html lang="es">`**: Define el idioma del documento como español. Se coloca al principio y al final de todo el contenido visible de la página.
  
  ```html
  <html lang="es">
  ...
  </html>
  ```

- **`<meta charset="UTF-8">`**: Especifica la codificación de caracteres como UTF-8, permitiendo que la página soporte varios caracteres. Esta etiqueta va dentro del `<head>`.

  ```html
  <meta charset="UTF-8">
  ```

- **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Asegura que la página se ajuste correctamente en dispositivos móviles.

  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

## Encabezados

Los encabezados se escriben con las etiquetas `<h1>` a `<h6>`. El encabezado principal es `<h1>`, y el más pequeño es `<h6>`.

  ```html
  <h1>Título Principal</h1>
  <h2>Subtítulo</h2>
  ```

## Listas

En HTML, hay dos tipos de listas principales:

- **Listas ordenadas** (`<ol>`), que muestran los elementos numerados.
- **Listas desordenadas** (`<ul>`), que muestran los elementos con viñetas.
- **Elementos de las listas** (`<li>`), que definen cada elemento de las listas.
```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
</ul>

<ol>
  <li>Paso 1</li>
  <li>Paso 2</li>
</ol>
```

## Tablas

Una tabla HTML (<table>) es un conjunto de celdas (<td> o <th>) organizadas en filas (<tr>) que a su vez se pueden organizar en grupos de filas (<thead>, <tbody> o <tfoot>). Además, la tabla puede tener una leyenda (<caption>) y hacer referencia a las columnas (<col> y <colspan>).
Las celdas de la tabla suelen ser elementos <td>, aunque también pueden ser elemento <th> para indicar que la celda es una cabecera de la fila o columna correspondiente.

```html
<table>
  <thead>
    <tr>
      <th>Producto</th>
      <th>Precio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Naranja</td>
      <td>1.2€</td>
    </tr>
    <tr>
      <td>Manzana</td>
      <td>1€</td>
    </tr>
  </tbody>
</table>
```

## Imágenes

Para insertar imágenes, se usa la etiqueta `<img>`. Dentro de esta etiqueta, hay que incluir los atributos `scr`, para indicar la ruta y el atributo `alt` para una descripción alternativa.

```html
<img src="ruta_de_imagen.jpg" alt="Descripción de la imagen">
```

## Formularios

Los formularios permiten a los usuarios ingresar datos que se envían a un servidor. Se utilizan etiquetas como `<form>`, `<input>`, `<label>`, y un botón `<button>` de envío.

```html
<form action="/enviar" method="post">
  
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" placeholder="Introduce tu nombre">
  <br>
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" placeholder="Introduce tu password">
  <br>
  <label for="numero">Número:</label>
  <input type="number" id="numero" name="numero" placeholder="Introduce un número">
  <br>
  <label for="email">Correo electrónico:</label>
  <input type="email" id="email" name="email" placeholder="Introduce tu correo electrónico">
  <br>
  <button type="submit">Enviar</button>
</form>
```

## Multimedia

HTML también permite integrar contenido multimedia como videos y audios usando las etiquetas `<video>` y `<audio>`.

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  Tu navegador no soporta este video.
</video>

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Tu navegador no soporta este audio.
</audio>
```



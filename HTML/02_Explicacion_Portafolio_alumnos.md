
# Explicación del Ejercicio: Portafolio Militar

Antes de que los alumnos comiencen a trabajar en su propio portafolio militar, es importante comprender qué se espera en cada sección. A continuación, se explica qué tipo de información y código deben añadir en cada parte del documento HTML.

## 1. Encabezado del Portafolio Militar

En el encabezado, se debe incluir el título principal del portafolio usando la etiqueta `<h1>`. Además, es importante crear un menú de navegación utilizando la etiqueta `<nav>` que permita a los usuarios moverse entre las secciones de la página.

- **Instrucciones:**
    - Escribe tu nombre en lugar de `[Tu Nombre]`.
    - Crea un menú de navegación con enlaces a las secciones del portafolio, como "Información Personal", "Destinos Militares", "Formación y Cursos", "Habilidades", y "Contacto".

## 2. Información Personal

Esta sección debe incluir detalles básicos sobre el militar, como el nombre completo, rango, unidad actual, y años de servicio. Usa la etiqueta `<p>` para cada línea de información y `<strong>` para resaltar los datos más importantes.

- **Instrucciones:**
    - Añade tu nombre completo, rango, unidad y años de servicio utilizando las etiquetas correctas.
    - Ejemplo: 
    ```html
    <p>Nombre completo: <strong>Juan Pérez</strong></p>
    ```

## 3. Destinos Militares

En esta sección, los alumnos deben crear una lista desordenada de los destinos en los que han servido. Usa la etiqueta `<ul>` para la lista y `<li>` para cada destino.

- **Instrucciones:**
    - Crea una lista de los destinos en los que has servido, incluyendo la unidad militar, la fecha de inicio y la fecha de fin.
    - Ejemplo:
    ```html
    <ul>
        <li><strong>Destino 1:</strong> [Unidad Militar] - [Fecha de Inicio] a [Fecha de Fin]</li>
    </ul>
    ```

## 4. Formación y Cursos

Aquí, los alumnos deben crear una tabla que muestre los cursos y certificaciones completados. Usa las etiquetas `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` y `<td>` para estructurar la tabla.

- **Instrucciones:**
    - Crea una tabla con tres columnas: Curso, Institución y Fecha de Finalización.
    - Añade las filas correspondientes para cada curso que hayas completado.
    - Ejemplo:
    ```html
    <table border="1">
        <thead>
            <tr>
                <th>Curso</th>
                <th>Institución</th>
                <th>Fecha de Finalización</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Curso de Operaciones Especiales</td>
                <td>Academia Militar</td>
                <td>2022</td>
            </tr>
        </tbody>
    </table>
    ```

## 5. Habilidades y Competencias

Los alumnos deben crear una lista de las habilidades y competencias adquiridas a lo largo de su carrera militar. Usa la etiqueta `<ul>` para la lista y `<li>` para cada habilidad.

- **Instrucciones:**
    - Crea una lista de habilidades adquiridas. Puedes incluir habilidades técnicas, de liderazgo, manejo de equipo, idiomas, etc.
    - Ejemplo:
    ```html
    <ul>
        <li>Conocimientos avanzados en operaciones tácticas</li>
        <li>Dominio de varios idiomas: Inglés, Francés</li>
    </ul>
    ```

## 6. Sección de Contacto

En la sección de contacto, se debe crear un formulario que permita a los visitantes del portafolio enviar un mensaje. Usa etiquetas como `<form>`, `<input>`, `<textarea>`, y `<button>` para construir el formulario.

- **Instrucciones:**
    - Crea un formulario con los campos de nombre, correo electrónico, y mensaje.
    - Añade un botón de envío para que los visitantes puedan enviar el formulario.
    - Ejemplo:
    ```html
    <form action="enviar.php" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>

        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required>

        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje"></textarea>

        <button type="submit">Enviar</button>
    </form>
    ```

## 7. Pie de Página

Finalmente, en el pie de página, los alumnos deben añadir una frase como "Portafolio Militar - Creado por [Tu Nombre]" y el año actual. Usa la etiqueta `<footer>` para esta sección.

- **Instrucciones:**
    - Añade tu nombre y el año en el pie de página.
    - Ejemplo:
    ```html
    <footer>
        <p>Portafolio Militar - Creado por Juan Pérez</p>
        <p>&copy; 2024 Todos los derechos reservados.</p>
    </footer>
    ```

## Conclusión



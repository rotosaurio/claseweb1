hypertext markup lenguaje o en español lenguaje de marcado de hipertextos es el lenguaje base para la creacion de las paginas web ya que  son los que tienen la estructura basica 
la parte de hipertexto se refiere a que puede contener hipervinculos o links/enlaces dentro de su misma estructura la estructura basica de una pagina en html se divide en etiquetas como las siguientes


<html>
<head>
    <title>Ejemplo de Etiquetas HTML</title>
</head>
<body>
    <h1>Título Principal</h1>
    <h2>Subtítulo</h2>
    <p>Este es un párrafo de texto.</p>
    <a href="https://www.ejemplo.com">Enlace a Ejemplo</a>
    <img src="ejemplo.jpg" alt="Imagen de ejemplo">
    <div>
        <p>Este es un div que contiene otro párrafo.</p>
    </div>
    <span>Este es un texto dentro de un span.</span>
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>
    </ul>
    <ol>
        <li>Elemento A</li>
        <li>Elemento B</li>
        <li>Elemento C</li>
    </ol>
    <table border="1">
        <tr>
            <th>Encabezado 1</th>
            <th>Encabezado 2</th>
        </tr>
        <tr>
            <td>Dato 1</td>
            <td>Dato 2</td>
        </tr>
    </table>
    <form action="procesar.php" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre"><br><br>
        <label for="mensaje">Mensaje:</label><br>
        <textarea id="mensaje" name="mensaje" rows="4" cols="50"></textarea><br><br>
        <button type="submit">Enviar</button>
    </form>
</body>
</html>

1. **`<html>`**: Envuelve todo el contenido HTML de la página.
    
2. **`<head>`**: Contiene metadatos sobre el documento, como el título, enlaces a hojas de estilo, scripts, etc.
    
3. **`<title>`**: Define el título del documento que se muestra en la pestaña del navegador.
    
4. **`<body>`**: Contiene todo el contenido visible de la página, como texto, imágenes, enlaces, etc.
    
5. **`<header>`**: Define el encabezado de una sección o de la página en general.
    
6. **`<nav>`**: Define un conjunto de enlaces de navegación.
    
7. **`<main>`**: Define el contenido principal de la página.
    
8. **`<section>`**: Define una sección de contenido.
    
9. **`<article>`**: Define un contenido independiente y autónomo, como un artículo de un blog o una noticia.
    
10. **`<aside>`**: Define contenido relacionado pero que está apartado del contenido principal.
    
11. **`<footer>`**: Define el pie de página de la página o de una sección.
    
12. **`<div>`**: Se utiliza para agrupar elementos y aplicar estilos o comportamientos comunes.
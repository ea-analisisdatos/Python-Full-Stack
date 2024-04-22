# Explicación del código HTML

Este código HTML define la estructura de una página web. 

1. `<!DOCTYPE html>`: Define el tipo de documento como HTML5, indicando al navegador qué versión de HTML se está utilizando.

2. `<html lang="es">`: El elemento `<html>` es el contenedor raíz de todo el contenido HTML de la página. El atributo `lang` se utiliza para especificar el idioma principal del contenido, que en este caso es español (`es`).

3. `<head>`: Esta sección contiene metadatos y enlaces a recursos externos que son necesarios para la presentación de la página, pero no forman parte del contenido visible para el usuario.

   - `<meta charset="UTF-8" />`: Especifica la codificación de caracteres del documento como UTF-8, que es una codificación de caracteres Unicode que admite una amplia variedad de caracteres y símbolos.
   
   - `<meta http-equiv="X-UA-Compatible" content="ie=edge" />`: Proporciona instrucciones al navegador sobre cómo debe interpretar y mostrar la página. En este caso, "ie=edge" indica que el navegador debe utilizar la última versión del motor de renderizado de Internet Explorer.
   
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: Define cómo debe comportarse y escalar la página en dispositivos móviles. `width=device-width` indica que el ancho de la página debe ajustarse al ancho del dispositivo, y `initial-scale=1.0` establece el nivel de zoom inicial a 1.0.

   - `<link rel="stylesheet" href="style.css" />`: Enlaza la hoja de estilos externa llamada "style.css" para aplicar estilos a la página.

   - `<title>Ejemplo de maquetación</title>`: Define el título de la página que se muestra en la pestaña del navegador.

4. `<body>`: Esta sección contiene todo el contenido visible de la página, incluyendo encabezados, párrafos, botones, secciones y pie de página.

   - `<header>`: Define la cabecera de la página, que generalmente incluye el logotipo y la barra de navegación.
   
   - `<section>`: Define secciones de contenido de la página, como el héroe (sección principal), información sobre la empresa, programas ofrecidos, características y llamada a la acción final.
   
   - `<footer>`: Define el pie de página de la página, que generalmente incluye información de copyright y enlaces adicionales.

   - Dentro de estas secciones, se utilizan diferentes clases y etiquetas HTML para estructurar y presentar el contenido de manera adecuada, incluyendo títulos (`h1`, `h2`, `h3`), párrafos (`p`), botones (`button`), listas (`ul`, `li`), imágenes, y contenedores (`div`).



# Explicación del código CSS

Este código CSS define estilos para una página web. Explicación de algunas de las reglas CSS utilizadas:

- `* { box-sizing: border-box; }`: Esto hace que al añadir margen o relleno a los elementos, estos no crezcan más allá del borde de su contenedor. La propiedad `box-sizing: border-box;` hace que el tamaño total de un elemento incluya el relleno y el borde, pero no el margen exterior.

- `html { scroll-behavior: smooth; }`: Esta regla hace que el desplazamiento entre secciones de la página sea suave, con una transición animada.

- `body { ... }`: Aquí se establecen varios estilos para el cuerpo del documento, como el tamaño de fuente, el margen (que se establece en 0 para eliminar el espacio entre el borde del cuerpo y el borde de la ventana del navegador), y se establece la fuente para todo el documento como "Roboto" (una fuente sans-serif).

- `h1`, `h2`, `h3`, `p { ... }`: Se definen diferentes tamaños de fuente para los títulos y párrafos.

- `ul { list-style: none; }`: Esta regla elimina los puntos por defecto de las listas desordenadas.

- `button { ... }`, `button:hover { ... }`: Estilos para los botones y sus estados de desplazamiento.

- `.container { max-width: 1400px; margin: auto; }`: Esta clase se utiliza para limitar el ancho máximo de los elementos contenedores y centrarlos horizontalmente en la página.

- `header`, `header nav`, `header a { ... }`: Estilos para la barra de navegación, incluyendo la apariencia de los enlaces de navegación.

- `#hero { ... }`: Estilos para la sección de héroe, que incluye una imagen de fondo con superposición de color y contenido centrado verticalmente.

- `#somos-Bejob`, `#nuestros-programas`, `#Caracteristicas`, `#final`: Estilos para diferentes secciones de la página, incluyendo alineación de texto, fondos y colores.

- `@media (min-width: 850px) { ... }`, `@media (min-width: 1200px) { ... }`: Estilos específicos que se aplican sólo cuando el ancho de la ventana del navegador es mayor que ciertos valores, ajustando el diseño de la página para diferentes tamaños de pantalla.

Estos son sólo algunos ejemplos de las reglas CSS utilizadas en este código. Cada una de ellas define cómo se verá y se comportará un elemento específico en la página web.
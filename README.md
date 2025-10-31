El README.md debe incluir: - Descripción del proyecto y temática elegida - Estructura del sitio (qué contiene cada página) - Decisiones de diseño estructural tomadas

## Descripción del Proyecto

Este proyecto se desarrolla a solicitud de la organización comunal anarquista de Madrid, **"Utopía Cotidiana"**. El objetivo es diseñar y construir su plataforma web, sirviendo como un punto central para la difusión de sus actividades y filosofía.

### Temática Elegida

La temática principal del proyecto es **mostrar y difundir el pensamiento de la organización**, así como promocionar las diversas actividades, proyectos y eventos que realizan en su espacio comunal.

----------

## Estructura del Sitio (Contenido por Página)

El sitio se compone de las siguientes secciones clave, diseñadas para una navegación clara:

-   **`index.html`:** Página de Bienvenida. Presentación inicial de la organización y un mensaje de bienvenida.
    
-   **`servicios.html`:** Librería/Venta de Libros. Sección dedicada a mostrar el servicio de venta de libros gestionado por la organización.
    
-   **`about.html`:** Filosofía y Objetivos. Detalle sobre el pensamiento de la organización, su tipo de estructura comunal y sus objetivos fundacionales.
    
-   **`blog.html`:** Agenda/Actividades. Sección dinámica para publicar y anunciar las actividades y proyectos que se llevarán a cabo.
    
-   **`contacto.html`:** Formulario de Contacto e Inscripción. Formulario destinado a la inscripción de interesados y para que la organización pueda contactarles.
    
-   **`conciertos_ev.html`:** Eventos Destacados/Conciertos. Promoción de eventos especiales o conciertos próximos a realizarse.
    

----------

## Decisiones de Diseño Estructural y Semántica

Las decisiones de estructura se han tomado priorizando la **buena semántica HTML5** y los principios de **Ecodiseño**, buscando optimizar el código para una mejor accesibilidad, mantenimiento y rendimiento (menor impacto ambiental).

Se han utilizado de forma rigurosa las principales **etiquetas semánticas** para estructurar el contenido:

### 1. Etiquetas Estructurales de Alto Nivel

-   **`<header>`:** Define la cabecera de la página. Contiene elementos esenciales como el logotipo y el menú de navegación.
    
-   **`<nav>`:** Define la sección de navegación principal del sitio.
    
-   **`<main>`:** Define el contenido principal y único del documento. Solo debe existir uno por página.
    
-   **`<body>`:** Contenedor de todo el contenido visible de la página web.
    
-   **`<footer>`:** Define el pie de página, habitualmente para derechos de autor, enlaces secundarios o información de contacto.
    
-   **`<section>`:** Define secciones temáticas dentro de la página.
    
-   **`<article>`:** Define contenido independiente y autocontenido (ej. entradas de blog o noticias).
    

### 2. Etiquetas para Jerarquía y Agrupación

-   **`<h1>` a `<h6>`:** Jerarquización del contenido. Esencial para la accesibilidad y el SEO.
    
-   **`<p>`:** Agrupación para párrafos de texto.
    
-   **`<ul>`, `<ol>`, `<li>`:** Creación de listas no ordenadas, ordenadas y sus elementos, respectivamente.
    

### 3. Etiquetas de Interacción y Contenido Incrustado

-   **`<a>`:** Creación de hiperenlaces para la navegación interna y externa.
    
-   **`<img>`:** Inserción de imágenes en la página web.
    

### 4. Etiquetas para Formularios (Utilizadas en `contacto.html`)

-   **`<form>`:** Contenedor principal de todos los elementos del formulario.
    
-   **`<fieldset>`:** Agrupación temática de elementos de un formulario (genera un recuadro visual).
    
-   **`<legend>`:** Título o descripción del grupo definido por `<fieldset>`.
    
-   **`<label>`:** Define el nombre o título de un control de formulario.
    
-   **`<input>`:** Campo genérico de introducción de datos por parte del usuario.
    
-   **(Para tablas):** `<tr>`, `<td>`, `<th>` para filas, celdas de datos y celdas de encabezado.
 
En caso de que se haya omitido algún requisito esencial en el proyecto, **agradezco de antemano cualquier observación para la mejora continua.**
Me gustaría cerrar con una frase que guía mi aprendizaje:

_Yo no estudio para saber más, sino para ignorar menos_
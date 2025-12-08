## 💡 Descripción y Temática del Proyecto

El proyecto web **"Utopía Cotidiana"** es el sitio digital para una **casa comunitaria anarquista y autogestionada**. El objetivo principal es la difusión de los principios de la comunidad y la captación de nuevos participantes y visitantes.

**Aspecto**

**Descripción**

**Temática Central**

Anarquismo en la vida diaria, Apoyo Mutuo, Autogestión y Construcción de Alternativas Sociales.


----------

## 🌐 Estructura del Sitio (Contenido por Página)

El sitio web consta de **seis páginas HTML** principales, cada una dedicada a un aspecto clave de la comunidad:

### 1. `index.html` (Inicio)

Es la puerta de entrada. Presenta una **bienvenida** impactante, define la comunidad (no es una ONG ni un retiro) y enumera los tres **principios fundamentales**: Apoyo Mutuo, Auto-Organización y Construcción de Alternativas Reales.

### 2. `about.html` (Quiénes somos)

(Solo se proporcionó el encabezado, pero su función es clara).

Página dedicada a la profundización de la identidad del proyecto. Explicaría la filosofía, la historia, los valores y, posiblemente, los miembros clave o cómo funciona la toma de decisiones asamblearia.

### 3. `servicios.html` (Servicios libertarios)

(Solo se proporcionó el nombre del archivo).

Detallaría las actividades prácticas y recursos que la comunidad ofrece bajo los principios de autogestión y apoyo mutuo (e.g., talleres de reparación, biblioteca social, cocina o comedor popular, huerto comunitario, etc.).

### 4. `blog.html` (Noticias)

(Solo se proporcionó el encabezado).

Funcionaría como un registro de la actividad de la comunidad. Contendría artículos sobre eventos pasados, reflexiones políticas, comunicados o crónicas de la vida diaria en la casa.

### 5. `conciertos_ev.html` (Conciertos y eventos)

Muestra una **tabla organizada** con la agenda de actividades culturales y sociales futuras, detallando el **Tipo de evento, Grupo o artista, Fecha y Género**. Es el principal canal para atraer a la gente a participar en actividades de ocio y cultura.

### 6. `contacto.html` (Sé el cambio)

Contiene un **formulario exhaustivo** para la participación. Solicita datos personales (nombre, email), demográficos (edad, género, comunidad autónoma) y la intención de visita, actuando como un primer filtro para nuevos colaboradores o interesados.

----------

## 🏗️ Decisiones de Diseño Estructural

Las decisiones de diseño se enfocan en la **coherencia**, la **navegación clara** y el uso de **HTML semántico** para estructurar la información.

### 1. Arquitectura Consistente (Boilerplate)

-   **Encabezado y Pie de Página Unificados:** Todos los archivos comparten exactamente el mismo código para el `<header>` (navegación principal) y el `<footer>` (contacto y redes sociales). Esta decisión garantiza una **experiencia de usuario (UX) coherente** y facilita el mantenimiento.
    
-   **Navegación Completa:** El menú principal incluye enlaces a las seis páginas en todo momento, facilitando que el usuario se mueva libremente por todo el sitio.
    

### 2. Uso Semántico de HTML5

El código utiliza etiquetas HTML5 de manera apropiada para definir la estructura del contenido, lo cual es vital para la accesibilidad y el SEO:

-   **`<header>` y `<nav>`:** Para la navegación y el menú.
    
-   **`<main>`:** Para contener el contenido único de cada página.
    
-   **`<section>` y `<article>`:** Para dividir el contenido principal en temas lógicos (ej. en `index.html`, la bienvenida y los principios están en secciones separadas).
    
-   **`<address>`:** Utilizada correctamente en el `<footer>` para contener la información de contacto físico y digital.
    
-   **`<fieldset>` y `<legend>`:** Utilizados en `contacto.html` para agrupar campos relacionados en el formulario, mejorando la estructura lógica.
    

### 3. Diseño de Formulario Detallado

En `contacto.html`, se tomó la decisión de incluir campos sensibles y detallados:

-   El campo de género ofrece una opción abierta ("Otres géneros"), reflejando la **filosofía inclusiva** del proyecto.
    
-   El uso de un campo `<select>` con todas las Comunidades Autónomas de España ayuda a la comunidad a **geolocalizar** a sus interesados.
    

### 4. Organización de Eventos

En `conciertos_ev.html`, se eligió usar la etiqueta **`<table>`**. Esta es una decisión estructural correcta porque el contenido (Eventos, Artista, Fecha, Género) es **información tabular** que se relaciona directamente entre filas y columnas, lo que facilita la comprensión rápida de la agenda.


### CSS


## 🎨 Decisiones de Diseño Visual y Paleta de Colores

Las decisiones de diseño visual para el sitio "Utopía Cotidiana" se centran en proyectar una imagen **seria, orgánica y activista** mediante una paleta de colores fresca y el uso de sombras para destacar elementos clave.

----------

### Paleta de Colores Usada 🟢⚫

La paleta se define por tonos de verde azulado y un contraste de fondo muy claro, utilizando las siguientes variables CSS:

**Color**

**Código Hexadecimal**

**Uso Principal**

**Función en el Diseño**

**Verde Oscuro** (`--color-vede_oscuro`)

`#2F9C95`

Fondo del Menú y Footer, Encabezados de Tablas.

Aporta la base fuerte y la identidad visual principal.

**Verde Claro** (`--color-verde_claro`)

`#40C9A2`

Sombra de Elementos (`.libros`), `hover` de Filas de Tabla.

Funciona como color de **acento**, dando profundidad y _feedback_ interactivo.

**Azul Claro** (`--color-azul_claro`)

`#E5FFFC`

Fondo Global de la Página.

Garantiza la legibilidad al mantener un fondo muy claro.

**Rojo** (`--color-rojo`)

`red`

Botón de Envío (`.enviar`).

Se usa estratégicamente para un **llamado a la acción** urgente y destacado.

**Negro** (`--color-negro`)

`#1b1b1e`

Texto Principal.

Contraste óptimo para el cuerpo del texto.

### Decisiones Estructurales y Visuales Clave 🖼️

1.  **Fondo y Contraste:** El uso de un fondo muy claro (`#E5FFFC`) permite que el contenido y la navegación (en verde oscuro) sobresalgan claramente.
    
2.  **Énfasis en el Contenido (`servicios.html`):** Los elementos clave, como los "Libros" en la sección de servicios, utilizan una **sombra proyectada en verde claro** (`box-shadow: 20px 20px 30px 3px var(--color-verde_claro)`) para destacarse visualmente y dar una sensación de profundidad.
    
3.  **Botón de Acción:** El botón de envío (`.enviar`) es intencionalmente llamativo. Es **circular** (`border-radius: 100%`) y de color **rojo** para asegurar que el usuario lo identifique inmediatamente como la acción final del formulario.
    
4.  **Diseño de Tablas (`conciertos_ev.html`):** Las filas de eventos alternan el color para mejorar la legibilidad, y el estado **`hover`** utiliza el color de acento (`var(--color-verde_claro)`) para una interacción clara.
    

----------

## 🖋️ Tipografías Elegidas

El sitio utiliza una única familia tipográfica importada de Google Fonts:

-   **Tipografía:** **Merriweather**
    
-   **Tipo:** _Serif_ (con remates)
    
-   **Función:** A pesar de ser un proyecto contemporáneo y activista, la elección de una fuente _serif_ confiere al sitio un aire de **seriedad, solidez y contenido sustancial**, siendo una opción popular para facilitar la lectura de bloques de texto grandes (como en un blog o una sección "Quiénes somos").
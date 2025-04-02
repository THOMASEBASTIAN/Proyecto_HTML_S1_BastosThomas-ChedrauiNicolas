## Descripción del Proyecto

El proyecto **Kario** es una experiencia web interactiva que presenta una animación visual utilizando imágenes y transiciones en CSS. A través de un simple pero efectivo diseño, se logra una animación dinámica que presenta un icono animado sobre un fondo con una transición de aparición y desaparición. El propósito de esta página es mostrar un concepto visual atractivo y llamativo con un enfoque en la interactividad a través de la animación CSS.

## Estructura del Proyecto

Este proyecto está compuesto por dos archivos principales:

1.  **index.html** - El archivo principal de la página.
    
2.  **index.css** - El archivo de estilos que controla la presentación y animación de la página.
    

El proyecto también hace uso de fuentes personalizadas y una imagen de fondo para enriquecer la experiencia visual.

## Detalle del Código

### **1. Estructura HTML (`index.html`)**

El archivo HTML contiene una estructura simple con los siguientes elementos clave:

-   **Etiquetas de Meta**:
    
    -   `meta charset="UTF-8"`: Define la codificación de caracteres como UTF-8.
        
    -   `meta name="viewport" content="width=device-width, initial-scale=1.0"`: Asegura que la página se ajuste correctamente en diferentes tamaños de pantalla.
        
    -   `meta http-equiv="refresh" content="2; url=pagina3.html"`: Esta línea establece una redirección automática después de 2 segundos a otra página (`pagina3.html`).
        
-   **Enlace al CSS**:
    
    -   Se enlaza el archivo de estilos `index.css` para aplicar el diseño y las animaciones.
        
-   **Cuerpo de la Página**:
    
    -   Dentro del `<body>`, se encuentra un contenedor `<div class="fondo">`, que incluye una imagen de fondo (`fondo.png`) y un icono animado (`kario sin kairo.svg`).
        

### **2. Estilos CSS (`index.css`)**

El archivo de estilos contiene varias definiciones clave:

-   **Animación (`@keyframes fadeInOut`)**:
    
    -   Se define una animación llamada `fadeInOut` que hace que el icono desaparezca y aparezca en bucle. La animación tiene una duración de 1 segundo y se repite infinitamente.
        
    -   La animación varía la opacidad del elemento de `0` a `1` y luego de vuelta a `0`, creando un efecto de desvanecimiento.

## Estructura de la pagina3

Este proyecto está compuesto por los siguientes archivos:

1.  **index.html** - El archivo HTML principal de la página.
    
2.  **index.css** - El archivo de estilos que controla la apariencia y las animaciones de la página.
    

El diseño incluye imágenes personalizadas, fuentes específicas, y un enfoque en la interactividad a través de CSS.

## Detalle del Código

### **1. Estructura HTML (`index.html`)**

El archivo HTML contiene los siguientes elementos clave:

-   **Etiquetas de Meta**:
    
    -   `meta charset="UTF-8"`: Define la codificación de caracteres como UTF-8.
        
    -   `meta name="viewport" content="width=device-width, initial-scale=1.0"`: Asegura que la página se ajuste correctamente en diferentes tamaños de pantalla.
        
    -   `meta http-equiv="refresh" content="2; url=pagina4.html"`: Establece una redirección automática después de 2 segundos a la página `pagina4.html`.
        
-   **Enlace al CSS**:
    
    -   Se enlaza el archivo de estilos `index.css` para aplicar el diseño y las animaciones.
        
-   **Cuerpo de la Página**:
    
    -   Dentro del `<body>`, se incluye un contenedor `<div class="fondo">` que contiene:
        
        -   Una imagen de fondo (`fondo.png`).
            
        -   Un icono animado (`kario sin kairo.svg`).
            

### **2. Estilos CSS (`index.css`)**

El archivo de estilos contiene varias reglas clave:

-   **Animación (`@keyframes fadeInOut`)**:
    
    -   Se define una animación llamada `fadeInOut` que hace que el icono aparezca y desaparezca en bucle. La animación tiene una duración de 1 segundo y se repite infinitamente. Se utiliza para darle un efecto de visibilidad intermitente al icono.

## Detalle de la pagina4

### **1. Estructura HTML (`pagina4.html`)**

El archivo HTML contiene la siguiente estructura:

-   **Etiquetas Meta**:
    
    -   `meta charset="UTF-8"`: Define la codificación de caracteres como UTF-8.
        
    -   `meta name="viewport" content="width=device-width, initial-scale=1.0"`: Asegura que la página se ajuste correctamente en diferentes tamaños de pantalla.
        
-   **Enlace al CSS**:
    
    -   Se enlaza el archivo de estilos `pagina4.css` para aplicar el diseño y las animaciones.
        
-   **Cuerpo de la Página**:
    
    -   Dentro del `<body>`, se encuentra un contenedor principal `div.fondo`, que incluye un cuadro central (con la clase `rectangulo`) con el siguiente contenido:
        
        -   **Logo**: Un logo dentro de un `div.logomd`.
            
        -   **Texto Principal**: Un texto de bienvenida en el `div.texto1`.
            
        -   **Texto Secundario**: Un mensaje de instrucciones en el `div.pq`.
            
        -   **Campos de Usuario y Contraseña**: Campos de texto dentro de `div.cajita` y `div.cajita2`.
            
        -   **Botón de Ingreso**: Un botón de login con la clase `boton`, que redirige a `pagina5.html`.
            
        -   **Texto de asistencia**: Un mensaje de contacto en caso de problemas, dentro del `div.texitco`.
            

### **2. Estilos CSS (`pagina4.css`)**

El archivo de estilos contiene las siguientes reglas clave:

-   **Estilos Globales**:
    
    -   El cuerpo de la página tiene un fondo negro, y el contenido se centra tanto horizontal como verticalmente utilizando `flexbox`. También se establece una altura de vista completa con `height: 100vh`.

## Detalle de la pagina5

### **1. Estructura HTML (`pagina5.html`)**

El archivo HTML contiene la siguiente estructura:

-   **Etiquetas Meta**:
    
    -   `meta charset="UTF-8"`: Define la codificación de caracteres como UTF-8.
        
    -   `meta name="viewport" content="width=device-width, initial-scale=1.0"`: Asegura que la página se ajuste correctamente en diferentes tamaños de pantalla.
        
    -   `meta http-equiv="refresh" content="2; url=pagina6.html"`: Redirige automáticamente a `pagina6.html` después de 2 segundos.
        
-   **Enlace al CSS**:
    
    -   Se enlaza el archivo de estilos `pagina5.css` para aplicar el diseño y las animaciones.
        
-   **Cuerpo de la Página**:
    
    -   Dentro del `<body>`, se encuentra un contenedor principal `div.fondo`, que incluye un cuadro central (con la clase `rectangulo`) con el siguiente contenido:
        
        -   **Logo**: Un logo dentro de un `div.logomd`.
            
        -   **Texto Principal**: Un texto de bienvenida dentro de `div.texto1`.
            
        -   **Foto de Perfil**: Una imagen de perfil dentro del `div.fotoperfil`.
            
        -   **Nombre de Usuario**: El nombre del usuario dentro de `div.texto2`.
            
        -   **Rol del Usuario**: El rol del usuario dentro de `div.texto3`.
            

### **2. Estilos CSS (`pagina5.css`)**

El archivo de estilos contiene las siguientes reglas clave:

-   **Estilos Globales**:
    
    -   El cuerpo de la página tiene un fondo negro.

## Detalle de la pagina7

El siguiente código define una página web que presenta un "Panel de Indicadores", utilizando HTML y CSS. En esta sección, explicaremos la estructura y el funcionamiento de los componentes clave del código.

### HTML

#### Estructura General

El archivo HTML es el contenido principal que define la estructura de la página. Este código comienza con la etiqueta `<!DOCTYPE html>` y está compuesto por varias secciones:

1.  **Cabecera (`<header>`)**: Incluye diversos elementos visuales como íconos de imagen para diversas acciones, como aumentar, disminuir, notificaciones, etc.
    
2.  **Título y Texto Introductorio**: Dentro del `<body>`, se incluye un título principal con la clase `titulo` y una breve descripción dentro de un párrafo con la clase `texto`.
    
3.  **Tabla de Indicadores**: El contenedor principal de la tabla de indicadores está dentro de la clase `titulos`, que incluye las cabeceras de las columnas para cada indicador: Indicador, Descripción, Categoría, Fecha de Inicio, Fecha de Terminación, Fórmula, Frecuencia, Cumplimiento y Área.
    
4.  **Bloques de Datos**: Cada bloque de datos es representado dentro de clases como `block1`, `block2`, etc., donde cada celda dentro de los bloques contiene la información sobre el indicador correspondiente.
    
5.  **Progreso**: La visualización del progreso de cada indicador se muestra a través de la etiqueta `<progress>`, en conjunto con una clase de barra de progreso (`progress-bar`, `progress-bar2`, etc.). Las barras de progreso se ajustan con un valor específico para reflejar el estado del indicador.
    
6.  **Enlaces de Acción**: Al final del código, se proporcionan enlaces de acción, como "añadir", "refrescar", "eliminar", "reportar" y "ayuda", que redirigen a otras páginas de la aplicación.
    

#### Formulario

Se incluye un formulario vacío para agregar un nuevo indicador con el ID `Formulario`, y un elemento `select` que ofrece opciones como "Ajustes" y "Equipos".

### CSS

#### Estilos Generales

El archivo CSS proporciona estilos para la apariencia visual de la página. A continuación, se detallan algunos aspectos clave:

1.  **Tipografía**: Se utiliza la fuente personalizada "MYRIADPRO-REGULAR" a través de `@font-face`, y la mayoría de los elementos en la página usan la fuente regular definida.
    
2.  **Cabecera**: El `header` tiene un fondo con bordes y los íconos dentro de él están posicionados de manera absoluta para alinearlos a la derecha e izquierda de la pantalla.
    
3.  **Barra de Progreso**: Cada barra de progreso se muestra en forma de círculo con un fondo radiante que cambia de color dependiendo del estado del indicador. Las barras tienen diferentes colores que indican el nivel de progreso (rojo, verde, amarillo, etc.).
    
4.  **Bloques de Indicadores**: Cada bloque de indicador tiene un borde redondeado y un fondo gris claro. Los elementos dentro de estos bloques están dispuestos en una cuadrícula para alinearse correctamente en cada columna.
    
5.  **Enlaces**: Los enlaces, como "añadir", "refrescar", "eliminar", etc., tienen un efecto de subrayado cuando el usuario pasa el cursor sobre ellos, mediante una transición que aumenta el ancho del subrayado.
    
6.  **Rayitas**: Se repiten varias imágenes de "rayitas" al final de la página, ubicadas en la parte inferior, para decorar el diseño.
    

### Funcionalidad

El código de la página no contiene scripts JavaScript, pero se puede agregar fácilmente para agregar funcionalidades interactivas, como enviar un formulario, refrescar los datos o eliminar indicadores. El comportamiento visual se maneja completamente con CSS.

# Detalle de la apgina "ayuda"

El siguiente código implementa una página web con una interfaz de ayuda que contiene varias secciones interactivas. A continuación se describe la estructura y el funcionamiento del código:

## HTML

1.  **Estructura general**:  
    El código HTML define la estructura básica de una página web utilizando etiquetas comunes como `<html>`, `<head>`, y `<body>`. La página está diseñada para ofrecer un menú de navegación con enlaces a diferentes funcionalidades, como "Añadir", "Eliminar", "Refrescar", "Reportar" y "Ayuda".
    
2.  **Enlaces de navegación**:  
    Se encuentran cinco enlaces principales que redirigen a distintas páginas:
    
    -   "Añadir"
        
    -   "Refrescar"
        
    -   "Eliminar"
        
    -   "Reportar"
        
    -   "Ayuda"
        
3.  **Encabezado (Header)**:  
    El encabezado contiene una serie de iconos representados por imágenes, cada uno con diferentes funciones o significados. Estos iconos se encuentran en diferentes posiciones dentro del contenedor `<header>`. Además, algunos de estos iconos redirigen a otras páginas, como el logo de la aplicación.
    
4.  **Formulario de búsqueda**:  
    Hay un campo de texto de búsqueda (`<input class="busqueda" type="text">`) que permite a los usuarios escribir consultas relacionadas con la ayuda que necesitan. Junto a este campo se encuentra un botón de búsqueda (`<input class="boton" type="submit" value="Buscar">`).
    
5.  **Cuadros informativos**:  
    La página presenta varios cuadros con información sobre diferentes funciones de la aplicación, como "Añadir", "Eliminar", "Refrescar" y "Reportar". Cada cuadro tiene una imagen asociada y un breve texto descriptivo.
    

## CSS

1.  **Estilos generales**:
    
    -   Se define la fuente "regular" con `@font-face` que apunta a un archivo OTF.
        
    -   Se aplica un fondo blanco a la página (`background-color: #ffff`), y los márgenes se eliminan con `margin: 0`.
        
2.  **Estilo del encabezado**:  
    El encabezado tiene un borde negro y una altura fija de 100px. Los iconos dentro del encabezado se posicionan de manera absoluta para que se ubiquen en lugares específicos de la página. Se utilizan imágenes con distintos tamaños y posiciones para crear una barra de navegación funcional.
    
3.  **Enlaces de navegación**:  
    Los enlaces de navegación se posicionan absolutamente y se estilizan con una fuente personalizada ("regular"). Además, se les ha añadido un efecto de transición para que al pasar el ratón sobre ellos, aparezca una línea de color naranja debajo del texto.
    
4.  **Cuadros de contenido**:  
    Cada cuadro que describe una funcionalidad tiene un fondo blanco y un tamaño fijo. Los cuadros están posicionados de manera absoluta para que se alineen horizontalmente en la página. Además, cada cuadro tiene una imagen en la parte superior y un título junto con una breve descripción de la función.
    
5.  **Icono final**:  
    Al final de la página se coloca un icono adicional, que es una imagen de la aplicación. Este icono se posiciona absolutamente en la parte inferior central de la página.
    

## Funcionalidad del código

-   **Interactividad de enlaces**: Los enlaces en el menú de navegación redirigen a diferentes páginas dentro del sitio web, lo que permite al usuario navegar entre distintas secciones.
    
-   **Efectos visuales**: Los elementos interactivos, como los enlaces de navegación, tienen un efecto visual cuando se pasa el ratón sobre ellos, gracias al uso de pseudo-clases como `:hover` y `::after` para crear transiciones suaves.

# Detalle del código

Este proyecto contiene una página web que permite visualizar un conjunto de indicadores, con detalles sobre su descripción, categoría, fecha de inicio, fecha de terminación, fórmula, frecuencia, cumplimiento y área. Cada indicador tiene un estilo de presentación en bloques, con barras de progreso visuales que indican el avance de cada uno.

## HTML

La estructura del archivo HTML define la organización y el contenido de la página. A continuación se describen las secciones clave:

-   **Header**: Contiene imágenes de iconos, como el logo, una campanita de notificación, ajustes, y opciones para interactuar con la página.
    
-   **Indicadores**: Se presenta un conjunto de bloques (`block1`, `block2`, `block3`, etc.), cada uno con información detallada sobre los indicadores, como nombre, descripción, categoría, fechas, fórmula, frecuencia, cumplimiento, y el área correspondiente.
    
-   **Barras de progreso**: Cada bloque tiene una barra de progreso que indica el avance de la actividad correspondiente a cada indicador.
    
-   **Enlaces de navegación**: Existen varios enlaces de navegación, como "añadir", "refrescar", "eliminar", "reportar" y "ayuda", para permitir al usuario interactuar con la página y realizar acciones específicas.
    

## CSS

El archivo CSS define el estilo visual de la página. Se incluye el uso de fuentes, diseño de contenedores, y estilos interactivos.

### Reglas clave del CSS:

-   **Estilos globales**:
    
    -   La página utiliza una fuente personalizada definida con `@font-face`, apuntando a un archivo `.OTF`.
        
    -   El fondo de la página es blanco (`background-color: #ffff`), sin repetirse y con tamaño ajustado a la pantalla.
        
-   **Encabezado (`header`)**:
    
    -   Un `header` fijo en la parte superior de la página con varios iconos alineados en posiciones específicas usando la propiedad `position: relative`.
        
-   **Estilo de los bloques**:
    
    -   Los indicadores están presentados en bloques organizados en una cuadrícula de 9 columnas (`grid-template-columns: repeat(9, auto)`).
        
    -   Cada bloque tiene bordes redondeados y se posicionan con un pequeño margen entre ellos. Los bloques se ajustan en altura y tamaño.
        
-   **Barras de progreso**:
    
    -   Las barras de progreso están diseñadas con un estilo circular usando `conic-gradient` para representar el avance de cada indicador. Los valores de las barras son estilizados para representar porcentajes de avance.
        
-   **Interactividad**:
    
    -   Los enlaces tienen un efecto de transición de color al pasar el cursor sobre ellos (`hover`), donde se anima una línea inferior (`::after`) que se extiende para resaltar el enlace.
        

## Elementos visuales

-   **Iconos y logo**:
    
    -   Los iconos de la interfaz (como la campanita, el logo, los ajustes, etc.) se posicionan en lugares específicos del `header` utilizando `position: relative` y `top`, `left` para su ubicación exacta.
        
-   **Botones de acción**:
    
    -   Los botones de acción como "añadir", "refrescar", "eliminar", "reportar", y "ayuda" tienen un estilo único y se posicionan de manera relativa con respecto a la página, permitiendo la interacción del usuario.
        
-   **Barras de progreso**:
    
    -   Las barras de progreso están diseñadas en forma circular y cambian de color dependiendo del progreso, proporcionando una representación visual atractiva del avance de cada indicador.
        

## Estructura de la pagina "eliminar"

-   **HTML**: La estructura HTML contiene las secciones mencionadas, con cada indicador colocado en su propio bloque dentro de un contenedor de estilo grid.
    
-   **CSS**: Se encargan de definir los estilos visuales de cada elemento, desde los iconos y la disposición del encabezado hasta las barras de progreso.
    

Este diseño proporciona una experiencia de usuario interactiva y visualmente atractiva para monitorear el progreso de varios indicadores a lo largo del tiempo.

### Dependencias

-   **Fuente personalizada**: Se utiliza una fuente personalizada (`MYRIADPRO-REGULAR.OTF`), que debe estar disponible en la ruta especificada.

# Detalle de la pagina "refrescar"

Este archivo HTML y su respectiva hoja de estilo CSS están diseñados para una interfaz de usuario interactiva para una aplicación web con varias secciones y controles visuales. A continuación, se detallan los componentes clave del código:

## HTML (Estructura de la página)

La estructura HTML se compone de varios bloques que contienen imágenes, enlaces y elementos de texto. Aquí se describen los elementos clave:

### 1. **Encabezado (header)**

El encabezado contiene varias imágenes que actúan como iconos de navegación o controles para la interfaz. Estas imágenes incluyen:

-   `mas`, `menos`, `campanita`, `pedro`, `logo`, `ajustes`, `interrogacion`, `basura`, `refrescar` Cada imagen está posicionada de manera relativa con el uso de CSS para un diseño específico.
    

### 2. **Navegación (links)**

Se han creado enlaces con clases `link1`, `link2`, `link3`, `link4` y `link5`, que permiten la navegación entre diferentes páginas (`añadir`, `refrescar`, `eliminar`, `reportar`, `ayuda`). Cada uno de estos enlaces tiene un estilo hover para resaltar al pasar el cursor por encima.

### 3. **Bloques de información (block1, block2, block3)**

Estos bloques están diseñados con un diseño de cuadrícula (grid) para mostrar información organizada en columnas:

-   Cada bloque contiene información como nombre del proyecto, descripción, estatus, fechas y otros detalles relevantes.
    
-   Cada bloque también incluye una barra de progreso que refleja el estado de cada elemento con valores visuales.
    

### 4. **Botón de recuperación (Recuperar)**

Un botón prominente con la clase `.boton` permite al usuario realizar una acción, como recuperar un proyecto. El botón tiene un estilo visual destacado con un fondo naranja.

### 5. **Imágenes**

El código incluye imágenes de íconos, tales como el logo (`kairo.png`) y otros iconos como el de la basura, ajustes, y campanita. Estas imágenes son utilizadas para mejorar la interfaz y hacerla más interactiva.

## CSS (Estilos y Diseño)

### 1. **Estilos Globales**

El fondo de la página está configurado como blanco y sin repetirse, y el margen se establece a cero para asegurar un diseño limpio. La fuente utilizada en la página es "MYRIADPRO-REGULAR.OTF".

### 2. **Estilo del encabezado**

El encabezado tiene una altura de 100px y contiene múltiples imágenes que se posicionan con coordenadas relativas utilizando propiedades como `top`, `left`, `width` y `height`.

### 3. **Estilo de enlaces**

Los enlaces tienen un estilo básico de texto con color negro y sin subrayado. Cuando el usuario pasa el cursor sobre un enlace, se añade una animación que cambia el ancho de una línea debajo del texto (`::after`).

### 4. **Bloques de información (block1, block2, block3)**

Los bloques de información están definidos con un diseño de cuadrícula utilizando `grid-template-columns` para crear un diseño de 9 columnas. Cada bloque tiene bordes redondeados y un espaciado entre las celdas. Las celdas contienen textos con la clase `.cell` y se ajustan al contenido.

### 5. **Barra de progreso**

Las barras de progreso son representadas con círculos que tienen un fondo en forma de gradiente cónico, reflejando diferentes porcentajes. Estos círculos se posicionan dentro de cada bloque de información y muestran el porcentaje de progreso de cada proyecto.

### 6. **Botón de recuperación**

El botón tiene un fondo naranja, texto en blanco, bordes redondeados y un tamaño considerable para destacar. Está centrado en la página y se coloca a una posición específica con `top` y `left`.

## Funcionamiento de la página

Al visitar esta página, el usuario puede ver los proyectos listados en los bloques `block1`, `block2`, `block3`, con su información detallada y barras de progreso visuales. Además, puede navegar a diferentes secciones de la aplicación utilizando los enlaces en la parte superior de la página.

## Detalle de la pagina "reportar"

Este archivo HTML contiene la estructura de una página para reportar problemas, que incluye secciones para categorizar los errores utilizando emojis.

### Estructura del archivo

#### Cabecera (`<header>`)

El encabezado incluye varios íconos como:

-   Un ícono de "más", "menos", "campanita", "ajustes", "interrogación", "basura" y "recargar" que representan distintas funciones en la página.
    
-   Un ícono de perfil de usuario, y el logotipo de la página.
    

#### Navegación

En la parte inferior del encabezado, se encuentran enlaces para navegar a las diferentes secciones de la aplicación:

-   **Añadir**
    
-   **Refrescar**
    
-   **Eliminar**
    
-   **Reportar**
    
-   **Ayuda**
    

#### Contenido Principal

-   **Título**: La página tiene como título "Guía de emojis para reportar problemas", que se presenta en una fuente personalizada.
    
-   **Enunciado**: Un texto que explica cómo usar los emojis para identificar y reportar problemas en la página.
    

#### Sección para clasificar los problemas

Los problemas se clasifican mediante bloques que muestran emojis asociados con diferentes tipos de problemas en la página. Cada bloque tiene:

-   Un emoji de categoría.
    
-   Una breve descripción del problema.
    

Estos bloques están organizados en una cuadrícula usando CSS Grid, con un espacio de separación entre ellos.

-   **Bloque 1**: Problema de tipo "Bug/Error" (🔴🪲).
    
-   **Bloque 2**: Problema de "Lentitud" (🔵 🐢).
    
-   **Bloque 3**: Problema de "Enlace roto" (🟢 🔗).
    
-   **Bloque 4**: Problema de "Acceso" (🟠 📵).
    
-   **Bloque 5**: Problema con el "Chat" (⚪ 💬).
    
-   **Bloque 6**: Problema de "Diseño" (⚫ 🎨).
    
-   **Bloque 7**: Problema en "Formularios" (🟣 📩).
    

#### Pie de página

Un ícono de la marca de la página se muestra al final del contenido.

### Estilos CSS

#### Fuentes

-   Se definen dos tipos de fuentes mediante `@font-face`, **regular** y **light**, que se utilizan en diferentes secciones de la página.
    

#### Diseño y Estilo de la Página

-   El fondo de la página es blanco y los íconos de la barra superior tienen un posicionamiento absoluto para ubicarse en lugares específicos.
    
-   La estructura principal de la página utiliza un diseño de cuadrícula (CSS Grid) para organizar las categorías de problemas.
    
-   Cada categoría se presenta en un bloque con un fondo ligeramente gris y bordes redondeados.
    
-   Los enlaces en la parte superior tienen un efecto visual de subrayado al pasar el cursor sobre ellos.
    

#### Detalles Específicos de los Bloques

-   **CSS para los bloques**: Se utiliza `grid-template-columns` para organizar los bloques en una cuadrícula con 3 columnas.
    
-   **Emojis**: Los emojis son utilizados para clasificar los problemas, ayudando a los usuarios a identificar rápidamente el tipo de error.
    

#### Iconos y Funcionalidad de Navegación

-   Las imágenes en la barra de navegación (como el icono de "más", "menos", "ajustes", etc.) se posicionan con un `position: relative` y se ajustan a la página.
    

### Archivos Relacionados

-   **reportar.css**: Es el archivo de estilos asociado a esta página, que contiene la mayor parte del diseño y el estilo de los elementos HTML.

## Detalle de la pagina "Sing-Up"

Este archivo HTML define una página de registro con un diseño de barra de navegación en la parte superior, que incluye imágenes de íconos para diferentes funcionalidades. Además, contiene un formulario para ingresar datos de usuario.

### Estructura del archivo

#### Cabecera (`<header>`)

La cabecera incluye varios íconos:

-   Un ícono de "más", "menos", "campanita", "ajustes", "interrogación", "basura" y "recargar" que representan distintas funcionalidades en la página.
    
-   Un ícono de perfil de usuario y el logotipo de la página.
    

#### Navegación

Se incluyen enlaces a distintas secciones de la aplicación:

-   **Añadir**
    
-   **Refrescar**
    
-   **Eliminar**
    
-   **Reportar**
    
-   **Ayuda**
    

#### Contenido Principal

El contenido principal está dividido en una caja central que contiene:

-   Un encabezado "Añadir".
    
-   Dos secciones de entrada de datos para el nombre y correo electrónico.
    
-   Un botón de tipo "Add" para completar el registro.
    

#### Estilos CSS

#### Fuentes

-   Se define una fuente personalizada `regular` mediante `@font-face`.
    

#### Diseño y Estilo de la Página

-   El fondo de la página es de color gris claro y las imágenes de la cabecera están posicionadas usando `position: relative` para colocarlas en posiciones específicas.
    
-   El formulario y otros elementos tienen un diseño centrado en la página, con bordes redondeados y sombras para dar un efecto visual atractivo.
    

#### Caja de Contenido

La caja que contiene el formulario tiene un estilo con un borde y sombra, lo que resalta los campos de entrada y botones.

-   **Caja principal**: La caja tiene un fondo blanco, bordes redondeados y una sombra para darle un efecto de profundidad.
    
-   **Campos de entrada**: Los campos para ingresar el nombre y el correo tienen un fondo naranja y bordes redondeados.
    
-   **Botón "Add"**: El botón tiene un efecto de transición y escala al hacer hover, lo que mejora la interacción del usuario.
    

#### Detalles Específicos de los Elementos

-   **CSS para los botones**: El botón tiene una animación que cambia su tamaño y color cuando el usuario pasa el cursor sobre él.
    
-   **Estilo de los enlaces**: Los enlaces en la parte superior están estilizados para ser fácilmente legibles y accesibles.
    

#### Funcionalidades de Interacción

-   El botón "Add" tiene una animación que lo hace aumentar de tamaño y cambiar de color al pasar el cursor sobre él, gracias a la propiedad `transform: scale` y `transition` en CSS.
    

### Archivos Relacionados

-   **Sing-up.css**: El archivo de estilos asociado que contiene todas las reglas de diseño y el estilo visual de los elementos HTML definidos en este archivo.

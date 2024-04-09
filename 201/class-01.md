# LECTURA CLASE 1
- El siguiente contenido es importante para este modulo ya que es una introduccion breve a lo que ya hemos visto en el code 102 y nos permite recoradar los conceptos brindados para iniciar este modulo Code 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## PRIMEROS PASOS
  
  ***1.Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.***

  - HTTP viaja, datos al volar, de un extremo al otro, sin descansar.
    Servidor y cliente, en su enlace sin par, la web se expande, sin cesar.

  ***2.Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.***

  * HTML (HyperText Markup Language):
    - El navegador interpreta el HTML para estructurar la página web.
    - Lee las etiquetas y sus atributos para determinar cómo organizar y mostrar el contenido.
    - Construye el DOM (Document Object Model), una representación en memoria de la estructura de la página.

  * CSS (Cascading Style Sheets):
    - El navegador analiza el CSS para dar estilo al contenido HTML.
    - Aplica las reglas de estilo definidas en el CSS al DOM, determinando cómo se verán los elementos en la página.
    - Puede haber reglas de estilo en archivos externos (archivos .css) o incrustadas directamente en el HTML.

  * JavaScript (JS):
    - El navegador interpreta y ejecuta el código JavaScript.
    - Puede modificar dinámicamente el contenido HTML (a través del DOM), el estilo CSS y el comportamiento de la página.
    - Interactúa con eventos del usuario y de la página para crear interactividad y funcionalidad dinámica.
      
  ***3.¿Cómo puedes encontrar imágenes para agregar a una página web?***

  - Bancos de imágenes gratuitos: Unsplash, Pexels, Pixabay.
  - Búsqueda en motores de búsqueda: Google Images, Bing Images.
  - Crear tus propias imágenes: Arte o fotografía.
  - Contratar a profesionales: Fotógrafos o diseñadores.

  ***4.¿Cómo creas una “ `String` “ en comparación con un “ `Number` “ en Javascript?***

  ```js
  let miCadena = "Hola mundo";
  ```  

 ```js
  let miCadena = "Hola mundo";
  ```  

  ***5.¿Qué es una “ `Variable` “ y por qué son importantes en JavaScript?***

  - Una variable en JavaScript es un contenedor para almacenar datos. Estos datos pueden ser valores de diferentes tipos, como números, cadenas, objetos, etc. En JavaScript, las variables se definen utilizando la palabra clave “ `let` “,“ `const` “ o “ `var` “, seguida por un nombre descriptivo. 
  
  #### Enlaces de Fuentes

  - [Primeros Pasos](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web)

  - [Como Funciona la Web](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

  - [La Apariencia de tu Sitio Web](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

  - [Fundamentos de JavaScript](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## INTRODUCCION A HTML

  ***1.¿Qué es un atributo en HTML?***

  - Un atributo en HTML es una propiedad que se añade a una etiqueta para proporcionar información adicional sobre el elemento, como su apariencia o comportamiento.

  ***2.Describe la anatomía de un elemento en HTML.***

  * La anatomía de un elemento HTML consta de varias partes:

    - Etiqueta de apertura (< >): Es el punto de partida del elemento y define su tipo y comportamiento.

    - Contenido: Es el contenido del elemento, como texto, otros elementos HTML, o ambos.

    - Etiqueta de cierre (</ >): Es el final del elemento y sirve para indicar dónde termina su contenido.

    - Atributos: Son propiedades que proporcionan información adicional sobre el elemento, como el color, tamaño o enlace. Se definen dentro de la etiqueta de apertura y se componen de un nombre y un valor.
      
  ***3.¿Cuál es la diferencia entre las etiquetas “ `<article>` “ y “ `<section>` “?***

  * La diferencia principal entre las etiquetas `<article>` y `<section>` en HTML radica en su propósito y semántica:

    - `<article>` se usa para contenido independiente y completo, como artículos de blog.

    - `<section>` se usa para agrupar contenido relacionado temáticamente, como capítulos de una página.

  ***4.¿Qué elementos se incluyen en una página web “típica”?***

  * Una página web típica puede incluir una variedad de elementos, dependiendo de su propósito y contenido específicos. Sin embargo, algunos elementos comunes que se encuentran en muchas páginas web incluyen:

    - Encabezado (Header)
    - Barra de navegación (Navigation Bar)
    - Contenido Principal (Main Content)
    - Barra lateral (Sidebar) - opcional
    - Pie de página (Footer)
    - Formularios (Forms)
    - Enlaces (Links)
    - Imágenes (Images)
    - Archivos JavaScript y CSS

  ***5.¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?***

  - Los metadatos, como el título de la página y la descripción, son clave para el SEO. Ayudan a los motores de búsqueda a entender el contenido y mejorar la visibilidad de la página en los resultados de búsqueda. Es importante optimizar estos metadatos con palabras clave relevantes para obtener mejores resultados en el posicionamiento.

  ***6.¿Cómo se utliza la etiqueta “ `<meta>` “ en HTML cuando se quiere especificar metadatos?***

  - La etiqueta `<meta>` se utiliza en HTML para especificar metadatos, como el conjunto de caracteres, la descripción de la página, palabras clave, autor, etc. Se coloca dentro de la sección `<head>` del documento HTML.

  #### Enlaces de Fuentes

  - [Primeros pasos con HTML](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web)

  - [Estructura Web y Documentacion](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

  - [Metadatos en HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

## MISCELANEA

  ### ¿Como empiezo a diseñar mi sitio Web?

   ***1.¿Cuál es el primer paso para diseñar una página web?***

  - El primer paso para diseñar una página web es definir su propósito y audiencia objetivo. Esto implica comprender qué tipo de contenido se presentará en la página, qué acciones se espera que realicen los usuarios y quiénes son esos usuarios.

   ***2.¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?***

  - La pregunta más importante que se debe responder al diseñar una página web es:

    *"¿Cuál es el propósito de la página y quiénes son los usuarios objetivo?"*
      
  #### Enlaces de Fuentes

  - [¿Como empiezo a diseñar mi sitio Web?](https://developer.mozilla.org/es/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

  ### Semantica

   ***1.¿Por qué se debe utilizar un elemento “ `<h1>` “ en vez de un “ `<span>` “ para mostrar un título de primer nivel?***

  - Utilizar un elemento `<h1>` en lugar de un `<span>` para mostrar un título de primer nivel proporciona significado semántico claro, mejora el SEO, facilita la accesibilidad y mantiene la consistencia en la estructura del contenido HTML.

   ***2.¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?***

  * Utilizar etiquetas semánticas en HTML mejora la accesibilidad, el SEO, la legibilidad del código, la usabilidad y promueve estándares de desarrollo web sólidos:

      - Accesibilidad mejorada: Facilitan la comprensión del contenido para lectores de pantalla y dispositivos de asistencia.

      - SEO mejorado: Ayudan a los motores de búsqueda a entender y clasificar mejor el contenido de la página.

      - Legibilidad y mantenimiento del código: Hacen que el código HTML sea más comprensible y fácil de mantener para los desarrolladores.

      - Mejora de la usabilidad: Ayudan a los usuarios a entender la estructura y jerarquía del contenido.

      - Consistencia y estándares: Promueven prácticas de desarrollo web consistentes y siguen los estándares de HTML.

  #### Enlaces de Fuentes

  - [Semantica](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

  ### ¿Que es JavaScript?

   ***1.Describe 2 cosas que requieran de JavaScript en el navegador.***

  * Dos ejemplos que requieren JavaScript en el navegador son:

      - Validación de formularios: Verificar datos ingresados por usuarios en tiempo real.
      - Interactividad de la interfaz de usuario: Crear elementos que responden a acciones del usuario, como animaciones y actualización de contenido sin recargar la página.

   ***2.¿Cómo se puede añadir JavaScript a un documento en HTML?***

  * Puedes añadir JavaScript a un documento HTML de tres formas principales:

      - Incrustado directamente: Insertando código JavaScript entre las etiquetas `<script>` dentro del cuerpo del documento.
      - Archivo externo: Enlazando un archivo JavaScript externo utilizando la etiqueta `<script>` en el encabezado del documento.
      - Eventos del DOM: Utilizando atributos de eventos HTML para llamar a funciones JavaScript directamente desde elementos HTML, como botones o enlaces.

#### Enlaces de Fuentes

  - [¿Que es JavaScript?](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

## COSAS DE LAS QUE QUIERO SABER MAS

* Me gustaria saber mas sobre :
  - Responsive web disign, sitios que se adapten a diferentes dispositivos
  - optimizacion de rendimiento, velicidad y eficiencia de sitios web
  - seguridad web
  - Bases de dato, SQL - NoSQL
  - Arquitectura de aplicaciones web
  - Pruebas y depuracion, problemas de aplicaciones web.

  ### Autor
  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`
  ###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chatgpt)*

  ### Creacion
  - Jueves 09 de Abril del 2024.

Enlace de este contenido [class-01](https://omartpiza.github.io/reading-notes/201/class-01)
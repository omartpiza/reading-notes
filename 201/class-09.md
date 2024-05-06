# LECTURA CLASE 9

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## FORMULARIOS EN HTML
  
***1.¿Por qué los formularios son tan importantes en el desarrollo web?***

- Los formularios son importantes en el desarrollo web porque permiten la interacción con los usuarios, la recolección de datos, la personalización de la experiencia del usuario y la generación de leads.

***2.Al diseñar un formulario, ¿cuáles son algunas de las cosas más importantes a tener en cuenta sobre la experiencia de usuario?***

- Simplicidad: Mantén el formulario simple y fácil de entender para evitar abrumar a los usuarios.

- Claridad: Utiliza etiquetas descriptivas y mensajes de ayuda claros para guiar a los usuarios a través del proceso.

- Organización lógica: Agrupa campos relacionados y organiza el formulario de manera lógica para facilitar su navegación.

- Validación en tiempo real: Proporciona retroalimentación inmediata sobre los errores de entrada y validación para ayudar a los usuarios a corregir problemas fácilmente.

- Adaptabilidad: Diseña el formulario para que sea accesible y usable en diferentes dispositivos y tamaños de pantalla.

- Facilidad de entrada: Minimiza la cantidad de campos requeridos y utiliza controles de entrada adecuados (por ejemplo, casillas de verificación, botones de opción) para facilitar la entrada de datos.

- Seguridad y privacidad: Asegúrate de que los usuarios se sientan seguros al proporcionar su información personal, y comunica claramente las políticas de privacidad y seguridad del sitio.

***3.Enumera 5 elementos de los formularios y explica su importancia.***

1. Etiquetas (labels): Son descripciones de campos que ayudan a los usuarios a entender qué información se espera en cada campo del formulario, siendo esenciales para la accesibilidad.

2. Campos de entrada (input fields): Permiten a los usuarios ingresar datos, siendo importante ofrecer el tipo correcto de campo para facilitar la entrada de información.

3. Botones de envío (submit buttons): Permiten a los usuarios enviar el formulario una vez que esté completo, siendo clave para la funcionalidad del formulario y deben ser claramente visibles y etiquetados.

4. Mensajes de validación: Informan a los usuarios sobre errores o problemas al completar el formulario, proporcionando retroalimentación instantánea y ayudando a corregir errores fácilmente.

5. Mensajes de confirmación: Después de enviar el formulario con éxito, aseguran a los usuarios que su acción se ha completado correctamente, cerrando el ciclo de retroalimentación y proporcionando una experiencia satisfactoria.

#### Enlaces de Fuentes

- [Formularios en HTML](https://developer.mozilla.org/es/docs/Learn/Forms)
- [Mi primer formulario HTML](https://developer.mozilla.org/es/docs/Learn/Forms/Your_first_form)
- [Cómo estructurar un formulario HTML](https://developer.mozilla.org/es/docs/Learn/Forms/How_to_structure_a_web_form)

## APRENDE JS

***1.¿Cómo describirías los event a un amigo sin conocimiento técnico?***

- Los eventos en términos sencillos son como señales que un programa envía cuando algo importante sucede, como cuando alguien hace clic en un botón en una página web o cuando se carga una imagen. Imagina que estás jugando un juego y cada vez que haces algo importante, como ganar puntos o pasar de nivel, el juego te muestra una notificación o una animación para informarte sobre lo que sucedió. Los eventos funcionan de manera similar en programas y páginas web: activan ciertas acciones cuando ocurren ciertos eventos, lo que permite que las cosas sucedan de forma dinámica y en respuesta a las acciones del usuario.

***2.Al utilizar el método `addEventListener()`, ¿cuáles son los 2 arguments que debes proporcionar?***


1. El primer argumento es el tipo de evento que estás escuchando, como "click", "mouseover", "keydown", etc. Este argumento especifica qué tipo de acción activará la función que estás pasando.

2. El segundo argumento es la función que se ejecutará cuando ocurra el evento especificado. Esta función se llama el "manejador de eventos" y contiene el código que deseas que se ejecute en respuesta al evento.

    - Por ejemplo, si quieres ejecutar una función llamada mostrarMensaje() cuando se haga clic en un botón, usarías addEventListener() de esta manera:

        ```js
         boton.addEventListener("click", mostrarMensaje);
        ```

    - Donde "click" es el tipo de evento y mostrarMensaje es la función que se ejecutará cuando ocurra el evento de clic en el botón.

***3.Describe el objeto event. ¿Por qué el target dentro del objeto event es útil?***

- El objeto event contiene información sobre el evento que ocurrió en la página web. El atributo target dentro de event es útil porque indica qué elemento del DOM causó el evento, lo que te permite actuar específicamente sobre ese elemento en tu código.

***4.¿Cuál es la diferencia entre event bubbling y event capturing?***

- La diferencia entre event bubbling y event capturing radica en el orden en que se propagan los eventos a través de los elementos del DOM durante la fase de captura y burbujeo:

    - Event capturing (captura de eventos): Durante esta fase, el evento se captura desde el elemento superior (ancestro) hasta el elemento objetivo (descendiente). Es decir, el evento se procesa primero en el elemento más externo y luego se propaga hacia adentro, descendiendo en la jerarquía del DOM hasta llegar al elemento objetivo.

    - Event bubbling (burbujeo de eventos): En cambio, durante esta fase, el evento se propaga desde el elemento objetivo hacia arriba, desde el elemento más interno hasta el más externo en la jerarquía del DOM. Después de que se haya completado la fase de captura, el evento se propaga hacia arriba a través de los elementos padres hasta llegar al elemento superior.


#### Enlaces de Fuentes

- [Aprende JS](https://developer.mozilla.org/es/docs/Learn/JavaScript)
- [Introducción a los Eventos.](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/Events)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [Tipos de input de HTML5](https://developer.mozilla.org/es/docs/Learn/Forms/HTML5_input_types)
- [Referencia de Eventos](https://developer.mozilla.org/es/docs/Web/Events)

## COSAS DE LAS QUE QUIERO SABER MAS

- Ejemplos de diseños comunes con Flexbox, Ver ejemplos prácticos de cómo Flexbox se usa en diseños comunes, como columnas, navegación y tarjetas.
- Comparación con otras técnicas de diseño, Entender las diferencias entre Flexbox, Grid Layout y floats, y cuándo usar cada uno.
- Problemas y soluciones con Flexbox, Identificar desafíos comunes al usar Flexbox y cómo solucionarlos para diseños flexibles.
- Casos avanzados de uso de Flexbox, Explorar cómo crear diseños complejos con Flexbox y combinarlo con otras técnicas de diseño.
- Limitaciones y consideraciones de compatibilidad, Conocer las limitaciones de Flexbox en diferentes navegadores y cómo abordarlas para una experiencia consistente.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Domingo 05 de Mayo del 2024.

Enlace de este contenido [class-09](https://omartpiza.github.io/reading-notes/201/class-09)
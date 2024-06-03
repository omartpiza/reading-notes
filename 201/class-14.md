# LECTURA CLASE 14

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## CSS Transforms
  
***1.¿Qué le permite al desarrollador hacer un CSS transform a un elemento?***

- El CSS transform permite aplicar transformaciones a un elemento, como:

    1. Translate: Mueve el elemento.

        ```css
        transform: translate(x, y);
        ```

    2. Scale: Cambia su tamaño.

        ```css
        transform: scale(x, y);
        ```

    3. Rotate: Gira el elemento.

        ```css
        transform: rotate(angle);
        ```

    4. Skew: Inclina el elemento.

        ```css
        transform: skew(x-angle, y-angle);
        ```

    5. Matrix: Combina múltiples transformaciones.

        ```css
        transform: matrix(a, b, c, d, e, f);
        ```

***2.Da un ejemplo de un transform y cómo puedes utiliarlo en un página web.***

- Al pasar el cursor sobre la imagen, ésta girará 45 grados, creando un efecto visual atractivo y dinámico en la página web.

    ```css
    .container {
    text-align: center;
    margin-top: 50px;
    }

    .rotar-imagen {
        width: 300px;
        transition: transform 0.5s ease;
    }

    .rotar-imagen:hover {
        transform: rotate(45deg);
    }
    ```

#### Enlaces de Fuentes

- [CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

## Transiciones & Animaciones CSS

***1.¿Qué le permite al desarrollador hacer un CSS transition a un elemento?***

- El CSS transition permite animar cambios en las propiedades de un elemento de manera suave. Se utilizan principalmente cuatro propiedades:

    1. transition-property: Qué propiedades animar.

        ```css
        transition-property: background-color;
        ```

    2. transition-duration: Duración de la animación.

        ```css
        transition-duration: 0.5s;
        ```

    3. transition-timing-function: Velocidad de la animación.

        ```css
        transition-timing-function: ease;
        ```

    4. transition-delay: Retraso antes de empezar la animación.

        ```css
        transition-delay: 0s;git 
        ```

***2.¿En qué se diferencia un CSS animation de un CSS transition?***

- CSS transition y animation son herramientas para animar elementos, pero tienen diferencias clave. Transition se activa por cambios en el estado (como hover o click), es simple de usar, y define solo estados inicial y final. Por ejemplo, al pasar el ratón sobre un elemento, se puede cambiar su color de fondo suavemente. En cambio, animation se define con @keyframes, puede iniciar automáticamente, y permite crear animaciones complejas con múltiples etapas. También ofrece más control, como repeticiones y direcciones de la animación. Un ejemplo es cambiar continuamente el color de un elemento en bucle. En resumen, usa transition para cambios simples y animation para animaciones más elaboradas y controladas.

#### Enlaces de Fuentes

- [Transiciones CSS](https://lenguajecss.com/css/animaciones/transiciones/)
- [Animaciones CSS](https://lenguajecss.com/css/animaciones/animaciones/)

## 8 simple CSS3 transitions that will wow your users

***1.¿Cuáles son los beneficios de utilizar CSS transitions en páginas web?***

1. Mejora de la experiencia del usuario: Transiciones suaves y naturales.
2. Feedback visual: Respuestas inmediatas a interacciones del usuario.
3. Fácil implementación: Más simples que las animaciones con JavaScript.
4. Mejor rendimiento: Optimizadas para navegadores, eficientes en dispositivos limitados.
5. Compatibilidad: Soportadas por la mayoría de los navegadores.
6. Aspecto moderno: Hacen la interfaz más dinámica y atractiva.

***2.¿Cómo este tema encaja con tus metas a largo plazo?***

- Comprender y dominar las transiciones CSS es fundamental para mejorar la experiencia de usuario en las aplicaciones web que desarrollo. Las CSS transitions permiten animar cambios en propiedades CSS como color, tamaño y posición de manera suave y elegante, lo cual es crucial para crear interacciones fluidas y naturales en la interfaz de usuario.

#### Enlaces de Fuentes

- [8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/QWMxRR)
- [6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)
- [CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/dyBqVo)
- [404](https://codepen.io/kieranfivestars/pen/MYdQxX)

## COSAS DE LAS QUE QUIERO SABER MAS

- CSS Animations: Aprender a crear animaciones más complejas y controladas utilizando `@keyframes`.
- Propiedades de Transición Avanzadas: Explorar otras propiedades de transición como `transition-delay`, `transition-property`, y `transition-timing-function`.
- JavaScript y CSS Transitions/Animations: Integración y uso de JavaScript para controlar transiciones y animaciones CSS.
- Animaciones 3D: Introducción a las transformaciones 3D y animaciones utilizando `transform: translate3d`, `rotate3d`, etc.
- Transiciones con SVG: Aplicar transiciones y animaciones a elementos SVG para crear efectos visuales avanzados.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Lunes 03 de Junio del 2024.

Enlace de este contenido [class-14](https://omartpiza.github.io/reading-notes/201/class-14)
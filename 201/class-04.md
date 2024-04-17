# LECTURA CLASE 4

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## Enlaces en HTML
***1.Para crear un enlace básico, ¿en qué elemento colocamos el texto u otro contenido?***

- Para crear un enlace básico en HTML, utilizamos el elemento `<a>`. Dentro de este elemento, colocamos el texto o cualquier otro contenido que queramos que se muestre como el enlace. 
Por ejemplo : 

```html
<a href=https://www.ejemplo.com>"nombre del enlace"</a>
```

***2.¿Qué información contiene el atributo `href`?***

- El atributo `href` es un atributo utilizado en elementos HTML, especialmente en elementos de anclaje `<a>` (es decir, enlaces). Este atributo define la URL a la que el enlace apunta. Cuando un usuario hace clic en un enlace con el atributo `href`, el navegador navegará a la dirección especificada por este atributo.

***3.¿Cuáles son algunas de las formas en las que podemos asegurarnos de que los enlaces a nuestras páginas sean accesibles a todos los lectores?***

- Para asegurarnos de que los enlaces en nuestras páginas sean accesibles para todos los lectores, es importante seguir algunas prácticas recomendadas de accesibilidad web. Aquí tienes algunas formas de lograrlo:

1. Texto descriptivo: Usa descripciones claras y específicas en lugar de "clic aquí".

2. Atributo title: Usa el atributo title para proporcionar información adicional.

3. Contraste de color: Asegúrate de que el texto del enlace sea legible en todos los fondos.

4. Subrayado o resaltado: Usa subrayado o resaltado para indicar enlaces.

5. Estilos consistentes: Mantén estilos de enlace consistentes en todo el sitio.

6. Tamaño del área de clic: Haz que el área de clic de los enlaces sea suficientemente grande.

7. Orden de tabulación: Asegúrate de que los enlaces se naveguen en un orden lógico.

8. Pruebas de accesibilidad: Realiza pruebas de accesibilidad para garantizar la accesibilidad del sitio.
  
#### Enlaces de Fuentes

- [Aprende HTML](https://developer.mozilla.org/es/docs/Learn/HTML)

- [Crea Hipervinculos](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

## Introducción al CSS: Layout

***1.¿A qué se refiere con “`normal flow`”?***

- se refiere al comportamiento predeterminado de los elementos HTML en una página web antes de aplicar estilos adicionales. En este flujo normal, los elementos se colocan en la página uno después del otro en el orden en que aparecen en el código HTML, siguiendo una disposición predeterminada. Los elementos bloque ocupan todo el ancho disponible y se muestran en líneas separadas, mientras que los elementos en línea se muestran en la misma línea que sus elementos vecinos.

***2.¿Cuáles son algunas de las diferencias entre los elementos `block-level` e `inline`?***

- Comportamiento de presentación: Los elementos de nivel de bloque ocupan toda la anchura disponible y comienzan en una nueva línea, mientras que los elementos en línea solo ocupan el espacio necesario y permanecen en la misma línea que el contenido adyacente.

- Ancho y alto: Los elementos de nivel de bloque pueden tener un ancho y alto definidos, mientras que los elementos en línea generalmente ignoran las propiedades de ancho y alto, excepto en casos específicos como las imágenes y los elementos de formulario.

- Margen y relleno: Los elementos de nivel de bloque pueden tener márgenes y relleno en todas las direcciones, mientras que los elementos en línea generalmente solo pueden tener márgenes horizontales y relleno izquierdo y derecho.

- Comportamiento del modelo de caja: Los elementos de nivel de bloque siguen el modelo de caja completo (margen, borde, relleno y contenido), mientras que los elementos en línea solo se aplican al contenido dentro de ellos.

- Agrupación de contenido: Los elementos de nivel de bloque son útiles para agrupar y estructurar grandes secciones de contenido, mientras que los elementos en línea son más adecuados para elementos de contenido más pequeños y fragmentos de texto dentro de los bloques de nivel de bloque.

***3.El ___ positioning es la posición por defecto de todos los elementos en html.***

- El "`static`" positioning es la posición por defecto de todos los elementos en HTML.
Asimismo, es donde se colocan en el orden en que aparecen en el código sin ningún desplazamiento o superposición.

***4.Nombra algunas ventajas de utilizar absolute positioning en un elemento.***

- Control preciso de la ubicación: Puedes colocar un elemento exactamente donde lo desees en relación con su elemento contenedor o a la ventana del navegador.

- Superposición de elementos: Permite superponer elementos unos sobre otros, lo que es útil para crear capas de contenido, como menús desplegables o ventanas emergentes.

- Independencia del flujo del documento: Los elementos posicionados de forma absoluta se eliminan del flujo normal del documento, lo que significa que no afectan el diseño de otros elementos circundantes.

- Facilita el diseño responsive: Al posicionar elementos de forma absoluta, puedes ajustar fácilmente su ubicación y tamaño en diferentes tamaños de pantalla o dispositivos sin afectar el diseño general.

- Animaciones y efectos visuales: Es útil para crear efectos de animación o transición, ya que permite mover elementos de forma suave y controlada sin interferir con otros elementos en la página.

***5.¿Cuál es una diferencia clave entre fixed positioning y absolute positioning?***

- Absolute positioning: Los elementos posicionados de forma absoluta se colocan en relación con el ancestro posicionado más cercano, es decir, un elemento que tenga un posicionamiento diferente a `static` (como `relative`, `absolute`, `fixed`, o `sticky`).

- Fixed positioning: Los elementos posicionados de forma fija se colocan en relación con la ventana del navegador, lo que significa que permanecen en la misma posición incluso cuando la página se desplaza. No dependen de ningún elemento contenedor y se mantienen fijos en la pantalla.

#### Enlaces de Fuentes

- [CSS Layout](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout)

- [CSS: Layout: Normal Flow](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Normal_Flow)

- [CSS: Layout: Positioning](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Positioning)

## Funciones en JS

***1.Describe la diferencia entre una declaración de función y una invocación de función.***

- Declaración de función: Es cuando defines una función y le das un nombre, especificando los parámetros que puede recibir y el código que se ejecutará cuando la función sea llamada.

- Invocación de función: Es cuando realmente llamas o ejecutas la función que has definido. En otras palabras, es cuando usas el nombre de la función junto con los paréntesis para ejecutar el código dentro de ella.

***2.¿Cuál es la diferencia entre un parameter y un argument?***

- Parámetro: Es un término utilizado para nombrar las variables que se incluyen en la definición de una función. Son como marcadores de posición para los valores que se pasarán a la función cuando se llame.

- Argumento: Es el valor real que se pasa a la función cuando se la invoca. Estos valores se asignan a los parámetros de la función durante la llamada.

#### Enlaces de Fuentes

- [Aprende JS](https://developer.mozilla.org/es/docs/Learn/JavaScript)

- [Funciones](https://imoralescs.gitbooks.io/javascript/content/funciones.html)

## MISCELANEA

***1.Escoge 2 beneficios del pair programming y reflexiona acereca de cómo estos beneficios te pueden ayudar en tu carrera como programador.***

1. Mejora de la calidad del código: Al trabajar en equipo, es más probable que se detecten errores y se generen soluciones más sólidas. La revisión constante entre compañeros ayuda a identificar posibles problemas y a encontrar soluciones más eficientes.

2. Aprendizaje y crecimiento profesional: El pair programming ofrece la oportunidad de aprender de los demás, ya que cada miembro del equipo puede tener diferentes enfoques y conocimientos. Esto fomenta el desarrollo de habilidades técnicas y blandas, así como el intercambio de buenas prácticas de programación.

- El pair programming mejora la calidad del código al detectar errores y encontrar soluciones más sólidas, además de proporcionar oportunidades de aprendizaje y crecimiento profesional al trabajar en equipo y aprender de los compañeros. Esto es impotante para la carrera como programador, ya que permite mejorar las habilidades técnicas, adquirir nuevos conocimientos y desarrollar una comprensión más profunda de diferentes enfoques y técnicas de programación, además de fomentar la comunicación efectiva y la colaboración.

## COSAS DE LAS QUE QUIERO SABER MAS

- Explorar nuevas herramientas y tecnologías que puedan mejorar mi flujo de trabajo como desarrollador.

- Profundizar en el aprendizaje automático y la inteligencia artificial para explorar cómo estas tecnologías pueden mejorar mis proyectos.

- Profundizar en los conceptos de posicionamiento en CSS.

- Aprender sobre patrones de diseño de software y cómo aplicarlos en mis proyectos.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Miercoles 17 de Abril del 2024.

Enlace de este contenido [class-04](https://omartpiza.github.io/reading-notes/201/class-04)
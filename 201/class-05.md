# LECTURA CLASE 5

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## MEDIOS EN HTML
  
***1.¿Cuál es un caso práctico del atributo `alt` en una página web?***

- El atributo `alt` en la etiqueta `<img>` proporciona texto alternativo para las imágenes en una página web. Esto es esencial para la accesibilidad, permitiendo a los usuarios con discapacidad visual comprender el contenido de las imágenes mediante lectores de pantalla. Por ejemplo:

    ```html
  <img src="imagen.jpg" alt="Descripción de la imagen">
    ```  

    Donde "Descripción de la imagen" es un texto descriptivo de la imagen.

***2.¿Cómo puedes mejorar la accesibilidad de las imágenes en un documento HTML?***

- Para mejorar la accesibilidad de las imágenes en HTML:

1. Usa el atributo `alt` para proporcionar texto alternativo descriptivo.

2. Asegúrate de que el texto alternativo sea significativo y claro.

3. Utiliza imágenes con un tamaño adecuado.

4. Opcionalmente, usa la etiqueta `title` para información adicional.

5. En SVG, proporciona texto alternativo con la etiqueta `<desc>` o `aria-labelledby`.

6. Asegúrate de un buen contraste de color si hay texto en la imagen.

7. Valida y prueba la accesibilidad de tus imágenes usando herramientas adecuadas.

***3.Da un ejemplo en el que el elemento `figure` sería útil en un documento HTML.***

- El elemento `<figure>` en HTML es útil cuando queremos asociar una imagen con una leyenda o descripción. Por ejemplo:

    ```html
    <figure>
    <img src="imagen.jpg" alt="Descripción de la imagen">
    <figcaption>Leyenda o descripción de la imagen.</figcaption>
    </figure>
    ```  

    Esto proporciona una estructura semántica clara al contenido visual y su descripción asociada.

***4.Describe la diferencia entre una imágen `gif` y una imágen `svg`, imagina que se lo estás explicando a una persona mayor de tu comunidad.***

- Una imagen GIF es similar una foto animada, como un pequeño video. Mientras que una imagen SVG es parecido a un dibujo vectorial que puedes hacer más grande o más pequeño sin que pierda calidad. Por ell, GIF es para animaciones y SVG para gráficos que se ven bien en diferentes tamaños.

***5.¿Qué tipo de imagen usuarías para mostrar una captura de pantalla en tu página web y por qué?***

- Usaría el formato `PNG` para mostrar una captura de pantalla en una página web porque ofrece alta calidad visual, soporte de transparencia y compatibilidad universal. Ademas, la compresion sin perdida grantiza que el tamaño del archivo no sea excesivamente grande.
  
#### Enlaces de Fuentes

- [Utilizar Imágenes In HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

- [Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

- [Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

## APRENDE CSS

***1.Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una personas sin conocimientos técnicos***

- El `color de fondo` es como el papel sobre el que escribes, es el color que cubre toda la parte de atrás de algo, como una página o una caja. Mientras tanto, el `color de primer plano` es como la tinta que usas para escribir sobre ese papel, es el color que se utiliza para el texto o los dibujos que van encima del fondo.

***2.¿Tu amigo te pide que le des un retoque a este blog sin colores. ¿Cómo usarías el color para darle un poco de personalidad a este blog?***

- Si se pide darle un toque de personalidad al blog sin usar colores, aún hay muchas formas creativas de hacerlo utilizando otras características visuales. Por ejemplo:

1. Tipografía: Usa fuentes interesantes que reflejen el tono del blog.

2. Espacio en blanco: Mantén un diseño limpio y ordenado.

3. Contraste: Destaca elementos importantes con texto en negrita.

4. Iconos y gráficos: Agrega elementos visuales para mejorar la comunicación.

5. Texturas y patrones: Utiliza patrones sutiles para añadir profundidad.

6. Ilustraciones: Incorpora ilustraciones personalizadas para un toque único.

***3.¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?***

- Al escoger tipos de letra para un documento HTML, es importante tener en cuenta varios aspectos para garantizar una buena legibilidad y coherencia en el diseño. Por ejemplo:

1. Prioriza la legibilidad sobre la estética.

2. Mantén la coherencia en la elección de fuentes.

3. Asegúrate de que las fuentes sean compatibles con la mayoría de los navegadores.

4. Ajusta el tamaño de la fuente según el contenido.

5. Elige fuentes con buen contraste para una mejor legibilidad.

6. Considera el estilo y tono del contenido al seleccionar las fuentes.

7. Si usas fuentes web, asegúrate de incluir enlaces adecuados en tu HTML.

***4.¿Cuál es la relación entre `font-size`, `font-weight`, y `font-style` con los elementos de texto en HTML?***

- La relación entre font-size, font-weight y font-style y los elementos de texto en HTML es que son propiedades CSS que se utilizan para controlar el tamaño, peso y estilo de la fuente de los elementos de texto en una página web. Estos son:

1. font-size: Controla el tamaño del texto.
2. font-weight: Controla el grosor o peso del texto (normal, negrita, etc.).
3. font-style: Controla si el texto es normal o cursiva.

***5.Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento `h1`.***

1. Agrega `margin` o `padding` alrededor del elemento `<h1>` usando CSS. Por ejemplo:

    ```css
    h1 {
    margin: 10px; /* Añade espacio alrededor del elemento h1 */
    padding: 10px; /* Añade espacio dentro del elemento h1 */
    }
    ``` 

    Esto añadirá un espacio uniforme alrededor y dentro del elemento `<h1>`. Puedes ajustar los valores de `margin` y `padding` según sea necesario.

2. Usa la propiedad `letter-spacing` para ajustar el espacio entre los caracteres dentro del `<h1>`.

    ```css
    h1 {
    letter-spacing: 2px; /* Añade espacio entre los caracteres del h1 */
    }
    ```

    Esto añadirá un espacio adicional entre cada carácter dentro del elemento `<h1>`. Puedes ajustar el valor de `letter-spacing` según el grado de espaciado deseado.

#### Enlaces de Fuentes

- [Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

- [Styling HTML Text Elements](https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Fundamentals)

## COSAS DE LAS QUE QUIERO SABER MAS

- Selección tipográfica, aprender más sobre los principios de diseño tipográfico y cómo elegir y combinar tipos de letra efectivamente en un documento HTML.
- Formatos de imágenes, Investigar más sobre los formatos de imágenes recomendados para diferentes tipos de contenido web y comprender las ventajas y desventajas de cada uno.
- Espaciado y diseño visual, Explorar técnicas adicionales para controlar el espaciado y la disposición de los elementos en una página web, como el uso de márgenes, rellenos y alineaciones.
- CSS Avanzado, Profundizar en el uso de CSS para añadir personalidad y estilo a un sitio web, explorando técnicas como gradientes, sombras y efectos de transición.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Lunes 22 de Abril del 2024.

Enlace de este contenido [class-05](https://omartpiza.github.io/reading-notes/201/class-05)
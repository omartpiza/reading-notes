# LECTURA CLASE 11

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## Depuracion
  
***1.Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.***

- Desde el inicio de los años 2000, la capacidad para utilizar video y audio en la web ha evolucionado significativamente. En los primeros años, se limitaba principalmente a GIFs animados y clips de audio en formatos como MP3. A mediados de la década, Adobe Flash dominaba la reproducción de video, aunque requería un plugin y no era compatible con todos los dispositivos. A partir de 2010, la introducción de HTML5 marcó un cambio hacia estándares abiertos, con los elementos `<video>` y ` permitiendo la reproducción nativa sin plugins. Este avance también trajo códecs estándar como H.264 y VP9, mejorando la calidad y permitiendo la transmisión en alta definición y audio de mayor fidelidad.

***2.Describe el uso de los atributos `src` y `controls` en el elemento `<video>`.***

1. Atributo `src`:

    - El atributo `src` especifica la URL del archivo de video que se va a reproducir. Puede ser una ruta relativa o absoluta.En este ejemplo, video.mp4 es el archivo de video que se va a reproducir:

    ```html
    <video src="video.mp4"></video>
    ```

2. Atributo `controls`:

    - El atributo `controls` añade controles de reproducción estándar al reproductor de video, como botones de reproducción/pausa, barra de progreso y controles de volumen. En este caso, además de especificar el archivo de video (`video.mp4`), se incluyen automáticamente los controles para que los usuarios puedan reproducir, pausar y ajustar el video.

    ```html
    <video src="video.mp4" controls></video>
    ```

***3.¿Por qué es importante tener contenido de respaldo en el elemento `<video>`?***

- Es importante tener contenido de respaldo en el elemento `<video>` para asegurar la compatibilidad con diferentes navegadores y dispositivos, mejorar la accesibilidad para usuarios con discapacidades, optimizar el rendimiento de carga del video y proporcionar una experiencia continua en caso de problemas de red.

***4.Escribe una historia corta en donde `<audio>` y `<video>` son personajes.***

- En la ciudad digital de Enterland, vivían dos hermanos inseparables: Audio y Video. Audio tenía una voz melodiosa que narraba historias emocionantes, mientras que Video capturaba momentos memorables en imágenes. Juntos, creaban experiencias inolvidables para todos en Enterland, complementándose perfectamente en cada evento y celebración.

***5.¿En qué se diferencia el layout Grid del Flex?***

- La principal diferencia radica en que CSS Grid es bidimensional y ofrece un control más granular sobre el diseño de la cuadrícula, mientras que Flexbox es unidimensional y está diseñado para organizar elementos en una dirección (fila o columna) de manera más predecible y eficiente. La elección entre Grid y Flexbox dependerá del tipo de diseño que se esté implementando y de las necesidades específicas del proyecto.

#### Enlaces de Fuentes

- [Contenido de audio y video](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## El Depurador de JavaScript

***1.Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?***

- Los desarrolladores deberían hacer imágenes responsivas porque optimizan el rendimiento del sitio al cargar versiones más pequeñas en dispositivos móviles, mejoran la experiencia del usuario al reducir los tiempos de carga, ahorran ancho de banda y mejoran el SEO al proporcionar una mejor experiencia de usuario y velocidad de carga.

***2.Define los siguientes atributos de `<img>`: `srcset` y `sizes`. Escribe un ejemplo de cómo se usan.***

- Estos atributos permiten que las imágenes se ajusten de manera óptima a diferentes tamaños de pantalla y dispositivos, mejorando así la experiencia del usuario y optimizando el rendimiento del sitio web.

    1. `srcset`: Especifica diferentes versiones de una imagen junto con sus tamaños, permitiendo al navegador seleccionar la más adecuada según la resolución del dispositivo.

        ```html
        <img src="small.jpg" srcset="medium.jpg 1000w, large.jpg 2000w" alt="Descripción">
        ```

    2. `sizes`: Indica al navegador los tamaños de diseño de la imagen que se utilizarán para seleccionar la imagen correcta de `srcset`.

        ```html
        <img src="small.jpg" srcset="medium.jpg 1000w, large.jpg 2000w"
        sizes="(max-width: 600px) 100vw, (max-width: 1200px) 50vw, 1000px"
        alt="Descripción">
        ```

***3.¿Cómo es que `srcset` es más útil para las imágenes responsivas que CSS o JavaScript?***

- El atributo `srcset` es más útil para imágenes responsivas que CSS o JavaScript porque permite al navegador seleccionar automáticamente la imagen adecuada según la resolución del dispositivo. Esto optimiza el rendimiento al cargar imágenes más pequeñas y específicas, sin necesidad de scripts adicionales, lo cual es más eficiente y compatible con los navegadores modernos.

#### Enlaces de Fuentes

- [Imágenes Responsivas](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [Imágenes en HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [Otras Tecnologías de Incrustación](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## COSAS DE LAS QUE QUIERO SABER MAS

- Aprender más sobre cómo hacer que los sitios web se vean bien en diferentes tamaños de pantalla y dispositivos.
- Profundizar en cómo estos sistemas de diseño en CSS funcionan y cuándo es mejor utilizar uno sobre el otro.
- Aprender más sobre cómo optimizar imágenes para diferentes resoluciones de pantalla utilizando `srcset` y `sizes`.
- Comprender cómo las imágenes responsivas y otros aspectos del diseño web afectan al rendimiento y al SEO de un sitio web.
- Mantenerse al día con las últimas tendencias y tecnologías emergentes en el desarrollo web, como las mejoras en CSS y HTML.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Martes 14 de Mayo del 2024.

Enlace de este contenido [class-11](https://omartpiza.github.io/reading-notes/201/class-11)
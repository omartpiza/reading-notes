# LECTURA CLASE 12

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## Canvas
  
***1.¿Qué es lo que el `<canvas>` le permite lograr al desarrollador?***

- El elemento `<canvas>` en HTML5 permite a los desarrolladores crear gráficos 2D dinámicos, animaciones, visualizaciones de datos interactivas, juegos, manipulación de imágenes y, a través de WebGL, renderizado 3D, todo dentro del navegador sin necesidad de plugins adicionales.

***2.¿Cuál es la importancia de cerrar la etiqueta `</canvas>`?***

- Cerrar la etiqueta `</canvas>` es importante porque asegura la correcta estructura del documento HTML y garantiza la compatibilidad con los estándares web. Aunque los navegadores modernos suelen manejar adecuadamente las etiquetas no cerradas, cerrar `<canvas>` correctamente mejora la claridad y mantenibilidad del código, además de prevenir posibles errores de renderizado en navegadores más antiguos o en situaciones inusuales.

***3.Explica lo que hace el método `getContext()`.***

- El método `getContext()` en JavaScript se utiliza con el elemento `<canvas>` para obtener un contexto de dibujo, como `"2d"` para gráficos 2D o `"webgl"` para gráficos 3D. Devuelve un objeto que permite realizar operaciones de dibujo en el `<canvas>`, como dibujar formas, texto, imágenes y realizar animaciones, dependiendo del contexto obtenido.

#### Enlaces de Fuentes

- [Canvas - una introducción](https://w3.unpocodetodo.info/canvas/introduccion.php)
- [Uso básico de Canvas](https://developer.mozilla.org/es/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

## Chart.js

***1.¿Qué es Chart.js y cómo se puede incorporar en nuestro proyecto?***

- Chart.js es una biblioteca JavaScript que permite crear gráficos interactivos en la web. Para incorporarlo en tu proyecto, incluye Chart.js en tu HTML desde una CDN o descárgalo directamente, luego crea un `<canvas>` donde quieras mostrar el gráfico y configúralo con JavaScript para definir el tipo de gráfico, los datos y las opciones de personalización. Es una forma fácil y poderosa de visualizar datos de manera atractiva y comprensible en tu aplicación web.

***2.Enumera 3 tipos diferentes de gráficos que puedes crear utilizando Chart.js.***

1. Gráfico de Barras (Bar Chart):

    - Este tipo de gráfico muestra datos en barras rectangulares horizontales o verticales.

    ```js
    var myChart = new Chart(ctx, {
        type: 'bar',
        data: {
            labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
            datasets: [{
                label: '# of Votes',
                data: [12, 19, 3, 5, 2, 3],
                backgroundColor: 'rgba(255, 99, 132, 0.2)',
                borderColor: 'rgba(255, 99, 132, 1)',
                borderWidth: 1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
    ```

2. Gráfico de Líneas (Line Chart):

    - Muestra información como una serie de puntos (marcadores) conectados por líneas rectas.

    ```js
    var myChart = new Chart(ctx, {
        type: 'line',
        data: {
            labels: ['January', 'February', 'March', 'April', 'May', 'June'],
            datasets: [{
                label: 'Sales',
                data: [65, 59, 80, 81, 56, 55],
                fill: false,
                borderColor: 'rgb(75, 192, 192)',
                tension: 0.1
            }]
        },
        options: {
            scales: {
                y: {
                    beginAtZero: true
                }
            }
        }
    });
    ```

3. Gráfico de Pastel (Pie Chart):

    - Muestra partes proporcionales de un todo, representado como un círculo dividido en segmentos.

    ```js
    var myChart = new Chart(ctx, {
        type: 'pie',
        data: {
            labels: ['Red', 'Blue', 'Yellow'],
            datasets: [{
                label: '# of Votes',
                data: [10, 20, 30],
                backgroundColor: ['rgb(255, 99, 132)', 'rgb(54, 162, 235)', 'rgb(255, 205, 86)'],
                hoverOffset: 4
            }]
        }
    });
    ```

#### Enlaces de Fuentes

- [Chart.js Documentation](https://www.chartjs.org/docs/latest/)

## Graficos animados con Chart.js

***1.¿Cuáles son algunas de las ventajas de mostrar datos por medio de un gráfico en vez de una tabla?***

- Mostrar datos mediante gráficos en lugar de tablas tiene ventajas como una visualización más clara y rápida de relaciones y tendencias, facilita la comparación de valores, captura tendencias fácilmente, es más atractivo visualmente, simplifica la interpretación de datos complejos y facilita la comunicación efectiva de ideas clave.

***2.¿Cómo puede ayudar Chart.js a tus aplicaciones creadas anteriormente?***

- Chart.js puede mejorar las aplicaciones anteriores al agregar gráficos interactivos y atractivos que facilitan la comprensión rápida de datos, permiten personalización y flexibilidad, integran fácilmente en aplicaciones existentes, son compatibles con dispositivos móviles y ofrecen visualizaciones dinámicas en tiempo real.

#### Enlaces de Fuentes

- [Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [Dibujando formas con canvas](https://developer.mozilla.org/es/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
- [Applying Style and Colors - Canvas API](https://developer.mozilla.org/es/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- [Dibujar texto - Canvas API](https://developer.mozilla.org/es/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

## COSAS DE LAS QUE QUIERO SABER MAS

- Aprender a crear gráficos dinámicos y animaciones utilizando el elemento `<canvas>` en HTML5 en tus aplicaciones web.
- Explorar por qué los gráficos son más efectivos que las tablas para mostrar datos, facilitando la comprensión y la visualización de tendencias.
- Aprender cómo las visualizaciones de datos pueden mejorar la experiencia del usuario y la comprensión de la información en aplicaciones web existentes.
- Amplíar tu conocimiento sobre JavaScript y cómo se aplica en el desarrollo web para crear interactividad y dinamismo en tus aplicaciones.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Lunes 16 de Mayo del 2024.

Enlace de este contenido [class-12](https://omartpiza.github.io/reading-notes/201/class-12)
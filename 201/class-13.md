# LECTURA CLASE 13

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## Local Storage
  
***1.¿Por qué un desarrollador utilizaría el local storage para una aplicación web?***

- Un desarrollador utilizaría el almacenamiento local en una aplicación web para proporcionar persistencia de datos, almacenar información del usuario, reducir la carga del servidor, permitir el funcionamiento sin conexión y mejorar la experiencia del usuario al cargar datos de manera rápida y sin necesidad de conexión constante al servidor.

***2.¿Qué información no se puede guardar en el local storage?***

- El almacenamiento local en el navegador tiene limitaciones en cuanto a qué tipo de información se puede guardar. No se puede almacenar información sensible, como contraseñas en texto plano, información financiera o información personal identificable, debido a preocupaciones de seguridad y privacidad. Además, el almacenamiento local tiene un límite de capacidad variable según el navegador y el dispositivo, por lo que no es adecuado para grandes cantidades de datos. Los datos sensibles deben ser encriptados antes de ser almacenados, y se recomienda utilizar métodos de almacenamiento más seguros para datos críticos, como bases de datos en el servidor.

***3.¿Qué tipo de datos se pueden guardar en el local storage? ¿Cómo puedes convertirlo a ese tipo de archivo antes de guardarlo?***

- En el almacenamiento local del navegador se pueden guardar datos en forma de pares clave-valor, donde tanto la clave como el valor son cadenas de texto. Esto significa que se pueden guardar datos simples como cadenas de texto, números, booleanos, arrays y objetos JSON. Antes de guardar datos en el almacenamiento local, es importante convertirlos al tipo de dato adecuado utilizando métodos como `JSON.stringify()` para convertir objetos JavaScript en cadenas JSON, y `JSON.parse()` para convertir cadenas JSON de vuelta a objetos JavaScript. Esto asegura que los datos estén en un formato compatible con el almacenamiento local y puedan ser recuperados y utilizados correctamente más adelante.

#### Enlaces de Fuentes

- [Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [“The Past, Present, and Future of Local Storage for Web Applications”](https://diveinto.html5doctor.com/storage.html)

## COSAS DE LAS QUE QUIERO SABER MAS

- Investigar eventos y métodos avanzados relacionados con el almacenamiento local en JavaScript, como los eventos de almacenamiento local (`storage`), la gestión de límites de almacenamiento y la sincronización de datos entre pestañas o ventanas del navegador.
- Comprender otras formas de almacenamiento de datos en el navegador, como cookies, Web Storage (sessionStorage), IndexedDB y caches del navegador, y comparar sus ventajas y limitaciones en diferentes escenarios de desarrollo web.
- Aprender cómo se integra el almacenamiento local en diferentes frameworks y bibliotecas de JavaScript, como React, Angular o Vue.js, y cómo aprovecharlo al máximo para mejorar la funcionalidad y la experiencia del usuario en aplicaciones web modernas.
- Explorar ejemplos prácticos de cómo el almacenamiento local se utiliza en aplicaciones web reales, incluyendo aplicaciones que requieren funcionamiento sin conexión, almacenamiento de preferencias de usuario y datos temporales para mejorar la experiencia del usuario.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Lunes 20 de Mayo del 2024.

Enlace de este contenido [class-13](https://omartpiza.github.io/reading-notes/201/class-12)
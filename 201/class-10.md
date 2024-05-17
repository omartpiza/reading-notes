# LECTURA CLASE 10

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## Depuracion
  
***1.Menciona algunas diferencias clave entre un Syntax Error y un Logic Error***

- Syntax Error (Error de Sintaxis)
    1. Definición: Ocurre cuando el código no sigue las reglas del lenguaje de programación.
    2. Detección: Detectado por el compilador o intérprete antes de ejecutar el programa.
    3. Mensaje de Error: Proporcionado por el sistema, indicando la ubicación y naturaleza del error.
    4. Resolución: Corregir la escritura o estructura del código.

- Logic Error (Error Lógico)
    1. Definición: Ocurre cuando el código se ejecuta sin problemas de sintaxis, pero produce resultados incorrectos.
    2. Detección: Detectado durante la ejecución mediante pruebas.
    3. Mensaje de Error: No hay mensajes específicos; el programa no funciona como se espera.
    4. Resolución: Revisar y ajustar la lógica del programa.

***2.Enumera algunos tipos de errores que has encontrado en las tareas de laboratorio anteriores y explica cómo fuiste capaz de corregirlos.***

1. Syntax Error:
    - Descripción: Olvidar un punto y coma en Java.
    - Corrección: Añadí el punto y coma al final de la línea para cumplir con la sintaxis del lenguaje.

2. Logic Error:
    - Descripción: Usar `+` en lugar de `*` en una fórmula matemática.
    - Corrección: Revisé la lógica del cálculo y sustituí el operador `+` por `*`.

3. Runtime Error:
    - Descripción: Intentar acceder a un índice fuera del rango en un arreglo.
    - Corrección: Añadí una verificación para asegurarme de que el índice estaba dentro del rango válido del arreglo.

4. Type Error:
    - Descripción: Intentar concatenar una cadena con un número sin conversión explícita.
    - Corrección: Convertí el número a cadena antes de la concatenación usando `str()` en Python.

5. Name Error:
    - Descripción: Uso de una variable no declarada o mal escrita.
    - Corrección: Verifiqué la declaración y corregí la escritura del nombre de la variable.

6. Off-by-One Error:
    - Descripción: Iterar un bucle una vez más o menos de lo necesario.
    - Corrección: Ajusté las condiciones del bucle para que iterara el número correcto de veces.

7. Null Pointer Exception:
    - Descripción: Intentar acceder a un método o propiedad de un objeto que no ha sido inicializado.
    - Corrección: Añadí verificaciones para asegurarme de que el objeto no era nulo antes de acceder a sus métodos o propiedades.

***3.¿Cómo este tema influye en tus metas a largo plazo?***

- El manejo eficaz de errores en programación no solo mejora mi habilidad técnica, sino que también contribuye a la eficiencia, calidad del trabajo, avance profesional, y habilidades de colaboración, todas esenciales para alcanzar mis metas a largo plazo en el campo de la tecnología y desarrollo de software.

#### Enlaces de Fuentes

- [¿Qué ha salido mal? Corrigiendo JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_went_wrong)

## El Depurador de JavaScript

***1.¿Cómo le describirías la herramienta de depuración de JavaScript y su función a una persona que recién comienza en el desarrollo de software?***

- La herramienta de depuración de JavaScript es una función incorporada en navegadores web como Chrome y Firefox, diseñada para ayudar a los desarrolladores a encontrar y solucionar errores en su código. Sus principales funciones incluyen una consola para ejecutar código directamente y mostrar mensajes de error, puntos de interrupción que pausan el código en lugares específicos para inspeccionar, un inspector de variables que muestra los valores de las variables durante la ejecución, y la capacidad de ejecutar el código paso a paso para entender el flujo del programa. Además, ofrece perfilado de rendimiento para analizar y mejorar la velocidad del código. Esta herramienta es extremadamente útil porque permite identificar rápidamente errores, comprender el flujo del programa y optimizar el código, facilitando un desarrollo más eficiente y efectivo.

***2.Define qué es un breakpoint.***

- Un breakpoint es un punto específico en el código de un programa donde se le indica al depurador que detenga la ejecución normal del programa. Cuando se alcanza un breakpoint durante la ejecución del programa, éste se pausa y permite al desarrollador examinar el estado del programa en ese punto, como el valor de las variables y la ejecución de la función. Esto facilita la depuración y el diagnóstico de problemas al permitir inspeccionar el código línea por línea y entender cómo se comporta el programa en tiempo de ejecución.

***3.¿Qué es el call stack?***

- El call stack es una estructura de datos que sigue el orden de las funciones que un programa de computadora ha llamado. Funciona como una pila donde la última función llamada es la primera en completarse, y es esencial para el seguimiento y la gestión de las llamadas a funciones durante la ejecución del programa.

#### Enlaces de Fuentes

- [El depurador de JavaScript](https://developer.mozilla.org/es/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools#the_javascript_debugger)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [Depurar HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)
- [Depurar CSS](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Debugging_CSS)

## COSAS DE LAS QUE QUIERO SABER MAS

- Explorar tipos de errores como errores de lógica, errores de tiempo de ejecución y errores de sintaxis. Aprende sobre las causas comunes y cómo identificar y corregir estos errores.
- Profundizar en técnicas avanzadas para la depuración de problemas complejos, como el uso de perfiles de rendimiento, análisis de flujo de datos y técnicas de trazado de ejecución.
- Aprender mejores prácticas para manejar y prevenir errores en el desarrollo de software, como el manejo adecuado de excepciones y el uso de pruebas unitarias para la detección temprana de errores.
- Comprender la teoría detrás de la depuración y cómo se aplica en la práctica. Esto incluye entender los principios de la depuración y cómo usar herramientas para solucionar problemas de código.
- Comprender las funciones clave de las herramientas de depuración, como consolas, puntos de interrupción, inspectores de variables y ejecución paso a paso. Aprende cómo utilizar estas herramientas para diagnosticar y corregir problemas en el código.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Jueves 09 de Mayo del 2024.

Enlace de este contenido [class-10](https://omartpiza.github.io/reading-notes/201/class-10)
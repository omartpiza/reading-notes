# LECTURA CLASE 2

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## INTRODUCCION A HTML
  
***1.¿Por qué es importante utilizar elementos semánticos en nuestro HTML?***

- Utilizar elementos semánticos en HTML es importante porque mejora la legibilidad del código, facilita la accesibilidad para personas con discapacidad visual, y ayuda a los motores de búsqueda a entender mejor el contenido de la página web.

***2.¿Cuántos niveles de encabezado existen en HTML?***

- En HTML, existen seis niveles de encabezados, que van desde “ `<h1>` “ como el más importante hasta “ `<h6>` “ como el menos importante.

***3.¿Cuáles son algunos de los usos para los elementos “ `<sup>` “ y “ `<sub>` “?***

- Algunos de los usos para los elementos "`<sup>`" y "`<sub>`" en HTML son los siguientes:

    1. El elemento "`<sup>`" se utiliza para representar superíndices, como en fórmulas matemáticas o abreviaturas francesas.
    2. El elemento "`<sub>`" se utiliza para representar subíndices, como en fórmulas químicas o matemáticas, y para notas al pie en documentos.

***4.Al utilizar el elemento “ `<abbr>` “, ¿qué atributo se debe añadir para proporcionar una ampliación del término?***

- El atributo a añadir al elemento "`<abbr>`" para proporcionar una ampliación del término es "`title`".
  
#### Enlaces de Fuentes

- [Introduccion a HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML)

- [Fundamentos de texto en HTML](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

- [Formateo de texto avanzado](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

## APRENDE CSS

***1.¿De qué formas podemos añadir CSS a nuestro HTML?***

- Hay tres formas de añadir CSS a HTML:
    1. Estilo en línea: se inserta CSS en una sola línea, dentro del atributo "style" de la etiqueta HTML correspondiente.
    2. CSS incrustado: se inserta dentro del encabezado de la página HTML, dentro de una etiqueta "style", y se especifica el selector para aplicar las propiedades CSS a un elemento específico.
    3. Enlace externo: se crea un archivo CSS separado y se vincula a la página HTML mediante una etiqueta "link" en el encabezado de la página.

***2.¿Por qué deberíamos evitar utilizar estilos inline?***

- Se debe evitar utilizar estilos inline en HTML porque dificultan la gestión del sitio web, desordenan la estructura HTML, llevan mucho tiempo y afectan al tamaño de la página y al tiempo de carga, y no se pueden almacenar en caché. Se recomienda utilizar CSS externo o interno para una mejor organización y mantenimiento del código.

***3.Revisa el código a continuación y responde a las siguientes preguntas:***

    ```css
    h2 {
     color: black;
     padding: 5px;
    }
    ```  

1. ¿Qué representa el selector?

    - El selector en el código dado es "h2".

2. ¿Qué componentes son declaraciones CSS?

    - Las declaraciones CSS en el código son: `color: black;` y `padding: 5px;`.

3. ¿Qué componentes se consideran propiedades?

    - Las propiedades en el código son: `color` y `padding`.

#### Enlaces de Fuentes

- [Cómo se estructura el CSS](https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/How_CSS_is_structured)

## APRENDE JS

### Fundamentos de JavaScript

***1.¿Qué tipo de dato es una secuencia de texto entre comillas simples?***

- Una secuencia de texto entre comillas simples es una cadena de texto delimitada por comillas simples en HTML.

***2.Enumera 4 tipos de operadores en JavaScript.***

- Hay tres formas de añadir CSS a HTML:
    1. Operadores Aritméticos: Se utilizan para realizar operaciones matemáticas básicas, como sumar, restar, multiplicar y dividir números.
    2. Operadores de Asignación: Permiten asignar valores a variables y actualizar sus valores.
    3. Operadores de Comparación: Se utilizan para comparar valores y devuelven un valor booleano (true o false).
    4. Operadores Binarios: Operan a nivel de bits, donde los operandos solo pueden tomar valores de 0 o 1.

***3.Describe un problema práctico que puedes resolver con una función.***

- Si queremos calcular el doble de un número. Podemos crear una función llamada "doble" que tome como argumento el número y devuelva su doble. Podriamos utilizar el siguiente codigo:

```js
function doble(numero) {
  return numero * 2;
}

let miNumero = 5;
let resultado = doble(miNumero);
console.log("El doble de " + miNumero + " es " + resultado);
```  

#### Enlaces de Fuentes

- [Fundamentos de JavaScript](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

### Tomando decisiones en tu código — condicionales

***1.Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará.***

- "Si una declaración if comprueba una *condición* y si resulta *verdadera* , entonces el código se ejecutará."

***2.¿Cuál es el uso del “ `else if` “?***

- El “ `else if` “ es una cláusula que se utiliza en JavaScript para evaluar varias condiciones de forma secuencial después de una condición “ `if` “. Si la condición del “ `if` “ no se cumple, se pasa a evaluar la condición del “ `else if` “. Si esta condición se cumple, se ejecuta el código asociado a ella. Si ninguna de las condiciones se cumple, se ejecuta el código del “ `else` “ (si existe).

***3.Enumera 3 tipos de operadores de comparación.***

- Algunos operadores de comparación en JavaScript son::
    1. Igualdad débil `(==)`: Compara dos valores después de convertirlos a un tipo de datos común.
    2. Igualdad estricta `(===)`: Compara dos valores sin realizar ninguna conversión de tipo.
    3. Mayor que `(>)`: Compara si el valor de la izquierda es mayor que el valor de la derecha.
    4. Menor o igual que `(<=)`: Compara si el valor de la izquierda es menor o igual que el valor de la derecha.

***4.¿Cuál es la diferencia entre los operadores lógicos “ `&&` “ y “ `||` “?***

- Algunos operadores de comparación en JavaScript son::
    1. El operador "`&&`" (AND) devuelve "`true`" si ambas expresiones son verdaderas. Si alguna de las expresiones es falsa, devuelve "`false`".
    2. El operador "`||`" (OR) devuelve "`true`" si al menos una de las expresiones es verdadera. Si ambas expresiones son falsas, devuelve "`false`".

#### Enlaces de Fuentes

- [Tomando decisiones en tu código — condicionales](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)

- [Marcadores y Repaso](https://chris.beams.io/posts/git-commit/)

## COSAS DE LAS QUE QUIERO SABER MAS

- Frameworks y bibliotecas
- Lenguajes del lado del servidor, puede ser útil para crear aplicaciones web más dinámicas y complejas.
- paginas en las que se pueden hacer ejercicios.
- paginas que muestren diversos estilos que podrian usarse con CSS, con ejemplos.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Perplexity)*

### Creacion

- Jueves 10 de Abril del 2024.

Enlace de este contenido [class-02](https://omartpiza.github.io/reading-notes/201/class-02)

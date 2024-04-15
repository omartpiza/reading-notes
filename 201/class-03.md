# LECTURA CLASE 3

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## APRENDE HTML
  
***1.¿Cuándo se puede utilizar una `lista no ordenada` en tu documento HTML?***

- Puedes utilizar una `lista no ordenada` en HTML cuando quieras presentar elementos que no necesitan estar secuenciados en un orden específico, como una lista de ítems sin una importancia relativa entre ellos. Esto es útil para crear una estructura visualmente clara de elementos que no tienen una jerarquía específica.

***2.¿Cómo cambias el `estilo bullet` de la lista de elementos no ordenados?***

- Para cambiar el estilo del bullet de una lista de elementos no ordenados en HTML, puedes utilizar CSS. Puedes hacerlo mediante la propiedad list-style-type. Ademas, puedes cambiar el bullet a un círculo (`list-style-type: circle;`), cuadrado (`list-style-type: square;`) o ningún bullet en absoluto (`list-style-type: none;`).

***3.¿Cuándo debes usar una `lista ordenada` o `lista no ordenada` en tu documento HTML?***

- Debes usar una lista ordenada (`<ol>`) cuando necesites presentar elementos en un orden secuencial o jerárquico, como pasos de un proceso, instrucciones numeradas o una lista clasificada. Por otro lado, debes usar una lista no ordenada (`<ul>`) cuando los elementos no necesiten seguir un orden específico y simplemente desees presentar una serie de ítems sin una secuencia definida, como una lista de características, puntos de discusión o elementos sin importancia relativa entre sí.

***4.Describe dos formas en las que puedes cambiar los números en los `elementos de la lista` proporcionados por una `lista ordenada`***

- Utilizando CSS: Puedes cambiar el estilo de los números de la lista ordenada utilizando la propiedad `list-style-type`. Por ejemplo, puedes cambiar los números a letras, romanos, o incluso imágenes personalizadas.

- Utilizando el atributo `type`: También puedes cambiar el tipo de numeración directamente en el HTML utilizando el atributo `type` en la etiqueta `<ol>`. Este atributo acepta diferentes valores, como `1` para números arábigos, `A` para letras mayúsculas, `a` para letras minúsculas, `I` para números romanos mayúsculos, `i` para números romanos minúsculos, entre otros. Por ejemplo:
  
#### Enlaces de Fuentes

- [Aprende HTML](https://developer.mozilla.org/es/docs/Web/HTML)

- [Ordenada](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

- [No Ordenada](https://developer.mozilla.org/es/docs/Web/HTML/Element/ul)

## APRENDE CSS

***1.Describe las propiedades de `margin` y `padding` en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?***

- En la historia del "Box Model", Margin y Padding son dos personajes que juegan roles distintos pero complementarios:
    1. `Margin`: es como el espacio entre los personajes en un escenario teatral. Es el espacio exterior que rodea al contenido del elemento, manteniendo una distancia entre él y otros elementos cercanos en la página. Margin es amable y considerado, siempre asegurándose de que haya suficiente espacio alrededor del contenido para que se destaque y respire.

    2. `Padding`: por otro lado, es como el relleno dentro de un regalo. Se encuentra dentro del borde del elemento y proporciona espacio adicional entre el contenido y el borde. Padding es como un abrazo cálido y acogedor para el contenido, asegurándose de que esté cómodo y protegido dentro del elemento.

***2.Enumera y describe las cuatro partes de un box del elementos HTML según el `box model`.***

1. `Content (Contenido)`:Esta es la parte principal del elemento y contiene el contenido real, como texto, imágenes o cualquier otro elemento HTML anidado. El tamaño del contenido se define por las propiedades de ancho (`width`) y alto (`height`).

2. `Padding (Relleno)`: El relleno es el espacio entre el contenido y el borde del elemento. Proporciona un espacio adicional alrededor del contenido y se define mediante las propiedades `padding-top`, `padding-right`, `padding-bottom` y `padding-left`. El relleno ayuda a mejorar la legibilidad y el diseño del contenido al proporcionar espacio en blanco adicional.

3. `Border (Borde)`: El borde es la línea que rodea el contenido y el relleno del elemento. Define los límites físicos del elemento y se puede personalizar con diferentes estilos, anchos y colores. Se define mediante las propiedades `border-width`, `border-style` y `border-color`.

4. `Margin (Margen)`: El margen es el espacio entre el borde del elemento y los elementos adyacentes. Proporciona separación entre elementos en el diseño de la página y se define mediante las propiedades `margin-top`, `margin-right`, `margin-bottom` y `margin-left`. Los márgenes ayudan a controlar el espacio entre los elementos y contribuyen al diseño general de la página.

#### Enlaces de Fuentes

- [Aprende CSS](https://developer.mozilla.org/es/docs/Learn/CSS)

- [The Box Model](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model)

## APRENDE JS

***1.¿Qué tipos de datos puedes almacenar en un `Array`?***

1. Números: Enteros, decimales, y valores NaN (Not a Number).

2. Cadenas de texto: Secuencias de caracteres.

3. Booleanos: Valores `true` o `false`.

4. Objetos: Cualquier tipo de objeto, incluyendo objetos predefinidos como `Date`, `RegExp`, y objetos personalizados.

5. Funciones: Declaraciones de funciones o funciones anónimas.

6. Otros Arrays: Arrays pueden contener otros arrays, creando estructuras de datos multidimensionales.

7. Valores `null`: Representa la ausencia intencionada de cualquier valor.

8. Valores `undefined`: Indica que una variable no ha sido asignada.

***2.¿El array `people` es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?***

```js
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];;
```  

- Sí, el array `people` es un array de JavaScript válido. Puedes acceder a los valores almacenados utilizando la notación de corchetes `[ ]`, indicando el índice del elemento que deseas acceder. Asimismo, puedes acceder a los valores individuales dentro de cada sub-array de la misma manera, utilizando índices adicionales.

***3.Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.***

1. `+=`: Este operador aumenta el valor de una variable sumándole otro valor y asigna el resultado a la variable original. 

2. `-=`: Este operador disminuye el valor de una variable restando otro valor y asigna el resultado a la variable original.

3. `*=`: Este operador multiplica el valor de una variable por otro valor y asigna el resultado a la variable original.

4. `/=`: Este operador divide el valor de una variable por otro valor y asigna el resultado a la variable original.

5. `%=`: Este operador calcula el módulo (resto de la división) del valor de una variable y otro valor, y asigna el resultado a la variable original.

***4.Lee el código a continuación, evalúa la últimaexpresión y explica cuál sería el resultado y por qué.***

```js
 let a = 10;
 let b = 'dog';
 let c = false;

 // evalúa esto
 (a + c) + b;
```  

- JavaScript primero evaluará la expresión dentro de los paréntesis `(a + c)`. Dado que a es un número `(10)` y c es un booleano `(false)`, JavaScript intentará convertir `c` a un número antes de realizar la suma. En JavaScript, `false` se convierte en `0` cuando se trata como un número en una operación aritmética.
Por esa razon, la expresión `(a + c)` se evaluará como `10 + 0`, que es igual a `10`. Por ultimo, se concatenará la cadena de texto `'dog'` al resultado de la suma anterior, `10`, resultando en `'10dog'`.
Y por ese motivo, el resultado de la expresión `(a + c) + b`; será `'10dog'`.

***5.Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.***

- Un ejemplo cotidiano pordira ser la construccion de un sitio web o una aplicación que requiera que los usuarios inicien sesión, se puede utilizar una declaración condicional para verificar si las credenciales proporcionadas por el usuario son válidas. Si las credenciales son correctas, se permite el acceso al sistema; de lo contrario, se muestra un mensaje de error y se impide el acceso. Esta declaración condicional ayuda a controlar el flujo del programa basado en una condición específica, en este caso, la validez de las credenciales del usuario, asegurando así la seguridad y la integridad del sistema (sistema de autenticacion de usuarios).

***6.Da un ejempo de por qué un Bucle es últil en JavaScript.***

- Un bucle es útil en JavaScript cuando necesitas repetir una acción varias veces. Por ejemplo, para iterar sobre elementos de una lista o matriz y realizar una operación en cada uno de ellos, como calcular la suma de una lista de números. Esto simplifica y hace más eficiente el proceso de trabajar con conjuntos de datos grandes. Se utlizaria el bucle `for` que itera sobre cada elemento en la `matriz` y suma cada número al valor de `sum`, resultando en la suma total de todos los números en la lista.

#### Enlaces de Fuentes

- [Aprende JS](https://developer.mozilla.org/es/docs/Learn/JavaScript)

- [Arrays](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/Arrays)

- [Operadores y Expresiones](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators)

- [Condicionales](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/conditionals)

- [Bucles](https://developer.mozilla.org/es/docs/Learn/JavaScript/Building_blocks/Looping_code)

## COSAS DE LAS QUE QUIERO SABER MAS

- Formularios y Validación, Dominar la creación y validación de formularios para mejorar la experiencia del usuario.
- Organización del Código, Adoptar prácticas de código limpio y modular para escribir y mantener código de manera eficiente.
- Gestión de Eventos en JavaScript, Aprender a responder a las interacciones del usuario de forma dinámica y fluida.
- CSS Avanzado, Aprender sobre flexbox y CSS Grid para crear diseños complejos de manera más eficiente.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Lunes 15 de Abril del 2024.

Enlace de este contenido [class-03](https://omartpiza.github.io/reading-notes/201/class-03)
# LECTURA CLASE 6

- El siguiente contenido es importante para este modulo ya que nos permite conocer los conceptos e informacion que nos serviran para el llevar con exito los laboratorios y test de este CODE 201.
A continuación se muestran las principales preguntas de una colección de recursos que describen los temas para la proxima clase:

## DESCRIPCIÓN DEL PROBLEMA, OBEJETOS Y EL DOM
  
***1.¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?***

- "Imagina una caja negra que puede hacer muchas cosas cuando le das instrucciones. Dentro de esta caja, hay piezas que trabajan juntas para realizar tareas específicas. Puedes decirle qué hacer escribiendo un conjunto de instrucciones en un idioma especial llamado código.
Por ejemplo, puedes pedirle que sume números, guarde información o muestre cosas en una pantalla. Es como tener un asistente que hace lo que tú le dices, pero solo entiende un idioma muy específico: el código de programación."

***2.¿Cuáles son algunas de las ventajas de crear objetos literales?***

- Las ventajas principales de crear obejetos son:

1. Sencillez y claridad: Son fáciles de entender y escribir.

2. Flexibilidad: Se adaptan fácilmente a diferentes necesidades.

3. Legibilidad: Su estructura es clara y fácil de entender.

4. Rendimiento: En algunos casos, pueden ser más eficientes que otras formas de crear objetos.

5. Uso en estructuras de datos simples: Son ideales para representar datos simples como diccionarios o registros.

***3.¿En qué se diferencian los objetos de los arrays?***

1. Objetos: Los objetos son colecciones de pares clave-valor donde cada valor se accede a través de una clave única. Cada par clave-valor en un objeto se denomina propiedad. Las propiedades de un objeto pueden contener cualquier tipo de dato, incluidos otros objetos, funciones y arrays. Se definen utilizando llaves `{}`.Por ejemplo:

    ```js
    let persona = {
    nombre: "Juan",
    edad: 30,
    ciudad: "Madrid"
    };
    ```  

2. Arrays: Los arrays son listas ordenadas de valores. Cada elemento en un array tiene una posición numérica conocida como índice, comenzando desde 0. Los elementos de un array pueden ser de cualquier tipo de dato, incluidos otros arrays y objetos. Se definen utilizando corchetes `[]`.Por ejemplo:

    ```js
    let frutas = ["manzana", "plátano", "naranja"];
    ```  


***4.Da un ejemplo acerca de los momentos en los que necesitarías utilizar `bracket notation` para acceder a la propiedad de un objeto en vez de `dot notation`.***

- Si se tiene un objeto que representa información sobre un estudiante, incluyendo sus calificaciones en diferentes materias. Algunas materias pueden tener nombres que contienen espacios, como "Ciencias de la Computación". Si intentas acceder a la calificación de esta materia utilizando la notación de punto, podrías encontrar un error debido a los espacios en el nombre de la propiedad. En estos casos, necesitarías utilizar la notación de corchetes para acceder correctamente a la propiedad del objeto. Por ejemplo:

    ```js
    let estudiante = {
        nombre: "Juan",
        edad: 20,
        "Ciencias de la Computación": 90
        };

        // Accediendo a la calificación utilizando la notación de punto (incorrecto debido al espacio)
        console.log(estudiante.Ciencias de la Computación); // Error de sintaxis

        // Accediendo a la calificación utilizando la notación de corchetes (correcto)
        console.log(estudiante["Ciencias de la Computación"]); // Imprime: 90
    ```

- En este caso, la notación de corchetes es necesaria para acceder a la propiedad correctamente debido a los espacios en el nombre de la materia.

***5.Evalúa el siguiente código. ¿A qué se refiere el término `this` y cuál es la ventaja de utilizarlo?***

```js
    const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
    }
    }   
```  

- En este código, `this` se refiere al objeto `dog`. La ventaja de utilizar `this` es que te permite acceder a las propiedades del objeto en el que se está ejecutando el método, haciendo que el código sea más flexible y reutilizable.
  
#### Enlaces de Fuentes

- [Conceptos básicos de los objetos JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/Basics)

## INTRODUCCION AL DOM

***1.¿Qué es el DOM?***

- El `DOM` (Document Object Model, por sus siglas en inglés) es una representación estructurada de un documento HTML (o XML) que proporciona una forma de interactuar y manipular los elementos de dicho documento. En esencia, el `DOM` convierte un documento HTML en un conjunto de objetos que pueden ser accedidos y modificados mediante programación.

***2.Describe brevemente la relación entre el DOM y JavaScript.***

- JavaScript y el DOM están conectados: JavaScript es un lenguaje que permite interactuar con el DOM, que es una representación estructurada de una página web. JavaScript puede modificar y manipular los elementos de la página web a través del DOM, lo que permite crear páginas web dinámicas e interactivas.

#### Enlaces de Fuentes

- [Introducción al DOM](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction)

## MARCADORES Y RESPASO

#### Enlaces de Fuentes

- [¿Por qué parece tan difícil programar?](https://www.uv.es/vimupi/programar.html)

- [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## COSAS DE LAS QUE QUIERO SABER MAS

- Interacción entre objetos y DOM: Cómo JavaScript trabaja con el DOM para crear páginas web dinámicas.
- Manipulación del DOM: Cómo JavaScript modifica los elementos de una página web, añade nuevos elementos y responde a eventos.
- Notación de punto vs. corchetes: Cuándo utilizar cada una para acceder a propiedades de objetos en JavaScript.
- Uso de "this": Cómo y cuándo usar la palabra clave "this" en JavaScript para referirse al objeto actual en el que se está ejecutando el código.

### Autor

  Omar Torbisco: [omartpiza](https://github.com/omartpiza)`(GitHub)`

###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Jueves 25 de Abril del 2024.

Enlace de este contenido [class-06](https://omartpiza.github.io/reading-notes/201/class-06)
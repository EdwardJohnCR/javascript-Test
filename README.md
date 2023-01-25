##Test de JavaScript

#### este test lo resolvi con ayuda de **platzi y chat GPT**

¡Es hora de poner a prueba cuánto sabes sobre JavaScript!

Esta lectura es una prueba de JavaScript. A diferencia de un examen, nadie te obligará a nada. Puedes hacer trampa y saltar a la siguiente clase, ese es el camino fácil. Pero tengo mucha fe en ti, confío en que seguirás mis consejos y no avanzarás a la siguiente clase hasta superar esta prueba.

Instrucciones para tomar esta prueba
Evalúa muy críticamente tu conocimiento.
Si logras resolver la prueba, no importa cuánto te cueste, puedo asegurarte que tienes todo para continuar a las siguientes clases y tomar el resto del curso.
Si no lo logras, no te preocupes, absolutamente nadie puede juzgarte, solo tú. Vuelve al [Curso Básico de JavaScript](https://platzi.com/cursos/basico-javascript/), anota los temas clave donde puedes mejorar, ubica las clases donde puedes aprenderlos y estudia vigorosamente.
Es completamente válido hacer búsquedas en Google, cursos y tutoriales de Platzi, incluso usar tu cuaderno de notas sin importar si es físico o virtual.
Recuerda que el éxito no se mide por cuánto tiempo te toma aprender, esa métrica es relativamente inútil. Mejor concéntrate en completar los cursos de tu ruta de aprendizaje profesional y desarrollar los proyectos que realmente demuestran que dominas cada tecnología.

¡Mucha suerte!

## **Variables y operaciones**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es una variable y para qué sirve?

> Una variable es un espacio reservado en la memoria del computador para almacenar un valor o un conjunto de valores. En programación, las variables son utilizadas para representar información que puede cambiar durante la ejecución de un programa. Cada variable tiene un nombre único y un tipo de datos asociado, como números, cadenas de texto o valores booleanos.
>
>Las variables son utilizadas para almacenar información y para ser utilizadas en diferentes partes del programa, permitiendo su uso en operaciones aritméticas, comparaciones, almacenamiento temporal, entre otras acciones. Sirven para hacer que el código sea más legible y fácil de mantener, ya que en lugar de utilizar valores constantes se puede utilizar el nombre de una variable para hacer referencia a ese valor.

- ¿Cuál es la diferencia entre declarar e inicializar una variable?

>Declarar una variable significa reservar un espacio en la memoria para almacenar un valor y darle un nombre y un tipo de datos. Por ejemplo, en el lenguaje de programación Javascript, se declara una variable de enteros de la siguiente manera:
>
> _code_
>**let edad;**
>
>En este caso, se está reservando un espacio en la memoria para almacenar un valor entero y se le está dando el nombre "edad".
>
>Por otro lado, inicializar una variable significa asignar un valor inicial a una variable previamente declarada. Por ejemplo, en el siguiente código se está inicializando la variable "edad" con el valor 25:
>
> _code_
>**edad = 25;**
>
>En este caso, se está asignando el valor 25 a la variable "edad" previamente declarada.
>
>En resumen, declarar una variable es reservar un espacio en la memoria para almacenar un valor y darle un nombre y un tipo de datos; mientras que inicializar una variable es darle un valor inicial a una variable previamente declarada. Es importante recordar que no siempre es necesario inicializar una variable, pero siempre es necesario declararla antes de usarla.

- ¿Cuál es la diferencia entre sumar números y concatenar strings?

>La principal diferencia entre sumar números y concatenar strings es que la suma es una operación aritmética y la concatenación es una operación de cadenas de texto.
>
>Cuando se suman dos números, se está realizando una operación aritmética que devuelve un valor numérico. Por ejemplo, en el lenguaje de programación Java, el siguiente código suma dos números:
>
> _code_
>**let num1 = 5;**
>**let num2 = 3;**
>**let resultado = num1 + num2;**
>
>En este caso, la variable "resultado" tendría el valor 8 (5+3).
>
>Por otro lado, cuando se concatenan dos strings, se está uniendo una cadena de texto con otra para formar una nueva cadena. Por ejemplo, en Java el siguiente código concatena dos cadenas de texto:
>
> _code_
>**String saludo = "Hola";**
>**String nombre = "Juan";**
>**String mensaje = saludo + " " + nombre;**
>
>En este caso, la variable "mensaje" tendría el valor "Hola Juan". Es importante notar que en la mayoría de los lenguajes de programación existe un operador específico para concatenar strings, en el caso de java es el operador "+" pero en otros lenguajes puede ser otro.

- ¿Cuál operador me permite sumar o concatenar?

>En la mayoría de los lenguajes de programación el operador "+" es utilizado tanto para sumar números como para concatenar strings. Sin embargo, el comportamiento del operador depende del tipo de datos con los que se esté trabajando.
>
>Cuando se utiliza el operador "+" entre dos valores numéricos, se realiza una operación aritmética de suma. Por ejemplo, en el lenguaje de programación javascript, el siguiente código suma dos números:
>
> _code_
>**let num1 = 47;**
>**let num2 = 33;**
>**let resultado = num1 + num2;**
>
>En este caso, la variable "resultado" tendría el valor 80 (47+33).
>
>Por otro lado, cuando se utiliza el operador "+" entre dos cadenas de texto, se realiza una operación de concatenación de cadenas. Por ejemplo, en javascript el siguiente código concatena dos cadenas de texto:
>
> _code_
>**String saludo = "Hola";**
>**String nombre = "Juan";**
>**String mensaje = saludo + " " + nombre;**
>
>En este caso, la variable "mensaje" tendría el valor "Hola Juan".
>
>Es importante notar que en algunos lenguajes de programación existe un operador específico para concatenar strings, como el operador + en javascript


### 2️⃣ Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

- Nombre
    * **strings**
- Apellido
    * **strings**
- Nombre de usuario en Platzi
    * **strings**
- Edad
    * **numerico**      
- Correo electrónico
    * **strings**
- Mayor de edad
    * **numerico**
- Dinero ahorrado
    * **numerico**
- Deudas
    * **numerico**

### 3️⃣ Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.

### 4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

Nombre completo (nombre y apellido)
Dinero real (dinero ahorrado menos deudas)
Funciones

## 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es una función?

>Una función es un bloque de código que se puede ejecutar varias veces, con el propósito de realizar una tarea específica. Estas funciones son reutilizables y pueden recibir parámetros y devolver un resultado.
>La principal ventaja de las funciones es que permite separar el código en partes más pequeñas y manejables, lo que facilita la comprensión, el mantenimiento y la depuración del código. Además, ayudan a evitar la repetición de código y mejoran la modularidad del programa.
>En resumen, una función es un conjunto de instrucciones que realizan una tarea específica y se pueden invocar cuando sea necesario, permitiendo así una mejor organización y reutilización del código.

- ¿Cuándo me sirve usar una función en mi código?

>Existen varias situaciones en las que es útil usar funciones en tu código:

>* Cuando un bloque de código se va a utilizar varias veces en diferentes partes del programa: al encapsular ese código en una función, se puede llamar a la función en lugar de repetir el código cada vez.
>* Cuando quieres organizar tu código en bloques lógicos: las funciones te permiten dividir tu código en secciones que realizan tareas específicas, lo que facilita la comprensión y el mantenimiento del programa.
>* Cuando quieres aceptar parámetros y devolver resultados: las funciones te permiten recibir parámetros para personalizar su comportamiento y devolver resultados para ser utilizados por otras partes del programa.
>* Cuando quieres crear una abstracción sobre un bloque de código: las funciones te permiten envolver un

- ¿Cuál es la diferencia entre parámetros y argumentos de una función?

>La diferencia entre parámetros y argumentos en una función radica en el momento en el que se especifican.
>
>Los parámetros son las variables que se especifican en la definición de una función. Son los "placeholders" o "variables de entrada" de la función, ya que indican los valores que se esperan recibir cuando se llama a la función. Por ejemplo, en la función siguiente:
>
> _code_
>**function suma(a, b) {**
    >**return a + b;**
>**}**
>
>Los parámetros son "a" y "b".
>
>Los argumentos son los valores reales que se pasan a una función cuando se llama. Estos argumentos se asignan a los parámetros correspondientes en la función. Por ejemplo, en el siguiente código se está llamando a la función "suma" y pasando los argumentos 3 y 4:

> _code_
>**suma(3, 4);**
>
>Los argumentos son 3 y 4.
>
>En resumen, los parámetros son los "placeholders"

> _NOTA_
>"Placeholder" es un término en inglés que se refiere a un lugar reservado en un texto o código donde se espera que se inserten valores específicos en el futuro. En el contexto de programación, los parámetros de una función son placeholders o lugares reservados para recibir valores específicos (argumentos) cuando se llama a la función. Los parámetros son variables declaradas en la definición de una función y se utilizan como "entradas" para la función, mientras que los argumentos son los valores reales que se pasan a la función en el momento de la llamada.

### 2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:

const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");
Condicionales

> _code_
>**function nombreCompleto(name, lastname, nickname) {**
  >**const completeName = name + lastname;**
  >**console.log("Mi nombre es " + completeName + ", pero       prefiero que me digas " + nickname + ".");**
>**}**
>
>En este código, se define una función llamada "nombreCompleto", que recibe 3 parámetros: "name", "lastname" y "nickname", que son utilizados para construir el nombre completo y el nickname, y luego se usa console.log para imprimir el mensaje en pantalla.
>En lugar de usar variables constantes, se usan los parámetros de la función, esto permite que la función pueda ser reutilizada con diferentes valores de nombre, apellido y nickname.
>Por ejemplo, si queremos imprimir "Mi nombre es Juan David Castro Gallego, pero prefiero que me digas juandc.":
>
> _code_
>**nombreCompleto("Juan David","Castro Gallego","juandc");**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es un condicional?
- ¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?
- ¿Puedo combinar funciones y condicionales?

###  2️⃣ Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:
const tipoDeSuscripcion = "Basic";

switch (tipoDeSuscripcion) {
   case "Free":
       console.log("Solo puedes tomar los cursos gratis");
       break;
   case "Basic":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
       break;
   case "Expert":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
       break;
   case "ExpertPlus":
       console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año");
       break;
}

### 3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).
💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏

## **Ciclos**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un ciclo?
¿Qué tipos de ciclos existen en JavaScript?
¿Qué es un ciclo infinito y por qué es un problema?
¿Puedo mezclar ciclos y condicionales?

## 2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:

for (let i = 0; i < 5; i++) {
    console.log("El valor de i es: " + i);
}

>**let i = 0;**
>**while (i < 5) {**
>**i++;**
>**console.log("El valor de i es: " + i);**
>**}**


for (let i = 10; i >= 2; i--) {
    console.log("El valor de i es: " + i);
}

>**let i = 10;**
>**while (i >= 2) {**
>**i--;**
>**console.log("El valor de i es: " + i);**
>**}**


## 3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.
_💡 Pista: puedes usar la función prompt de JavaScript._

>**let respuesta = parseInt(prompt("¿Cuánto es 2 + 2?"));**
>
>**while (respuesta !== 4) {**
>    **alert("Incorrecto, vuelve a intentarlo.");**
>    **respuesta = parseInt(prompt("¿Cuánto es 2 + 2?"));**
>**}**
>
>**alert("¡Felicidades, la respuesta es correcta!");**
>
>En este código, se utiliza el método "prompt" para pedir al usuario que ingrese un valor. Luego, se utiliza un ciclo while que se repite mientras la respuesta del usuario sea diferente a **4**, si la respuesta es correcta la condición del ciclo while no se cumple y el código continua y muestra un mensaje de felicitaciones.

## **Listas**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es un array?

- ¿Qué es un objeto?

- ¿Cuándo es mejor usar objetos o arrays?

- ¿Puedo mezclar arrays con objetos o incluso objetos con arrays?

## 2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.

>**function imprimirPrimerElemento(arr) {**
  >**console.log(arr[0]);**
>**}**
>En este código se define una función llamada "imprimirPrimerElemento" que recibe un parámetro llamado "arr". La función utiliza console.log para imprimir en pantalla el primer elemento del array, el cual se accede con la notación [0], ya que los índices en los arrays empiezan en 0. Por ejemplo:
>
> _code_
>**let miArray = [1, 2, 3, 4, 5];**
>**imprimirPrimerElemento(miArray);**
>
>Imprimiría el primer elemento del array que es 1.

## 3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).

## 4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).


¿Cómo te fue? 🏆

¡Felicidades por completar la prueba de JavaScript! Confío en que hayas completado cada paso y hayas pausado para repasar los temas de los ejercicios que se te complicaron.


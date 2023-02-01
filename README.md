# Test de JavaScript

######  Yo use Platzi y chat GPT en las soluciones!    ![logo JavaScript](https://static.platzi.com/cdn-cgi/image/width=1024,quality=50,format=auto/media/achievements/badge-basicojs-e2ead888-428e-4f55-962c-8894aeaeacda.png)


 Es hora de poner a prueba cuánto sabes sobre JavaScript!
 ==

Esta lectura es una prueba de JavaScript. A diferencia de un examen, nadie te obligará a nada. Puedes hacer trampa y saltar a la siguiente clase, ese es el camino fácil. Pero tengo mucha fe en ti, confío en que seguirás mis consejos y no avanzarás a la siguiente clase hasta superar esta prueba.

Instrucciones para tomar esta prueba
Evalúa muy críticamente tu conocimiento.
Si logras resolver la prueba, no importa cuánto te cueste, puedo asegurarte que tienes todo para continuar a las siguientes clases y tomar el resto del curso.
Si no lo logras, no te preocupes, absolutamente nadie puede juzgarte, solo tú. Vuelve al [Curso Básico de JavaScript](https://platzi.com/cursos/basico-javascript/), anota los temas clave donde puedes mejorar, ubica las clases donde puedes aprenderlos y estudia vigorosamente.
Es completamente válido hacer búsquedas en Google, cursos y tutoriales de Platzi, incluso usar tu cuaderno de notas sin importar si es físico o virtual.
Recuerda que el éxito no se mide por cuánto tiempo te toma aprender, esa métrica es relativamente inútil. Mejor concéntrate en completar los cursos de tu ruta de aprendizaje profesional y desarrollar los proyectos que realmente demuestran que dominas cada tecnología.

¡Mucha suerte!
___



## **Variables y operaciones**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es una variable y para qué sirve?

> Una variable es un espacio reservado en la memoria del computador para almacenar un valor o un conjunto de valores. En programación, las variables son utilizadas para representar información que puede cambiar durante la ejecución de un programa. Cada variable tiene un nombre único y un tipo de datos asociado, como números, cadenas de texto o valores booleanos.
>
>Las variables son utilizadas para almacenar información y para serutilizadas en diferentes partes del programa, permitiendo su uso enoperaciones aritméticas, comparaciones, almacenamiento temporal, entre otras acciones. Sirven para hacer que el código sea más legibley fácil de mantener, ya que en lugar de utilizar valores constantes se puede utilizar el nombre de una variable para hacer referencia a ese valor.

- ¿Cuál es la diferencia entre declarar e inicializar una variable?

>Declarar una variable significa reservar un espacio en la memoria para almacenar un valor y darle un nombre y un tipo de datos. Por ejemplo, en el lenguaje de programación Javascript, se declara una variable de enteros de la siguiente manera:

 `code`
```js
let edad;
```
>En este caso, se está reservando un espacio en la memoria para 
>almacenar un valor entero y se le está dando el nombre "edad".
>
>Por otro lado, inicializar una variable significa asignar un valor inicial a una variable previamente declarada. Por ejemplo, en el siguiente código se está inicializando la variable "edad" con el valor 25:

`code`
```js
edad = 25;
```
>En este caso, se está asignando el valor 25 a la variable "edad" previamente declarada.
>
>En resumen, declarar una variable es reservar un espacio en lamemoria para almacenar un valor y darle un nombre y un tipo de datos; mientras que inicializar una variable es darle un valor inicial a una variable previamente declarada. Es importante ecordar que no siempre es necesario inicializar una variable, pero siempre es necesario declararla antes de usarla.

- ¿Cuál es la diferencia entre sumar números y concatenar strings?

>La principal diferencia entre sumar números y concatenar strings es que la suma es una operación aritmética y la concatenación es una operación de cadenas de texto.
>
>Cuando se suman dos números, se está realizando una operación aritmética que devuelve un valor numérico. Por ejemplo, en el lenguaje de programación javascript, el siguiente código suma dos números:

 `code`
```js
let num1 = 5
let num2 = 3;
let resultado = num1 + num2;
```

>En este caso, la variable "resultado" tendría el valor 8 (5+3).
>
>Por otro lado, cuando se concatenan dos strings, se está uniendo una cadena de texto con otra para formar una nueva cadena. 
>Por ejemplo, en JavaScript el siguiente código concatena dos cadenas de texto:

 `code`
```js
String saludo = "Hola";
String nombre = "Juan";
String mensaje = saludo + " " + nombre;
```

>En este caso, la variable "mensaje" tendría el valor "Hola Juan". 
>Es importante notar que en la mayoría de los lenguajes de programación existe un operador específico para concatenar strings,en el caso de java es el operador "+" pero en otros lenguajes puede ser otro.

- ¿Cuál operador me permite sumar o concatenar?

>En la mayoría de los lenguajes de programación el operador "+" es utilizado tanto para sumar números como para concatenar strings. 
>Sin embargo, el comportamiento del operador depende del tipo de datos con los que se esté trabajando.
>
>Cuando se utiliza el operador "+" entre dos valores numéricos, se realiza una operación aritmética de suma. Por ejemplo, en el lenguaje de programación javascript, el siguiente código suma dos números:

 `code`
```js
let num1 = 47;
let num2 = 33;
let resultado = num1 + num2;
```

>En este caso, la variable "resultado" tendría el valor 80 (47+33).
>

>Por otro lado, cuando se utiliza el operador "+" entre dos cadenas de texto, se realiza una operación de concatenación de cadenas. 
>Por ejemplo, en javascript el siguiente código concatena dos cadenas de texto:

 `code`
```js
String saludo = "Hola";
String nombre = "Juan";
String mensaje = saludo + " " + nombre;
```

>En este caso, la variable "mensaje" tendría el valor "Hola Juan".
>
>Es importante notar que en algunos lenguajes de programación existe un operador específico para concatenar strings, como el operador + en javascript


### 2️⃣ Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

- Nombre
    * **string**
- Apellido
    * **string**
- Nombre de usuario en Platzi
    * **string**
- Edad
    * **number**      
- Correo electrónico
    * **string**
- Mayor de edad
    * **boolean**
- Dinero ahorrado
    * **number**
- Deudas
    * **number**

### 3️⃣ Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.

 `code`
```js
let nombre = "Edward";
let Apelliso = "Rodriguez";
ler username = "EJ"
let Edad = 43;
let mail = "ej@edward.com";
let adult = "true";
let saving = $100;
let debts = $99
```

### 4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:

Nombre completo (nombre y apellido)
Dinero real (dinero ahorrado menos deudas)

 `code`
```js
let nombre = "Edward";
let Apellido = "Rodriguez"
let saving = 100;
let debts = 99;
let fullName = nombre +" "+ Apellido;
let money = saving - debts;
console.log( "El señor " + fullName + " tiene un monto de $"+ money);
```

>Este código asigna valores a las variables "nombre", "Apellido", "saving" y "debts". Luego, se concatenan los valores de "nombre" y "Apellido" para crear una nueva variable "fullName" y se calcula la diferencia entre "saving" y "debts" para crear una nueva variable "money". Finalmente, se utiliza la función "console.log()" para imprimir una cadena de texto junto con los valores de "fullName" y "money" en la consola.

## Funciones

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es una función?

>Una función es un bloque de código que se puede ejecutar varias veces, con el propósito de realizar una tarea específica. Estas funciones son reutilizables y pueden recibir parámetros y devolver un resultado.
>
>La principal ventaja de las funciones es que permite separar el código en partes más pequeñas y manejables, lo que facilita la comprensión, el mantenimiento y la depuración del código. Además, ayudan a evitar la repetición de código y mejoran la modularidad del programa.
>
>En resumen, una función es un conjunto de instrucciones que realizan una tarea específica y se pueden invocar cuando sea necesario, permitiendo así una mejor organización y reutilización del código.

- ¿Cuándo me sirve usar una función en mi código?

>Usar funciones en el código puede tener varios beneficios. Algunos de ellos son:
>
>Reutilización de código: Una función puede ser llamada varias veces en diferentes partes del código, lo que permite evitar escribir código repetitivo y aumenta la legibilidad.
>
>Abstracción: Al encapsular cierta lógica en una función, se puede ocultar la complejidad de esa lógica detrás de un nombre intuitivo, lo que facilita la comprensión y el mantenimiento del código.
>
>Modularidad: Al dividir un programa en funciones independientes, se pueden trabajar en diferentes partes del código de manera aislada y, si es necesario, intercambiarlas o reutilizarlas en otros programas.
>
>Probar y depurar: Es más fácil probar y depurar una función aislada que una gran cantidad de código.
>
>Flexibilidad: Al pasar diferentes argumentos a una función, se pueden obtener diferentes resultados.


- ¿Cuál es la diferencia entre parámetros y argumentos de una función?

>La diferencia entre parámetros y argumentos en una función radica en el momento en el que se especifican.
>
>Los parámetros son las variables que se especifican en la definición de una función. Son los "placeholders" o "variables de entrada" de la función, ya que indican los valores que se esperan recibir cuando se llama a la función. Por ejemplo, en la función siguiente:

 `code`
```js
function suma(a, b) {
return a + b;
}
```

>Los parámetros son "a" y "b".
>
>Los argumentos son los valores reales que se pasan a una función cuando se llama. Estos argumentos se asignan a los parámetros correspondientes en la función. Por ejemplo, en el siguiente código se está llamando a la función "suma" y pasando los argumentos 3 y 4:

 `code`
```js
suma(3, 4);
```

>Los argumentos son 3 y 4.
>
>En resumen, los parámetros son los "placeholders"

_NOTA_
>"Placeholder" es un término en inglés que se refiere a un lugar reservado en un texto o código donde se espera que se inserten valores específicos en el futuro. En el contexto de programación, los parámetros de una función son placeholders o lugares reservados para recibir valores específicos (argumentos) cuando se llama a la función. Los parámetros son variables declaradas en la definición de una función y se utilizan como "entradas" para la función, mientras que los argumentos son los valores reales que se pasan a la función en el momento de la llamada.

### 2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando  sea necesario las variables constantes por parámetros y argumentos en una función:

const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");

`code`
```js
function nombreCompleto(name, lastname, nickname) {
const completeName = name + lastname;
    console.log("Mi nombre es " + completeName + ", per prefiero que me digas " + 
nickname + ".");
}
```

>En este código, se define una función llamada "nombreCompleto", que recibe 3 parámetros: "name", "lastname" y "nickname", que son utilizados para construir el nombre completo y el nickname, y luego se usa console.log para imprimir el mensaje en pantalla.En lugar de usar variables constantes, se usan los parámetros de la función, esto permite que la función pueda ser reutilizada con diferentes valores de nombre, apellido y nickname.
>Por ejemplo, si queremos imprimir "Mi nombre es Juan David Castro Gallego, pero prefiero que me digas juandc.":

`code`
```js
nombreCompleto("Juan David","Castro Gallego","juandc");

```
## Condicionales

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es un condicional?

>Un condicional es una estructura de control de flujo en programación que permite ejecutar un bloque de código solo si se cumple una determinada condición. 
>Los condicionales suelen utilizar operadores de comparación para evaluar una >expresión y determinar si se cumple o no la condición. Si la condición se cumple, se ejecuta el bloque de código dentro del condicional, y si no se cumple, se puede elegir no ejecutar nada o ejecutar un bloque diferente de código. 
>Los condicionales más comunes son if-else, switch-case.

- ¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?

>Existen varios tipos de condicionales en JavaScript, los más comunes son:
>
>if-else: Este es el condicional más básico en JavaScript. Se utiliza para ejecutar un bloque de código si se cumple una determinada condición, y otro bloque de código si no se cumple.
>
>if-else if-else: Este condicional es similar al anterior, pero permite especificar varias condiciones adicionales con una estructura de ramificación.
>
>switch-case: Este condicional es útil para comparar una variable con varios valores específicos y ejecutar diferentes bloques de código dependiendo del valor de la variable.
>
>ternary operator : Es un operador condicional de una sola línea, se utiliza para asignar valores a una variable dependiendo de una condición. Es una forma más corta de escribir un if-else
>
>La principal diferencia entre ellos es la forma en que se evalúan las condiciones y se ejecutan los bloques de código. El if-else y if-else if-else se utilizan para evaluar una o varias condiciones y ejecutar bloques de código en función de si se cumplen o no. El switch-case, se utiliza para comparar una variable con varios valores específicos y ejecutar diferentes bloques de código dependiendo del valor de la variable. Y el ternary operator, es una forma más corta de escribir un if-else.

- ¿Puedo combinar funciones y condicionales?

>Sí, es posible combinar funciones y condicionales en JavaScript. De hecho, es común utilizar condicionales dentro de funciones para controlar el flujo de ejecución del código.
>
>Por ejemplo, se puede crear una función que toma una variable como parámetro y utiliza un condicional para determinar si el valor es mayor o menor que un número específico. Dependiendo del resultado, la función puede devolver un valor o imprimir un mensaje en la consola.
>
>También se puede crear una función que utiliza un condicional para decidir qué otra función llamar. Es posible llamar una función dentro de otra función.
>
>En resumen, los condicionales y las funciones son herramientas muy poderosas de programación que se complementan entre sí y se pueden utilizar juntos para controlar el flujo de ejecución del código y organizar el código de manera eficiente.


###  2️⃣ Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:

```js
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
       console.log("Tú y alguien más pueden tomar TODOS los cursos de 
        Platzi durante un año");
       break;
}
```
___

`code`
```js
const tipoDeSuscripcion = "Basic";

if (tipoDeSuscripcion === "Free") {
console.log("Solo puedes tomar los cursos gratis");

} else if (tipoDeSuscripcion === "Basic") {
console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");

} else if (tipoDeSuscripcion === "Expert") {
console.log("Puedes tomar casi todos los cursos de Platzi durante un año");

} else if (tipoDeSuscripcion === "ExpertPlus") {
console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi 
    durante un año");

} else {
console.log("Tipo de suscripción no válida");
}
```

>La estructura if-else if-else es similar a la sentencia switch, ya que ambas permiten evaluar varias condiciones y ejecutar diferentes bloques de código dependiendo del valor de una variable. Sin embargo, la sentencia switch tiene algunas ventajas sobre if-else if-else, ya que puede ser más fácil de leer y escribir en algunos casos.

### 3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).

`code`
```js
const tipoDeSuscripcion = "Basic";

if (tipoDeSuscripcion === "Free") {
    console.log("Solo puedes tomar los cursos gratis");
    return;
}

if (tipoDeSuscripcion === "Basic") {
    console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
    return;
}

if (tipoDeSuscripcion === "Expert") {
    console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
    return;
}

if (tipoDeSuscripcion === "ExpertPlus") {
    console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año");
    return;
}

if (tipoDeSuscripcion !== "Free" && tipoDeSuscripcion !== "Basic" && tipoDeSuscripcion !== "Expert" && tipoDeSuscripcion !== "ExpertPlus") {
    console.log("Tipo de suscripción no válida");
    return;
}
```

___
### 💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏

>Podrías crear un array o un objeto con la información de los diferentes tipos de suscripción, y luego utilizar un solo condicional para comparar el tipo de suscripción que tiene el usuario con las opciones del array o objeto. Por ejemplo:

```js
// Array con los tipos de suscripción

const suscripciones = [
{tipo: "Free", descripcion: "Solo puedes tomar los cursos gratis"},
{tipo: "Basic", descripcion: "Puedes tomar casi todos los cursos de Platzi 
    durante un mes"},
{tipo: "Expert", descripcion: "Puedes tomar casi todos los cursos de Platzi 
    durante un año"},
{tipo: "ExpertPlus", descripcion: "Tú y alguien más pueden tomar TODOS los 
    cursos de Platzi durante un año"}
];

const tipoDeSuscripcion = "Basic";
let descripcion;

// Iteramos sobre el array para encontrar el tipo de suscripcion
for (let i = 0; i < suscripciones.length; i++) {
if (suscripciones[i].tipo === tipoDeSuscripcion) {
descripcion = suscripciones[i].descripcion;
break;
}
}

console.log(descripcion); // Puedes tomar casi todos los cursos de Platzi durante un mes
```

>También se puede usar la estructura de objeto para almacenar las 
>suscripciones en lugar de un array

`code`
```js
const suscripciones = {
Free: "Solo puedes tomar los cursos gratis",
Basic: "Puedes tomar casi todos los cursos de Platzi durante un mes",
Expert: "Puedes tomar casi todos los cursos de Platzi durante un año",
ExpertPlus: "Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año"
};

const tipoDeSuscripcion = "Basic";
let descripcion = suscripciones[tipoDeSuscripcion];
console.log(descripcion); // Puedes tomar casi todos los cursos de Platzi durante un mes
```

>Se puede replicar este comportamiento utilizando un objeto con claves que representen los diferentes tipos de suscripción y valores que representen los mensajes a imprimir:

`code`
```js
const tipoDeSuscripcion = "Basic";

const suscripciones = {
  Free: "Solo puedes tomar los cursos gratis",
  Basic: "Puedes tomar casi todos los cursos de Platzi durante un mes",
  Expert: "Puedes tomar casi todos los cursos de Platzi durante un año",
  ExpertPlus: "Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año",
};

console.log(suscripciones[tipoDeSuscripcion] || "Tipo de suscripción no válida");
```

>Con esto, se evita tener que utilizar varias condicionales para determinar qué mensaje imprimir. En su lugar, se puede acceder directamente al valor correspondiente en el objeto. Si la clave no existe en el objeto, el resultado será undefined, por lo que se puede utilizar el operador || para imprimir un mensaje de "Tipo de suscripción no válida".

___

## **Ciclos**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es un ciclo?

>Un ciclo es una estructura de control de un programa que permite repetir un bloque de código una o varias veces, dependiendo de una condición dada. 
>Los ciclos son también conocidos como bucles o loops. Los ciclos se utilizan para automatizar tareas repetitivas, para recorrer elementos de una colección, etc. Los lenguajes de programación suelen tener varios tipos de ciclos, como los ciclos for, while, do-while, entre otros.

### EJEMPLOS
___

- Ciclo "for":

`code`
```js
for (let i = 1; i <= 10; i++) {
    console.log(i);
}
```

>Este ciclo imprimirá los números del 1 al 10 en la consola. La inicialización de la variable "i" se realiza dentro de los paréntesis del ciclo "for", y se establece en 1. La condición en el ciclo "for" es "i <= 10", lo que significa que el ciclo continuará hasta que "i" sea mayor que 10. Finalmente, la expresión de incremento "i++" se ejecuta después de cada iteración del ciclo y aumenta el valor de "i" en 1.

- Ciclo "while" en JavaScript:


`code`
```js
let i = 1;

while (i <= 10) {
    console.log(i);
    i++;
}
```

>Este ciclo imprimirá los números del 1 al 10 en la consola. La variable "i" se inicializa en 1 antes del ciclo. La condición en el ciclo "while" es "i <= 10", lo que significa que el ciclo continuará hasta que "i" sea mayor que 10. La expresión de incremento "i++" se encuentra dentro del cuerpo del ciclo y se ejecuta después de cada iteración, aumentando el valor de "i" en 1. Una vez que "i" es 11, la condición se vuelve falsa y el ciclo termina.

Aquí hay un ejemplo de un ciclo "do-while" en JavaScript:

`code`
```js
let i = 1;

do {
    console.log(i);
    i++;
} while (i <= 10);
```

>Este ciclo imprimirá los números del 1 al 10 en la consola. La variable "i" se inicializa en 1 y se incrementa en cada iteración del ciclo. La condición en el ciclo "while" es "i <= 10", lo que significa que el ciclo continuará hasta que "i" sea mayor que 10. Una vez que "i" es 11, la condición se vuelve falsa y el ciclo termina.

___


- ¿Qué tipos de ciclos existen en JavaScript?

>Existen dos tipos de ciclos en JavaScript: los ciclos for y los ciclos while. 
>El ciclo for se utiliza para repetir un bloque de código un número determinado de veces, mientras que el ciclo while se utiliza para repetir un bloque de código mientras se cumpla una condición.
>
>También existe un tercer ciclo en javascript llamado for-in el cual se utiliza para iterar sobre las propiedades de un objeto.

ciclo "for-in" en JavaScript:

`code`
```js
const person = {
    name: "John",
    age: 30,
    city: "New York"
};

for (const key in person) {
    console.log(`${key}: ${person[key]}`);
}
```

>Este ciclo recorre las propiedades de un objeto "person". La palabra clave "in" se utiliza para iterar sobre las propiedades de un objeto. Cada iteración del ciclo asigna el nombre de la propiedad actual a la variable "key". Luego, se puede acceder al valor de la propiedad utilizando la notación de corchetes "person[key]".

El ciclo imprimirá en la consola:

`code`
```js
name: John
age: 30
city: New York
```

- ¿Qué es un ciclo infinito y por qué es un problema?

>Un ciclo infinito es un ciclo que no tiene una condición de finalización o que tiene una condición de finalización que nunca se cumple. Esto puede causar problemas en el código ya que el ciclo continuará ejecutándose indefinidamente y puede consumir recursos del sistema, causar bloqueos o colisiones en el código, y eventualmente causar un crash del programa. Es importante asegurarse de que todos los ciclos tengan una condición de finalización válida y sean utilizados de manera apropiada en el código.

Ejemplo ciclo infinito:

`code`
```js
while (true) {
    console.log("Este ciclo nunca termina");
}
```

>Este ciclo utiliza la condición constante true, lo que significa que siempre se evaluará como verdadera y, por lo tanto, el ciclo nunca terminará. Por lo general, se utiliza una condición de ciclo que eventualmente se vuelva falsa para evitar ciclos infinitos y asegurarse de que el programa termine de manera controlada. Sin embargo, en algunos casos, puede ser útil crear un ciclo infinito para ejecutar un proceso en segundo plano hasta que se detenga manualmente.


- ¿Puedo mezclar ciclos y condicionales?

>Sí, es posible mezclar ciclos y condicionales en JavaScript. Por ejemplo, se puede utilizar un ciclo para iterar sobre un conjunto de datos y dentro del ciclo, se pueden utilizar condicionales para tomar decisiones en base al valor actual de la iteración. También es posible utilizar un ciclo dentro de un condicional o un condicional dentro de un ciclo, dependiendo de la lógica que se quiera implementar en el código.

>ejemplo de cómo mezclar ciclos y condicionales en JavaScript:

`code`
```js
for (let i = 1; i <= 10; i++) {
    if (i % 2 === 0) {
        console.log(`${i} es un número par`);
    } else {
        console.log(`${i} es un número impar`);
    }
}
```

>Este código utiliza un ciclo "for" para iterar sobre los números del 1 al 10. Dentro del cuerpo del ciclo, se usa una estructura de control "if-else" para verificar si el número actual es par o impar. Si el número es par, se imprime un mensaje que indica que es un número par. De lo contrario, se imprime un mensaje que indica que es un número impar.
>
>El código imprimirá en la consola:

`code`
```js
1 es un número impar
2 es un número par
3 es un número impar
4 es un número par
5 es un número impar
6 es un número par
7 es un número impar
8 es un número par
9 es un número impar
10 es un número par
```

### 2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:


for (let i = 0; i < 5; i++) {
    console.log("El valor de i es: " + i);
}

`code`
```js
let i = 0;
while (i < 5) {
i++;
console.log("El valor de i es: " + i);
}
```

for (let i = 10; i >= 2; i--) {
    console.log("El valor de i es: " + i);
}

`code`
```js
let i = 10;
while (i >= 2) {
i--;
console.log("El valor de i es: " + i);
}
```

### 3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.
_💡 Pista: puedes usar la función prompt de JavaScript._

`code`
```js
let respuesta = parseInt(prompt("¿Cuánto es 2 + 2?"));
while (respuesta !== 4) {
alert("Incorrecto, vuelve a intentarlo.");
respuesta = parseInt(prompt("¿Cuánto es 2 + 2?"));
}
alert("¡Felicidades, la respuesta es correcta!");
```

>En este código, se utiliza el método "prompt" para pedir al usuario que ingrese un valor. Luego, se utiliza un ciclo while que se repite mientras la respuesta del usuario sea diferente a **4**, si la respuesta es correcta la condición del ciclo while no se cumple y el código continua y muestra un mensaje de felicitaciones.

## **Listas**

### 1️⃣ Responde las siguientes preguntas en la sección de comentarios:

- ¿Qué es un array?

>Un array es una estructura de datos que permite almacenar una colección de elementos, los cuales pueden ser de cualquier tipo de dato (numéricos, cadenas, objetos, etc.). Los elementos se acceden mediante un índice, el cual es un número que indica la posición del elemento en el array. En JavaScript, los arrays se crean utilizando la notación de corchetes []. 

`code`
```js
Ejemplo: var miArray = [1, 2, 3, 4, 5];
```

- ¿Qué es un objeto?

>Un objeto en JavaScript es una estructura de datos que permite almacenar valores y propiedades asociadas a una determinada clave. Los objetos son similares a los arrays, pero en lugar de almacenar valores en posiciones específicas, los almacenan en propiedades, que son pares clave-valor. 
>Los objetos se crean utilizando la notación {} y se pueden acceder a sus propiedades mediante la notación de punto (.) o la notación de corchetes ([]). Los objetos son muy versátiles y se utilizan en muchos aspectos de la programación en JavaScript, como en la manipulación de datos, la creación de objetos personalizados y la programación orientada a objetos.
>
>Un ejemplo de objeto podría ser:

`code`
```js
const persona = {
    nombre: "Juan",
    edad: 30,
    ciudad: "Bogotá",
    esEstudiante: false,
    intereses: ["leer", "viajar", "programar"]
};
```

>En este ejemplo, el objeto "persona" tiene 5 propiedades: "nombre", "edad", 
>"ciudad", "esEstudiante" y "intereses", cada una con un valor asociado.


- ¿Cuándo es mejor usar objetos o arrays?

>Depende del caso de uso específico. Los arrays son mejores para almacenar una secuencia ordenada de elementos, mientras que los objetos son mejores para almacenar elementos que tienen una clave única o propiedad. Si necesita acceder a un elemento mediante un índice numérico, un array es una buena opción. Si necesita acceder a un elemento mediante un nombre o una clave, un objeto es una buena opción.

- ¿Puedo mezclar arrays con objetos o incluso objetos con arrays?

>Sí, es posible mezclar arrays con objetos o incluso objetos con arrays en JavaScript. 
>Un ejemplo podría ser tener un array de objetos, donde cada objeto contiene información de una persona, como su nombre, edad y dirección. También es posible tener un objeto con una propiedad que sea un array, como un objeto "usuario" que tiene una propiedad "historial" que es un array de objetos "actividad". Esto dependerá del uso que le quieras dar a los datos y cómo los quieras almacenar y manejar.
>Los objetos pueden contener arrays como propiedades, y los arrays pueden contener objetos como elementos. Esto se conoce como estructuras de datos anidadas. Sin embargo, es importante considerar la legibilidad y el mantenimiento del código al utilizar estructuras de datos anidadas.
>
>Ejemplo:

`code`
```js
let persona = {
    nombre: "Juan",
    edad: 30,
    hobbies: ["leer", "correr", "viajar"]
}
```
>En este ejemplo, el objeto "persona" tiene tres propiedades: "nombre", "edad" y "hobbies". La propiedad "hobbies" es un array de strings.


### 2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.

 `code`
```js
function imprimirPrimerElemento(arr) {
console.log(arr[0]);
}
```
>En este código se define una función llamada "imprimirPrimerElemento" que recibe un parámetro llamado "arr". La función utiliza console.log para imprimir en pantalla el primer elemento del array, el cual se accede con la notación [0], ya que los índices en los arrays empiezan en 0. 
>Por ejemplo:

`code`
```js
const numbers = [1, 2, 3, 4, 5];
printFirstElement(numbers); // Imprimirá "1" en la consola.
```
>Imprimiría el primer elemento del array que es *1*.

```js
const names = ["John", "Jane", "Jim"];
printFirstElement(names); // Imprimirá "John" en la consola.
```
>Imprimiría el primer elemento del array que es *John*.


### 3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).

>Ejemplo 

`code`
```js
function imprimirElementos(arr) {
  for (let i = 0; i < arr.length; i++) {
    console.log(arr[i]);
  }
}

let miArray = [1, 2, 3, 4, 5];
imprimirElementos(miArray);
```

>En esta función se usa un bucle "for" para recorrer cada elemento del array y se usa el método "console.log()" para imprimir cada elemento uno por uno.
>
>En resumen, la función recibe un array como parámetro, luego recorre todo el array con un bucle for, y en cada iteración, imprime el elemento actual. El nombre del array es "arr" pero puedes usar cualquier nombre.



### 4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).

>Ejemplo 


`code`
```js
function imprimirElementos(obj) {
  for (let key in obj) {
    console.log(key + ": " + obj[key]);
  }
}

let miObjeto = { nombre: "Juan", edad: 30, ciudad: "Mexico" };
imprimirElementos(miObjeto);
```

>En esta función se usa un bucle "for in" para recorrer cada elemento del objeto y se usa el método "console.log()" para imprimir cada elemento uno por uno. en cada iteración se imprime la key y el valor asociado a ella.
>
>En resumen, la función recibe un objeto como parámetro, luego recorre todo el objeto con un bucle for in, y en cada iteración, imprime la key y el valor asociado. El nombre del objeto es "obj" pero puedes usar cualquier nombre.


`code`
```js
function printElemetforElementObject(obj) {
    const arr = Object.values(obj);
    for (let i = 0; i <arr.length; i++) {
        console.log(arr[i])
    }
}
```

___

¿Cómo te fue? 🏆

¡Felicidades por completar la prueba de JavaScript! Confío en que hayas completado cada paso y hayas pausado para repasar los temas de los ejercicios que se te complicaron.


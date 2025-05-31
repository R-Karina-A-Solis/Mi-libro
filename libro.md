<div align="center">
  <table width="100%">
    <tr>
      <td width="20%" align="left">
        <img src="imagen/UNAPLOGO.png" alt="Logo Izquierdo" width="200">
      </td>
      <td width="60%" align="center">
        <h1 style="color:#0077b6;">UNIVERSIDAD NACIONAL DEL ALTIPLANO</h1>
        <h3 style="color:#023e8a;">Facultad de Ingeniería Estadística e Informática</h3>
         <h3 style="color:#023e8a;">Códigos que estructuran</h3>
        <p>
      </td>
      <td width="20%" align="right">
        <img src="imagen/LOGOFAC.png" alt="Logo Derecho" width="200">
      </td>
    </tr>
  </table>
    <p><strong>Alumno:</strong> Ruth Karina Apaza Solis </p> 
    <strong>Curso:</strong> Estructura de Datos</p>
    <strong>Docente:</strong> Fred Torres Cruz</p>
</div>

# Índice

- [Índice](#índice)
- [Introducción](#introducción)
- [1. ¿Qué es programación?](#1-qué-es-programación)
  - [1.1 ¿Qué es un lenguaje de programación?](#11-qué-es-un-lenguaje-de-programación)
  - [1.2 ¿Qué es la estructura de datos?](#12-qué-es-la-estructura-de-datos)
  - [1.3 ¿Para qué sirven las estructuras de datos?](#13-para-qué-sirven-las-estructuras-de-datos)
- [2. Programación en c++](#2-programación-en-c)
  - [2.1 Mi primer programa](#21-mi-primer-programa)
- [3. Operadores](#3-operadores)
  - [3.1 ¿Para que sirven los operadores?](#31-para-que-sirven-los-operadores)
    - [3.2 Operadores aritméticos:](#32-operadores-aritméticos)
    - [3.3 Operadores de comparación o relacionales:](#33-operadores-de-comparación-o-relacionales)
- [4. Estructura de control](#4-estructura-de-control)
  - [4.1 ¿Que son las estructuras de control?](#41-que-son-las-estructuras-de-control)
    - [4.1.1 Estructuras Condicionales](#411-estructuras-condicionales)
    - [4.1.2 Estructuras Repetitivas (Bucles)](#412-estructuras-repetitivas-bucles)
- [5. Funciones](#5-funciones)
- [Arreglos](#arreglos)
- [6. Operadores `&` y `*`.](#6-operadores--y-)
- [7. Operador -\>](#7-operador--)
# Introducción

Este libro presenta una síntesis ordenada de los principales contenidos abordados durante el curso de programación en C++ y estructuras de datos. Su objetivo es consolidar los conocimientos adquiridos, facilitar su comprensión y servir como material de consulta para futuros estudios.

Se inicia con una introducción a la programación, el lenguaje C++ y los conceptos básicos sobre estructuras de datos. Luego, se desarrollan temas fundamentales como operadores, estructuras de control, funciones y arrays. Posteriormente, se abordan estructuras dinámicas como pilas, colas y listas enlazadas, así como el uso de punteros y operadores específicos del lenguaje. Finalmente, se incluye el concepto de recursión, una técnica clave en la resolución de problemas computacionales.

Cada capítulo combina teoría y ejemplos prácticos, orientando al lector hacia una comprensión integral y aplicada del lenguaje C++.

# 1. ¿Qué es programación?

La programación informática es el arte del proceso por el cual se limpia, codifica, traza y protege el código fuente de programas computacionales, en otras palabras, es indicarle a la computadora lo que tiene que hacer. 

<div style="float: right; margin: 0 0 10px 15px; width: 500px;">
  <img src="imagen/programacion.png" alt="Imagen de programación" style="width: 100%;">
</div>

La programación informática es una de las habilidades esenciales que aprendes cuando estudias informática.
 
Detrás de todos los programas informáticos que conocemos y usamos de manera cotidiana para facilitarnos diversas actividades de nuestro día con día, existe todo un proceso para poderlos crear. Este proceso es conocido como programación, conozcamos un poco más sobre lo que conlleva este proceso.

Por medio de la programación se establecen los pasos a seguir para la creación del código fuente de los diversos programas informáticos.

Este código le indicara al programa informático que tiene que hacer y como realizarlo.

La programación se guía por una serie de normas y un conjunto de órdenes, instrucciones y expresiones que tienden a ser semejantes a una lengua natural acotada. Por lo cual recibe el nombre de lenguaje de programación. Y así como en los idiomas también en la informática existen diversos lenguajes de programación.

Hablando de forma más técnica, la programación se realiza mediante el uso de algoritmos, que se podrían explicar cómo reglas o instrucciones que deben seguirse para resolver el problema y lograr el objetivo.

Algunas de ellas pueden agruparse y de ese modo recibir un nombre para tener la facilidad de ser invocadas con facilidad tantas veces como sea necesario.
> ### 💻 *“La programación es cómo haces que las computadoras resuelvan problemas.”*


## 1.1 ¿Qué es un lenguaje de programación?

Un **lenguaje de programación** es un conjunto de reglas y símbolos que permiten a los seres humanos escribir instrucciones que una computadora puede entender y ejecutar. Es el medio de comunicación entre el programador y la máquina.

<div style="float: right; margin: 0 0 10px 15px; width: 500px;">
  <img src="imagen/lenguaje.png" alt="Imagen de programación" style="width: 100%;">
</div>

Así como los humanos usamos distintos idiomas para comunicarnos, las computadoras también entienden distintos lenguajes. Cada lenguaje tiene su propia **sintaxis** (forma de escribir) y **semántica** (significado de las instrucciones).

Los lenguajes de programación se utilizan para:

- Crear aplicaciones y programas.
- Controlar el hardware de una computadora.
- Automatizar tareas repetitivas.
- Manipular datos y resolver problemas lógicos.

Algunos ejemplos comunes de lenguajes de programación son:

- **C** y **C++**
- **Python**
- **Java**
- **JavaScript**
- **Ruby**
- **Go**

## 1.2 ¿Qué es la estructura de datos?

Una estructura de datos es una forma organizada y eficiente de almacenar, gestionar y acceder a la información dentro de un programa. Su propósito principal es facilitar el procesamiento de grandes cantidades de datos, permitiendo realizar operaciones como inserción, eliminación, búsqueda y ordenamiento de manera óptima.

Las estructuras de datos pueden clasificarse en primitivas (como enteros, caracteres y booleanos) y no primitivas (como arrays, listas, pilas, colas, árboles y grafos). Cada una de ellas responde a diferentes necesidades y se selecciona en función del tipo de problema a resolver.

El estudio de las estructuras de datos es fundamental en la programación, ya que permite diseñar algoritmos más eficientes y comprender cómo se gestiona la memoria y el rendimiento en una aplicación.


## 1.3 ¿Para qué sirven las estructuras de datos?

Las estructuras de datos cumplen un rol esencial en el desarrollo de programas eficientes y funcionales. Su principal utilidad radica en la organización lógica y estructurada de la información, lo cual permite optimizar el uso de los recursos del sistema y mejorar el rendimiento de los algoritmos.

A través de las estructuras de datos, es posible realizar operaciones complejas como el almacenamiento dinámico, la gestión de grandes volúmenes de información, el acceso rápido a elementos específicos, así como la implementación de técnicas de búsqueda, ordenamiento y recorrido. Además, muchas soluciones informáticas dependen directamente de la correcta elección y manipulación de estas estructuras.
Ya sean las más utilizadas comúnmente -como las variables, arrays, conjuntos o clases- o las diseñadas para un propósito específico -árboles, grafos, tablas, etc.-, una estructura de datos nos permite trabajar en un algo nivel de abstracción almacenando información para luego acceder a ella, modificarla y manipularla.


Las estructuras de datos desempeñan un papel fundamental en el desarrollo de programas eficientes y funcionales. Su principal objetivo es organizar la información de manera lógica y estructurada, lo que permite optimizar el uso de los recursos del sistema, como la memoria y el tiempo de procesamiento, y mejorar significativamente el rendimiento de los algoritmos implementados.

Mediante el uso adecuado de estructuras de datos, es posible llevar a cabo operaciones complejas como el almacenamiento dinámico de información, la gestión y manipulación de grandes volúmenes de datos, el acceso rápido y directo a elementos específicos, así como la implementación de técnicas eficientes de búsqueda, ordenamiento y recorrido. La correcta selección y aplicación de estas estructuras es crucial para garantizar que las soluciones informáticas sean efectivas y escalables.

Las estructuras de datos pueden clasificarse en aquellas más comunes y generales, como las variables, arrays, conjuntos y clases, así como en aquellas diseñadas para necesidades específicas, tales como árboles, grafos, tablas hash, entre otras. Estas últimas permiten modelar relaciones y conexiones complejas entre datos, ampliando las capacidades del programa para resolver problemas avanzados.

En esencia, una estructura de datos proporciona un nivel de abstracción que facilita la organización, almacenamiento, acceso, modificación y manipulación de la información. Esta abstracción no solo simplifica el diseño de algoritmos, sino que también contribuye a mantener la claridad y modularidad del código, aspectos fundamentales en el desarrollo de software profesional.

# 2. Programación en c++
La programación en C++ es el proceso de escribir instrucciones utilizando el lenguaje de programación C++ para que una computadora realice tareas específicas. C++ es un lenguaje de propósito general, compilado y multiparadigma, lo que significa que permite programar de diferentes maneras, incluyendo programación estructurada, orientada a objetos y, en algunos casos, programación funcional.

Fue creado por Bjarne Stroustrup a principios de la década de 1980 como una extensión del lenguaje C, incorporando características adicionales como clases, objetos, herencia y manejo de excepciones.

## 2.1 Mi primer programa

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hola, mundo!" << endl;
    return 0;
}
```
**Explicación**
 
1. `#include <iostream>`

**¿Qué hace?**  
    Le dice al programa que use una **biblioteca llamada iostream**, que permite mostrar mensajes en la pantalla o recibir datos del teclado.

  ✅ **Ejemplo real**: es como decirle a tu programa: *“Usa las herramientas necesarias para poder imprimir mensajes.”*


2. `using namespace std;`

**¿Qué hace?**  
    Le indica al programa que puede usar funciones como `cout` sin tener que escribir `std::cout`.

  ✅ **Traducción fácil**: le dice a C++ que use un “espacio de nombres” donde están los comandos comunes.



3. `int main() {`

**¿Qué hace?**  
    Aquí empieza el programa.  
  **`main()`** es el punto de inicio: es donde el programa comienza a ejecutarse.

  ✅  **Piensa en esto como el corazón del programa**

4. `cout << "Hola, mundo!" << endl;`

**¿Qué hace?**  
    Imprime el mensaje `"Hola, mundo!"` en la pantalla.

    🧠 `cout`: Significa "console output" (salida por consola).  
    🧠 `<<`: Se usa para enviar texto a la consola.  
    🧠 `endl`: Hace un salto de línea, como presionar ENTER.

- ✅ **Lo que verás en pantalla**:

 
  ```
    Hola, mundo!
  ```


5. `return 0;`

**¿Qué hace?**  
    Le dice al sistema que el programa terminó **correctamente**.

    ✅ `0` significa “todo bien”.



6. `}`

  **¿Qué hace?**  
    Cierra la función `main`.  
    Es el final del programa.

# 3. Operadores

Los operadores son símbolos **(+, -, *, /, <, >, %, )** especiales que realizan operaciones sobre uno o más operandos. Los operandos pueden ser variables, valores o expresiones. Los operadores permiten realizar diversas operaciones, como aritméticas, lógicas, relacionales, de asignación, entre otras.

## 3.1 ¿Para que sirven los operadores?
Los operadores en programación sirven para realizar diversas operaciones sobre datos, variables o valores. Cada tipo de operador tiene una función específica y se utiliza en diferentes contextos para lograr ciertos resultados.

**Operadores más comunes:**

**Operadores Aritméticos:**
Permiten realizar operaciones matemáticas básicas, como suma, resta, multiplicación, división y módulo. Son esenciales para realizar cálculos numéricos en programas.
Operadores de Comparación o Relacionales:
Se utilizan para comparar valores y producir resultados booleanos (True o False). Son fundamentales para tomar decisiones en base a condiciones en un programa.
**Operadores Lógicos:**
Permiten combinar o invertir valores booleanos. Son útiles para evaluar expresiones lógicas y tomar decisiones basadas en múltiples condiciones.
Estos tres tipos de operadores son los más comunes. Aunque existen algunos más:
**Operadores de Asignación:**
Sirven para asignar valores a variables. También existen operadores de asignación combinados con operadores aritméticos, facilitando la actualización de variables en una única instrucción.
**Operadores de Pertenencia e Identidad:**
in se utiliza para verificar si un valor está presente en una secuencia (como una lista o cadena). is se utiliza para verificar si dos objetos son el mismo objeto en la memoria.

Estos operadores son fundamentales en la construcción de algoritmos y lógica de programación. Permiten a los desarrolladores realizar cálculos, comparaciones y manipulaciones de datos, lo que es esencial para la creación de programas que resuelven problemas específicos.

### 3.2 Operadores aritméticos:
Se utilizan para realizar operaciones matemáticas en programación.
`+` **(suma)**: Se utiliza para sumar dos valores.  
`-` **(resta)**: Se utiliza para restar el valor de la derecha del valor de la izquierda.  
`*` **(multiplicación)**: Se utiliza para multiplicar dos valores.  
`/` **(división)**: Se utiliza para dividir el valor de la izquierda por el valor de la derecha.  
`%` **(módulo)**: Devuelve el resto de la división del valor de la izquierda por el valor de la derecha.  
`//` **(división entera)**: Devuelve el cociente entero de la división del valor de la izquierda por el valor de la derecha.  


### 3.3 Operadores de comparación o relacionales:
Se utilizan para comparar dos valores y devolver un resultado booleano que indica la relación entre esos valores.

`==` **(igual a)**: Devuelve True si los dos valores son iguales; de lo contrario, devuelve False.  
`!=` **(diferente de)**: Devuelve True si los dos valores no son iguales; de lo contrario, devuelve False.  
`<` **(menor que)**: Devuelve True si el valor de la izquierda es menor que el valor de la derecha; de lo contrario, devuelve False.  
`>` **(mayor que)**: Devuelve True si el valor de la izquierda es mayor que el valor de la derecha; de lo contrario, devuelve False.  
`<=` **(menor o igual que)**: Devuelve True si el valor de la izquierda es menor o igual al valor de la derecha; de lo contrario, devuelve False.  
`>=` **(mayor o igual que)**: Devuelve True si el valor de la izquierda es mayor o igual al valor de la derecha; de lo contrario, devuelve False.  
`**` **(exponenciación)**: Se utiliza para elevar el valor de la izquierda a la potencia del valor de la derecha.

**Ejemplo**
```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b, c;
    cout << "Ingresa tres numeros: " << endl;
    cin >> a >> b >> c;

    double promedio = (a + b + c) / 3.0;

    cout << "El promedio es: " << promedio << endl;
    return 0;
}
```
**Explicación**

1. 
```cpp
int a, b, c;
```
**Declaración de tres variables enteras** que almacenarán los valores ingresados por el usuario.

2. 
```cpp
cout << "Ingresa tres numeros: ";
```
**Salida estándar.** Solicita al usuario ingresar los números.

3. 
```cpp
cin >> a >> b >> c;
```
**Entrada estándar.** Captura tres números consecutivos ingresados desde el teclado.

4. 
```cpp
double promedio = (a + b + c) / 3.0;
```
**Se realiza la suma** de las tres variables y se divide entre `3.0`.

- **Uso de `3.0` en vez de `3`**: fuerza una división de punto flotante para evitar truncamiento por división entera.
- El resultado se guarda en una variable de tipo `double` para manejar posibles decimales.

5. 
```cpp
cout << "El promedio es: " << promedio << endl;
```
**Imprime el resultado** del cálculo con una etiqueta descriptiva.  
`endl` agrega un salto de línea al final de la salida.

6.
```cpp
return 0;
```
**Indica que el programa finalizó correctamente.**  
Esto es una convención del sistema operativo para señalar que no hubo errores.

**Práctica 1: Calaculadora basica**
Escribe un programa que lea dos números enteros y muestre el resultado de sumarlos, restarlos, multiplicarlos y dividirlos.

```cpp
#include <iostream>
using namespace std;
int main() {
    int num1, num2;

    cout << "Ingrese el primer número: ";
    cin >> num1;

    cout << "Ingrese el segundo número: ";
    cin >> num2;

    cout << "\nResultados:\n";
    cout << "Suma: " << num1 + num2 << endl;
    cout << "Resta: " << num1 - num2 << endl;
    cout << "Multiplicación: " << num1 * num2 << endl;
    cout << "División (entera): " << num1 / num2 << endl;

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese el primer número: 10
Ingrese el segundo número: 2

Resultados:
Suma: 12
Resta: 8
Multiplicación: 20
División: 5

**Práctica 2: Par o impar**
Pide un número entero e indica si es par o impar.

 ```cpp
#include <iostream>
using namespace std;

int main() {
    int numero;

    cout << "Ingrese un número: ";
    cin >> numero;

    if (numero % 2 == 0) {
        cout << "El número es par." << endl;
    } else {
        cout << "El número es impar." << endl;
    }

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese un número: 8
El número es par.

**Práctica 3: Comparación de edades**
```cpp
#include <iostream>
using namespace std;

int main() {
    int edad1, edad2;

    cout << "Ingrese la primera edad: ";
    cin >> edad1;

    cout << "Ingrese la segunda edad: ";
    cin >> edad2;

    if (edad1 > edad2) {
        cout << "La primera edad es mayor que la segunda." << endl;
    } else if (edad1 < edad2) {
        cout << "La segunda edad es mayor que la primera." << endl;
    } else {
        cout << "Ambas edades son iguales." << endl;
    }

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese la primera edad: 19
Ingrese la segunda edad: 25
La segunda edad es mayor que la primera.

# 4. Estructura de control

En C++, existen seis estructuras de control fundamentales que permiten controlar el flujo de ejecución de un programa. Estas se dividen en **estructuras condicionales** y **estructuras repetitivas (bucles)**. Conocerlas es esencial para crear programas eficientes y dinámicos.

## 4.1 ¿Que son las estructuras de control?

Son herramientas que permiten decidir **qué instrucciones se ejecutan, cuándo y cómo**, basándose en condiciones. Se recomienda dominar el uso de operadores antes de estudiar este tema, ya que son fundamentales para establecer condiciones lógicas.

### 4.1.1 Estructuras Condicionales

Permiten ejecutar diferentes bloques de código dependiendo del cumplimiento de una condición lógica.

1. `if`

Es la estructura más básica. Evalúa una condición, y si se cumple, ejecuta el bloque correspondiente.

2. `if...else`

Agrega una alternativa para ejecutar un bloque diferente cuando la condición no se cumple.

3. `if...else if...else`

Permite evaluar múltiples condiciones de forma secuencial. Solo se ejecuta el primer bloque cuya condición sea verdadera.

4. `switch...case`

Evalúa una sola variable contra diferentes valores posibles. Es útil para manejar múltiples opciones y mejora la legibilidad del código al evitar repeticiones innecesarias.

### 4.1.2 Estructuras Repetitivas (Bucles)

Permiten ejecutar un bloque de código de manera repetitiva, ya sea mientras se cumpla una condición o durante un número determinado de veces.

1. `while`

Ejecuta un bloque de instrucciones mientras una condición sea verdadera. La condición se evalúa antes de cada iteración.

2. `do...while`

Ejecuta el bloque al menos una vez, ya que la condición se evalúa después de ejecutar el código. Ideal cuando se necesita que la acción ocurra una vez antes de verificar.

3. `for`

Es un bucle con tres componentes definidos: inicialización, condición y actualización. Es útil cuando se conoce de antemano cuántas veces debe repetirse un proceso.

**Ejemplo**
```cpp
#include <iostream>
using namespace std;

int main() {
    int nota;
    cout << "Ingresa la nota: ";
    cin >> nota;

    if (nota > 10) {
        cout << "Aprobado";
    } else {
        cout << "Desaprobado";
    }

    return 0;
}
```
**Explicación**

1. 
```cpp
#include <iostream>
```
Permite usar entrada y salida (cin, cout) en C++.

2. 
```cpp
using namespace std;
```
Evita tener que escribir std:: antes de cin y cout.
3. 
```cpp
int main()
```
Función principal donde empieza la ejecución del programa.
4. 
```cpp
int nota;
```
Se declara una variable entera para guardar la nota del estudiante.

5. **Entrada del usuario:**
```cpp
cout << "Ingresa la nota: ";
cin >> nota;
```
Muestra un mensaje y espera que el usuario escriba un número.

6. **Condición if-else:**
```cpp
if (nota > 10) {
    cout << "Aprobado";
} else {
    cout << "Desaprobado";
}
```
Si la nota es mayor que 10, el programa muestra "Aprobado".

Si la nota es 10 o menor, muestra "Desaprobado".

7. 
```cpp
return 0;
```
Termina el programa correctamente.

**Practica 1: Mayor de dos números**
Pide dos números al usuario y muestra cuál es mayor, o si ambos son iguales.
```cpp
#include <iostream>
using namespace std;

int main() {
    int num1, num2;

    cout << "Ingrese el primer número: ";
    cin >> num1;

    cout << "Ingrese el segundo número: ";
    cin >> num2;

    if (num1 > num2) {
        cout << "El primer número es mayor." << endl;
    } else if (num2 > num1) {
        cout << "El segundo número es mayor." << endl;
    } else {
        cout << "Ambos números son iguales." << endl;
    }

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese el primer número: 12
Ingrese el segundo número: 8
El primer número es mayor.

**Práctica 2: Calificación con mensaje**
Pide una nota (de 0 a 20) e imprime un mensaje según el siguiente criterio:

- 18 a 20: Excelente  
- 14 a 17: Bueno  
- 11 a 13: Regular  
- 0 a 10: Desaprobado
```cpp
#include <iostream>
using namespace std;

int main() {
    int nota;

    cout << "Ingrese la nota (0 a 20): ";
    cin >> nota;

    if (nota >= 18 && nota <= 20) {
        cout << "Excelente" << endl;
    } else if (nota >= 14 && nota <= 17) {
        cout << "Bueno" << endl;
    } else if (nota >= 11 && nota <= 13) {
        cout << "Regular" << endl;
    } else if (nota >= 0 && nota <= 10) {
        cout << "Desaprobado" << endl;
    } else {
        cout << "Nota fuera de rango." << endl;
    }

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese la nota (0 a 20): 15
Bueno

**Práctica 3: Contar hasta N**
Pide al usuario un número entero positivo `N` y muestra los números del 1 hasta `N`.
```cpp
#include <iostream>
using namespace std;

int main() {
    int N;
    int contador = 1;

    cout << "Ingrese un número entero positivo: ";
    cin >> N;

    while (contador <= N) {
        cout << contador << " ";
        contador++;
    }

    cout << endl;
    return 0;
}
```
**Ejemplo de ejecución**
Ingrese un número entero positivo: 5
1 2 3 4 5

# 5. Funciones
una función es un bloque de código independiente que realiza una tarea específica. Puedes pensar en una función como una “mini-máquina” dentro de tu programa: tú le das una entrada (si necesita), ella hace algo con esa entrada, y luego te da una salida (si aplica).
Las funciones se utilizan para organizar el código de manera más clara, estructurada y reutilizable. Son una parte fundamental de cualquier lenguaje de programación moderno, incluyendo C++, porque permiten dividir un problema complejo en partes más pequeñas y manejables.

**¿Para qué sirven las funciones?**
1. 🧹 Organizar el código
En lugar de escribir todo en una sola gran secuencia, puedes dividir tu programa en varias funciones que cada una haga una parte del trabajo. Esto hace que tu código sea más limpio, más legible y más ordenado.

2. 🔁 Evitar la repetición (reutilizar código)
Si necesitas hacer la misma operación varias veces (como sumar dos números o mostrar un saludo), puedes escribir una función una sola vez y llamarla todas las veces que la necesites. Así no repites código innecesario.

3. 🧩 Dividir problemas grandes
Cuando tienes un problema grande, como hacer una calculadora o un sistema de notas, lo mejor es dividir el problema en pasos pequeños. Cada uno de esos pasos se puede convertir en una función diferente.

Por ejemplo:

Una función que lea datos.

Otra que los procese.

Otra que muestre resultados.

Esto se llama "modularidad", y ayuda a trabajar paso a paso.

**Palabras reservadas**

| `return`      | Devuelve un valor desde la función al lugar donde fue llamada |
| `int`         | Indica que la función devuelve un número entero |
| `float`       | Indica que la función devuelve un número decimal |
| `double`      | Similar a `float`, pero con más precisión |
| `char`        | Indica que devuelve un carácter |
| `void`        | Indica que la función **no devuelve** ningún valor |
| `main()`      | Es la función **principal** de todo programa en C++ |

**Ejemplo**
```cpp
#include <iostream>
using namespace std;

float area(float pi, float radio) {
    return pi * radio * radio;
}

int main() {
    float pi = 3.14;
    float radio;
    float resultado;

    cout << "Ingrese el radio del circulo: ";
    cin >> radio;

    resultado = area(pi, radio);


    cout << "El area del circulo es: " << resultado << endl;

    return 0;
}
```
**Explicación**
Este programa en C++ permite calcular el **área de un círculo** usando una **función** que recibe el valor de `pi` y el `radio` como parámetros.

1. **Función area**
```cpp
float area(float pi, float radio) {
    return pi * radio * radio;
}
```
-Esta función se llama area.
-Recibe dos parámetros: el valor de pi y el radio del círculo.
-Devuelve un número decimal (tipo float).
-Usa la fórmula del área del círculo: \[A = \pi \cdot r^2\]
2. **Función principal main()**
```cpp
int main() {
    float pi = 3.14;
    float radio;
    float resultado;

    cout << "Ingrese el radio del circulo: ";
    cin >> radio;

    resultado = area(pi, radio);

    cout << "El area del circulo es: " << resultado << endl;

    return 0;
}
```
Se declara pi con valor 3.14.

Se pide al usuario el radio del círculo.

Se llama a la función area() pasando pi y radio.

Se muestra el resultado con cout.

**Ejemplo de ejecución**
Ingrese el radio del circulo: 5
El area del circulo es: 78.5

**Práctica 1: Calcular la potencia de un número (sin usar pow)**
```cpp
#include <iostream>
using namespace std;

int potencia(int base, int exponente) {
    int resultado = 1;
    for (int i = 0; i < exponente; i++) {
        resultado *= base;
    }
    return resultado;
}

int main() {
    int base, exponente;

    cout << "Ingrese la base: ";
    cin >> base;

    cout << "Ingrese el exponente: ";
    cin >> exponente;

    int resultado = potencia(base, exponente);

    cout << "El resultado de " << base << "^" << exponente << " es: " << resultado << endl;

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese la base: 2
Ingrese el exponente: 3
El resultado de 2^3 es: 8

**Práctica 2: Sumar los dígitos de un número**
```cpp
#include <iostream>
using namespace std;

// Función que suma los dígitos de un número
int sumaDigitos(int numero) {
    int suma = 0;
    while (numero != 0) {
        suma += numero % 10;   // Extrae el último dígito
        numero /= 10;          // Elimina el último dígito
    }
    return suma;
}

int main() {
    int numero;

    cout << "Ingrese un número: ";
    cin >> numero;

    int resultado = sumaDigitos(numero);

    cout << "La suma de los dígitos es: " << resultado << endl;

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese un número: 1234
La suma de los dígitos es: 10

# Arreglos

**¿Qué es un arreglo?**
Un arreglo (también llamado vector o array) es una estructura de datos fundamental en programación que permite almacenar y organizar un conjunto de valores del mismo tipo bajo un solo nombre. Estos valores están organizados en una secuencia lineal, y cada valor puede ser accedido mediante un índice o posición numérica.

**Características principales de los arreglos:**
**Homogeneidad**: Todos los elementos del arreglo deben ser del mismo tipo (por ejemplo, todos enteros, todos caracteres, todos flotantes, etc.).

**Acceso por índice:** Cada elemento dentro del arreglo está numerado consecutivamente, comenzando en la posición 0, lo que permite acceder directamente a cualquier valor usando su índice.

**Tamaño fijo:** En lenguajes como C++ y C, el tamaño del arreglo debe definirse al declararlo y no puede cambiar durante la ejecución del programa.

**Conceptos claves**

| Concepto         | Ejemplo            | Explicación                 |
|------------------|--------------------|-----------------------------|
| Declarar arreglo | `int a[10];`       | Arreglo de 10 enteros       |
| Inicializar arreglo | `int b[3] = {5,10,15};` | Arreglo con valores iniciales |
| Asignar valor    | `a[0] = 7;`        | Asigna 7 al primer elemento |
| Acceder a valor  | `int x = b[2];`    | Guarda 15 (tercer elemento) en x |
| Índices válidos  | 0 a tamaño-1       | Ejemplo: para `a[10]`, índices 0-9 |

**Ejemplo**
```cpp
#include <iostream>
using namespace std;

int main() {
    // Declaración de un arreglo de 5 enteros
    int numeros[5];

    // Asignación de valores a cada posición
    numeros[0] = 10;
    numeros[1] = 20;
    numeros[2] = 30;
    numeros[3] = 40;
    numeros[4] = 50;

    // Acceso y muestra de los valores del arreglo
    for(int i = 0; i < 5; i++) {
        cout << "Elemento en posicion " << i << ": " << numeros[i] << endl;
    }

    return 0;
}
```
**Explicación**

1. `int numeros[5];`
   Aquí se declara un arreglo de tipo entero  `(int) ` llamado numeros, con espacio para 5 elementos.
Es importante recordar que en C++, los arreglos comienzan desde el índice  0. Por lo tanto,  `numeros[0] ` es el primer elemento y  `numeros[4]` el último.
2. **Asignación de valores**
```cpp
numeros[0] = 10;
numeros[1] = 20;
numeros[2] = 30;
numeros[3] = 40;
numeros[4] = 50;
```
En estas líneas, se asigna manualmente un valor a cada una de las posiciones del arreglo. Cada línea toma una posición específica e introduce un número.
3. **Recorrido con un bucle for** 
```cpp
for(int i = 0; i < 5; i++) {
    cout << "Elemento en posicion " << i << ": " << numeros[i] << endl;
}
```
Se utiliza un bucle `for` para recorrer todas las posiciones del arreglo, desde `i = 0` hasta `i = 4`. En cada iteración, se imprime el índice actual (`i`) y el valor almacenado en `numeros[i]`.

**Ejecución**
numeros[0] = 10;
numeros[1] = 20;
numeros[2] = 30;
numeros[3] = 40;
numeros[4] = 50;

**Práctica 1: Invertir los elementos**
Crear un programa que lea 8 números enteros en un arreglo y luego los muestre en orden inverso (del último al primero).
```cpp
#include <iostream>
using namespace std;

int main() {
    int numeros[8];

    // Lectura de datos
    cout << "Ingrese 8 numeros enteros:" << endl;
    for (int i = 0; i < 8; i++) {
        cin >> numeros[i];
    }

    // Mostrar en orden inverso
    cout << "Los numeros en orden inverso son:" << endl;
    for (int i = 7; i >= 0; i--) {
        cout << numeros[i] << " ";
    }

    cout << endl;
    return 0;
}
```
**Ejemplo de ejecución**
Ingrese 8 numeros enteros:
10 20 30 40 50 60 70 80
Los numeros en orden inverso son: 
80 70 60 50 40 30 20 10 

**Practica 2: Suma y producto escalar de dos arreglos**
Escribe un programa que lea dos arreglos de 5 enteros, calcule un tercer arreglo con la suma elemento a elemento y muestre el producto escalar de ambos arreglos.
```cpp
#include <iostream>
using namespace std;

int main() {
    const int n = 5; 
    int a[n], b[n];  
    int suma[n];    

    cout << "Ingrese los elementos del vector A y B:\n";
    for (int i = 0; i < n; i++) {
        cout << "a[" << i << "]: ";
        cin >> a[i];
        cout << "b[" << i << "]: ";
        cin >> b[i];
    }

    int productoEscalar = 0;

    cout << "\nSuma de elementos (a[i] + b[i]):\n";
    for (int i = 0; i < n; i++) {
        suma[i] = a[i] + b[i];
        productoEscalar += a[i] * b[i];
        cout << "suma[" << i << "] = " << suma[i] << endl;
    }

    cout << "\nProducto escalar: " << productoEscalar << endl;

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese los elementos del vector A y B:
a[0]: 1
b[0]: 2
a[1]: 3
b[1]: 4
a[2]: 5
b[2]: 6
a[3]: 7
b[3]: 8
a[4]: 9
b[4]: 10

Suma de elementos (a[i] + b[i]):
suma[0] = 3
suma[1] = 7
suma[2] = 11
suma[3] = 15
suma[4] = 19

Producto escalar: 130

# 6. Operadores `&` y `*`.

En el lenguaje de programación C++, los operadores `&` y `*` son fundamentales para trabajar con **direcciones de memoria** y **punteros**, herramientas clave para el control preciso de los datos y su almacenamiento en la memoria del computador.

**6.1. Operador `&` – Dirección de memoria**

El operador `&` se conoce como **operador de dirección**. Su función principal es obtener la **dirección de memoria** de una variable.

Cada vez que se declara una variable, el sistema operativo le asigna una ubicación específica en la memoria. El operador `&` permite acceder a esa ubicación.

**Puntos clave:**

- Permite trabajar con la posición física donde está almacenada la variable.
- Es utilizado para asignar direcciones a punteros.
- Es el primer paso para manipular datos de forma indirecta mediante punteros.
- Se aplica solamente a **variables**, no a literales o expresiones directas.

**6.2. Operador `*` – Puntero y desreferenciación**

El operador `*` tiene dos usos principales y muy distintos en C++, dependiendo del contexto:

1. **Declaración de punteros**

Cuando se usa en una declaración de variable, el `*` indica que esa variable es un **puntero**, es decir, una variable que almacena una **dirección de memoria** en lugar de un valor directo.

2. **Desreferenciación**

Cuando se usa sobre un puntero ya declarado, el operador `*` permite **acceder al valor almacenado** en la dirección de memoria que contiene el puntero.  
Este proceso se llama **desreferenciación**.

**Puntos clave:**

Permite leer o modificar datos que están almacenados en otra ubicación de memoria.
Es indispensable para la manipulación dinámica de datos y estructuras como arreglos, cadenas y memoria dinámica (`new`/`delete`).
El mal uso del operador `*` puede causar errores graves como **acceder a zonas de memoria no válidas** (errores de segmentación o *segmentation faults*).

> ✅ Comprender estos operadores es esencial para dominar el manejo de punteros, una de las características más poderosas y delicadas de C++.

**Ejemplo**
```cpp
#include <iostream>
int main() {
    int var = 10;
    int* ptr = &var;
    
    std::cout << "El valor de var: " << var << std::endl;
    std::cout << "La dirección de memoria de var: " << &var << std::endl;
    std::cout << "El valor de ptr: " << ptr << std::endl;
    std::cout << "El valor apuntado por ptr: " << *ptr << std::endl;

    return 0;
}
```
**🔍 Explicación**

1. `int var = 10;`

Se declara una variable entera llamada `var` y se le asigna el valor `10`.  
El sistema operativo reserva una posición de memoria para almacenarla.

2. `int* ptr = &var;`

Se declara un puntero llamado `ptr`, que es de tipo `int*` (puntero a entero).  
Este puntero almacena la **dirección de memoria** donde se encuentra `var`.  
El operador `&var` obtiene esa dirección.

3. `std::cout << "El valor de var: " << var << std::endl;`

Se imprime el valor almacenado en `var`, que es `10`.

4. `std::cout << "La dirección de memoria de var: " << &var << std::endl;`

Se muestra la **dirección de memoria** en la que está almacenada la variable `var`.  
El operador `&` permite acceder a esa dirección física.

5. `std::cout << "El valor de ptr: " << ptr << std::endl;`

Se imprime el contenido del puntero `ptr`.  
Como `ptr` almacena la dirección de `var`, este valor coincidirá con `&var`.

6. `std::cout << "El valor apuntado por ptr: " << *ptr << std::endl;`

Aquí se utiliza el operador `*` para **desreferenciar** el puntero `ptr`.  
Esto significa que accedemos al **valor almacenado** en la dirección que contiene `ptr`, es decir, el valor de `var`.

**Ejemplo de ejecución**

El valor de var: 10
La dirección de memoria de var: 0x61ff08
El valor de ptr: 0x61ff08
El valor apuntado por ptr: 10

**Práctica 1: Usar un puntero para acceder al valor de una variable**
```cpp
#include <iostream>
using namespace std;

int main() {
    int edad = 25;
    int* ptr = &edad; // ptr almacena la dirección de edad

    cout << "Direccion guardada en el puntero: " << ptr << endl;
    cout << "Valor al que apunta el puntero: " << *ptr << endl;

    return 0;
}
``` 
**Ejemplo de ejecución**
Direccion guardada en el puntero: 0x61fef8
Valor al que apunta el puntero: 25

**Práctica 2: Arreglo y puntero básico**
```cpp
#include <iostream>
using namespace std;

int main() {
    int numeros[3] = {5, 10, 15};
    int* ptr = numeros; // ptr apunta al primer elemento del arreglo

    for (int i = 0; i < 3; i++) {
        cout << "Elemento " << i << ": " << *(ptr + i) << endl;
    }

    return 0;
}
```
**Ejemplo de ejecución**
Elemento 0: 5
Elemento 1: 10
Elemento 2: 15

**Práctica 3: Intercambio de valores y uso de punteros para modificar variables**

Escribe un programa que reciba dos números enteros, intercambie sus valores usando punteros, y luego muestre los valores intercambiados.

```cpp
#include <iostream>
using namespace std;

void intercambiar(int* a, int* b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

int main() {
    int x, y;

    cout << "Ingrese el primer numero: ";
    cin >> x;
    cout << "Ingrese el segundo numero: ";
    cin >> y;

    intercambiar(&x, &y);

    cout << "Despues del intercambio:\n";
    cout << "Primer numero: " << x << endl;
    cout << "Segundo numero: " << y << endl;

    return 0;
}
```
**Ejemplo de ejecución**
Ingrese el primer numero: 15
Ingrese el segundo numero: 30
Despues del intercambio:
Primer numero: 30
Segundo numero: 15

# 7. Operador ->













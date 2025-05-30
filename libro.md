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

1. [Introducción](#introducción)
2. [Qué es programación](#que-es-programación)
    2.1. [Qué es un lenguaje de programación](#qué-es-un-lenguaje-de-programación)
3. [Programación en c++](programación-en-c++)
   3.1 [Mi primer programa](mi-primer-programa)
4. [Operadores](#operadores)
5. [Estructuras de Control](#estructuras-de-control)
6. [Funciones](#funciones)
7. [Arrays](#arrays)
8. [Arreglos](#arreglos)
9.  [Pilas](#pilas)
10. [Colas](#colas)
11. [Operadores `&` y `*`](#operadores--y-)
12. [Operador `->`](#operador-)
13. [Listas Enlazadas](#listas-enlazadas)
14. [Listas Doblemente Enlazadas](#listas-doblemente-enlazadas)
15. [Colas (Revisitado)](#colas-revisitado)
16. [Pilas (Revisitado)](#pilas-revisitado)
17. [Recursión](#recursión)
18. [Conclusión](#conclusión)

# Introducción
** Este libro trata...

# Qué es programación

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


### Qué es un lenguaje de programación

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

Los lenguajes pueden clasificarse en:

- **Lenguajes de bajo nivel**: Más cercanos al lenguaje máquina, como el lenguaje ensamblador.
- **Lenguajes de alto nivel**: Más cercanos al lenguaje humano, más fáciles de escribir y entender, como Python o Java.

# Programación en c++
La programación en C++ es el proceso de escribir instrucciones utilizando el lenguaje de programación C++ para que una computadora realice tareas específicas. C++ es un lenguaje de propósito general, compilado y multiparadigma, lo que significa que permite programar de diferentes maneras, incluyendo programación estructurada, orientada a objetos y, en algunos casos, programación funcional.

Fue creado por Bjarne Stroustrup a principios de la década de 1980 como una extensión del lenguaje C, incorporando características adicionales como clases, objetos, herencia y manejo de excepciones.

### Mi primer programa
```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hola, mundo!" << endl;
    return 0;
}
```
# Explicación 
### 1️⃣ `#include <iostream>`

- **¿Qué hace?**  
  Le dice al programa que use una **biblioteca llamada iostream**, que permite mostrar mensajes en la pantalla o recibir datos del teclado.

- ✅ **Ejemplo real**: es como decirle a tu programa: *“Usa las herramientas necesarias para poder imprimir mensajes.”*

---

### 2️⃣ `using namespace std;`

- **¿Qué hace?**  
  Le indica al programa que puede usar funciones como `cout` sin tener que escribir `std::cout`.

- ✅ **Traducción fácil**: le dice a C++ que use un “espacio de nombres” donde están los comandos comunes.

---

### 3️⃣ `int main() {`

- **¿Qué hace?**  
  Aquí empieza el programa.  
  **`main()`** es el punto de inicio: es donde el programa comienza a ejecutarse.

- ✅ **Piensa en esto como el corazón del programa.**

---

### 4️⃣ `cout << "Hola, mundo!" << endl;`

- **¿Qué hace?**  
  Imprime el mensaje `"Hola, mundo!"` en la pantalla.

- 🧠 `cout`: Significa "console output" (salida por consola).  
- 🧠 `<<`: Se usa para enviar texto a la consola.  
- 🧠 `endl`: Hace un salto de línea, como presionar ENTER.

- ✅ **Lo que verás en pantalla**:

  ```
  Hola, mundo!
  ```

---

### 5️⃣ `return 0;`

- **¿Qué hace?**  
  Le dice al sistema que el programa terminó **correctamente**.

- ✅ `0` significa “todo bien”.

---

### 6️⃣ `}`

- **¿Qué hace?**  
  Cierra la función `main`.  
  Es el final del programa.

---



# Propuesta de ejercicio de autoestudio

** Inspecciona Internet en busca de scripts en distintos lenguajes de programación de alto nivel:

- c++
- Java
- Python
- Javascript

** Cuando los tengas detectados, localiza los elementos que hemos visto en el temario:

- variables
- operadores
- condicionales
- bucles
- POO

1. Debería apreciar que, aunque cambia la sintaxis, los elementos que hemos estudiado son comunes a todos ellos y conforman la base de prácticamente todos los lenguajes de programación que se usan hoy en día.

2. Una forma fácil y práctica de hacerlo es investigando en github los diferentes códigos que los usuarios suben. Si buscamos por nombre de lenguaje de programación nos saldrán miles de scripts escritos en dicho lenguaje.

## Para realizar la tarea no pretendemos que analices y entiendas los scripts, simplemente localiza los elementos descritos anteriormente y comprueba que son de uso común en diferentes lenguajes.

Examina cada script para localizar los siguientes elementos:
- Variables: Identifica cómo se definen y utilizan variables en cada lenguaje.
- Operadores: Observa los operadores aritméticos, lógicos y de comparación utilizados en los scripts.
- Condicionales: Busca estructuras condicionales como if, else if y else, y cómo se aplican en cada lenguaje.
- Bucles: Encuentra ejemplos de bucles como for, while o do-while, y observa cómo se implementan.
- Programación Orientada a Objetos (POO): Si es posible, busca ejemplos de clases, objetos, métodos y herencia en los scripts.


| C++                            | Java                          | Python                       | JavaScript                   |
|--------------------------------|-------------------------------|------------------------------|------------------------------|
| ```c++                         | ```java                       | ```python                    | ```javascript                |
| #include <iostream>            | public class Main {           | # Variables                  | // Variables                 |
| using namespace std;           |     public static void main(String[] args) { | a = 5                        | let a = 5;                   |
|                                |       // Variables           | b = 3                        | let b = 3;                   |
| int main() {                   |         int a = 5;           |                              |                              |
|     int a = 5;                 |         int b = 3;           | # Operadores                 | // Operadores                |
|     int b = 3;                 |         int result;          | result = a + b               | let result = a + b;          |
|     int result;                |                               |                              |                              |
|                                |         // Operadores       | # Condicionales              | // Condicionales             |
|     result = a + b;            |         result = a + b;      | if result > 5:               | if (result > 5) {            |
|                                |                               |     print("El resultado es mayor que 5") |   console.log("El resultado es mayor que 5"); |
|                                |                               | else:                        | } else {                     |
|                                |                               |     print("El resultado es menor o igual que 5") |   console.log("El resultado es menor o igual que 5"); |
|                                |                               |                              |                              |
|                                |                               | # Bucles                     | # Bucles                    |
|                                |                               | for i in range(5):           | for (let i = 0; i < 5; i++) { |
|                                |                               |     print("Iteración", i)   |     console.log("Iteración", i); |
|                                |                               |                              | }                            |
|                                |                               |                              |                              |
|     return 0;                  |     }                         |                              |                              |
| }                              | }                             |                              | ```                          |
| ```                            | ```                           | ```                          | ```                          |



## Otra forma de presentar los scripts

### Ejemplo en C++:
```c++
#include <iostream>
using namespace std;

int main() {
    // Variables
    int a = 5;
    int b = 3;
    int result;

    // Operadores
    result = a + b;

    // Condicionales
    if (result > 5) {
        cout << "El resultado es mayor que 5" << endl;
    } else {
        cout << "El resultado es menor o igual que 5" << endl;
    }

    // Bucles
    for (int i = 0; i < 5; i++) {
        cout << "Iteración " << i << endl;
    }

    return 0;
}
```

### Ejemplo en Java:
```java
public class Main {
    public static void main(String[] args) {
        // Variables
        int a = 5;
        int b = 3;
        int result;

        // Operadores
        result = a + b;

        // Condicionales
        if (result > 5) {
            System.out.println("El resultado es mayor que 5");
        } else {
            System.out.println("El resultado es menor o igual que 5");
        }

        // Bucles
        for (int i = 0; i < 5; i++) {
            System.out.println("Iteración " + i);
        }
    }
}
```

### Ejemplo en Python:
```python
# Variables
a = 5
b = 3

# Operadores
result = a + b

# Condicionales
if result > 5:
    print("El resultado es mayor que 5")
else:
    print("El resultado es menor o igual que 5")

# Bucles
for i in range(5):
    print("Iteración", i)
```

### Ejemplo en JavaScript:
```javascript
// Variables
let a = 5;
let b = 3;

// Operadores
let result = a + b;

// Condicionales
if (result > 5) {
    console.log("El resultado es mayor que 5");
} else {
    console.log("El resultado es menor o igual que 5");
}

// Bucles
for (let i = 0; i < 5; i++) {
    console.log("Iteración", i);
}
```

Estos ejemplos muestran cómo se implementan elementos básicos de programación en cada uno de los lenguajes mencionados, permitiendo comparar y contrastar la sintaxis y la estructura en cada caso.


<p align="center">
<img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/46fa5800-6fee-43d4-937e-8af2438956ad" /></p></div>

# Funciones de primera clase: pasar y devolver funciones como cualquier dato.
--- 
### Autor: Gomez Cuevas Carlos.
### Grupo: 4:00 p.m.
### Materia: Programacion Logica y Funcional.
### Profesor: Rene Solis Reyes.
---
## Introduccion.
Se dice que un lenguaje de programación tiene funciones de primera clase si trata las funciones como ciudadanos de primera clase. Esto significa que admite:
* Poder pasar funciones como argumentos a otras funciones.
* Que el valor de retorno de una función sea otra función.
* Asignar funciones a variables o almacenarlas en estructuras de datos.

---

## Concepto.
Una función de primera clase es una función que se trata como una "cosa en sí misma", capaz de mantenerse sola y de ser tratada independientemente.
Otra forma de describir las funciones de primera clase es la de funciones como datos. Es decir, una función de primera clase puede ser asignada a una variable como cualquier otro dato. El término fue acuñado por Christopher Strachey en el contexto de "funciones como ciudadanos de primera clase" a mediados de los años 60.

---
## Propiedades.
Para que una función cumpla con esta definicion, debe permitir que una funcion pueda:
* Asignarse a una variable o constante: Guardar una función en una variable como si fuera un dato cualquiera.
* Pasarse como argumento a otra función: Enviar una función para que otra la ejecute (la base de los callbacks).
* Retornarse desde otra función: Crear fábricas de funciones o closures (clausuras).
* Almacenarse en estructuras de datos: Guardar funciones dentro de arreglos, listas, diccionarios u objetos.

## Diferencias ante las funciones de orden superior.
| Característica | Funciones de primera clase | Funciones de orden superior |
| :--- | :--- | :--- |
| **Definición** | Funciones que pueden tratarse como cualquier otro valor (asignadas a variables, pasadas como argumentos, devueltas por otras funciones). | Funciones que toman otras funciones como argumentos o devuelven funciones. |
| **Función como valor** | Sí, las funciones son ciudadanos de primera clase (pueden ser asignadas, aprobadas o devueltas). | Sí, las funciones pueden ser transmitidas o devueltas por otras funciones. |
| **Pasando funciones como argumentos** | Las funciones pueden pasarse como argumentos a otras funciones. | Una función de orden superior requiere específicamente funciones como argumentos. |
| **Funciones de regreso** | Las funciones pueden devolver otras funciones, pero esto por sí solo no las convierte en orden superior. | Las funciones de orden superior deben devolver otra función. |
| **Caso de uso** | Cualquier función que pueda tratarse como un objeto de primera clase, incluyendo asignación y paso a otras funciones. | Se usa cuando quieres pasar comportamiento como argumento o devolver comportamiento (como callbacks, gestores de eventos, etc.). |

## Referencias
* https://codigoencasa.com/programacion-funcional/
* https://en.wikipedia.org/wiki/First-class_function
* https://www.geeksforgeeks.org/javascript/difference-between-first-class-and-higher-order-functions-in-javascript/

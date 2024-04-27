# Estructuras-de-control
## Ejercicio 1 
Crea un programa que lea un número entero del usuario y lo clasifique como positivo, negativo o cero.
```mermaid
    flowchart TD
A[Ingresar número] ---> B{¿numero > 0?}
    B --->|Si| C[El número es positivo]
    B --->|No| D{¿numero === 0?}
    D ---> |Si| E[El número es cero]
    D ---> |No| F[El número es negativo]
    C ---> G[FIN]
    E ---> G[FIN]
    F ---> G[FIN]

```
## Ejercicio 2
Crea un programa que lea un número entero del usuario y muestre un mensaje indicando si es par o impar.


```mermaid
    flowchart TD
A[Ingresar número] ---> B{¿numero != 0?}
B --->|NO| C[El numero es 0]
B --->|SI| D{¿numero % 2 === 0?}
D --->|SI| E[El número es par]
D --->|NO| F[El número es impar]
F --->G[FIN]
E --->G[FIN]
C --->G[FIN]
```

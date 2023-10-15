# Apuntes Extras de Gambas

**1.1 Comentarios en Gambas:** 
Los comentarios son lineas de codigo que no se ejecutan, pero que sirven para documentar el codigo y hacerlo mas legible. En Gambas existen dos tipos de comentarios:
- **FIXME:** Son comentarios que hacemos cuando tenemos algo por arreglar en el codigo.

- **TODO:** Son comentarios que hacemos cuando tenemos algo por hacer en el codigo.

- **NOTE:** Son comentarios que hacemos para explicar algo en el codigo.


**1.2:** En las variables se tienen que cumplir ciertas condiciones para que podamos trabajar de manera ordenada y correcta:

**Evitar:**

- No usar nombres de variables repetidas
- No declarar dos veces la misma variable
- No usar espacios y caracteres especiales en el nombre de la variable
- No usar palabras reservadas del lenguaje como nombre de variable


**Recomendaciones:**
- Usar **camelcase** para nombrar variables
- Usar nombres de variables que sean descriptivos
- Usar nombres cortes para las variables


**1.3 Jerarquia de operaciones:** 
En aritmetica existe un orden para las operaciones matematicas basicas, tambien en javascript se respeta ese orden. El orden es el siguiente:

1. Parentesis
2. Exponentes
3. Multiplicacion y Division
4. Suma y Resta


## Conceptos

> **Camelcase:** El nombre se debe de escribir sin espacios y la primera letra de cada palabra debe de ir en mayuscula, excepto la primera palabra. Ejemplo: nombreUsuario.

> **Operadores Logicos:** Son aquellos en los que podemos evaluar una o mas condiciones que nosotros especifiquemos y revisar si se cumplen o no. Un recurso que nos puede a ayudar muchisimo son las tablas de la verdad 

> **Tablas de la Verdad:** Son tablas que nos ayudan a saber el resultado de una operacion logica, en ellas se muestran todas las posibles combinaciones de valores que pueden tomar las variables que se estan evaluando.

**AND:** Operador logico que se utiliza para determinar si dos condiciones se cumplen al mismo tiempo. Su tabla de la verdad es el siguiente:

| A     | B     | A AND B |
|-------|-------|---------|
| true  | true  | true    |
| true  | false | false   |
| false | true  | false   |
| false | false | false   |

**OR:** Operador logico que se utiliza para determinar si al menos una de las condiciones se cumple. Su tabla de la verdad es el siguiente:

| A     | B     | A OR B |
|-------|-------|--------|
| true  | true  | true   |
| true  | false | true   |
| false | true  | true   |
| false | false | false  |

**NOT:** Operador logico que se utiliza para cambiar el valor de la condicion a su opuesto. Su tabla de la verdad es el siguiente:

| A     | NOT A |
|-------|-------|
| true  | false |
| false | true  |

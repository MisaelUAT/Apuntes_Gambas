# Introduccion a Gambas3

Gambas es un lenguaje de programacion parecido a visual basic pero con la diferencia de que es mas moderno y esta basado en el lenguaje de programacion C. Algunas ventajas que nos ofrece este hermoso lenguaje son: 

- Es multiplataforma
- Es de codigo abierto
- Es facil de aprender
- Sintaxis Sencilla

> En esta guia nos enfocaremos en la sintaxis del mismo mas no vamos a ver como instalarlo en cada sistema operativo.

## Variables
Son contenedores en donde se pueden almacenar temporalmente datos para ser usados en el programa. En gambas las variables se declaran de la siguiente manera:

```vb
'Declaracion de Variables'
Dim nombre As String = "Juan"
```
> Estructura de una variable: **Dim + Nombre de la variable + As + Tipo de dato = Valor del dato**

Existen muchas situaciones en donde podemos usar variables, recuerda que estas pueden almacenar distintos tipos de datos ya sean numericos, cadenas de texto, booleanos, etc. Por ejemplo las podemos usar:

* Almacenar el nombre de una persona
* Almacenar la edad de una persona
* Almacenar la fecha de cumpleaños
* Almacenar el valor de una condicion

**Asi se veria en codigo todas estas situaciones:**
    
![Variables](/img/variables.png)

> Tranquilo si no sabes que es lo que andas viendo, veremos cada variable a detalle.

## String
Las variables de tipo string son las que almacenan cadenas de texto, estas se declaran de la siguiente manera:

```vb
'Declaracion de Variables'
Dim name As String= "Pedro"
```
**Un ejemplo del codigo:**

![String](/img/Variables1.png)

> Recuerda que despues de la palabra clave **_As_** se debe de especificar que va a ser de tipo String.

## Integer
Las variables de tipo integer son las que almacenan numeros enteros, estas se declaran de la siguiente manera:

```vb
'Declaracion de una variable Integer'
Dim numero As Integer= 200;
```

**Un ejemplo del codigo:**

![Integer](/img/variables3.png)


## Date
Las variables de tipo date son las que almacenan fechas, estas se declaran de la siguiente manera:

```vb
'Declaracion de una variable Date'
Dim fecha_hoy As Date= Date(2004,09,30)
```
**Un ejemplo del codigo:**

![Date](/img/Variables2.png)

> Recuerda siempre poner la palabra clave **_Date_** antes de la fecha que quieras almacenar.

## Booleano
Las variables de tipo booleano son las que almacenan valores de verdadero o falso, estas se declaran de la siguiente manera:

```vb
Dim soy_feliz As Boolean = false;
```

**Un ejemplo del codigo:**

![Booleano](/img/Variables4.png)

> Este tipo de datos solo admite los valores: **_True or False_**

## Float
Este tipo de valores son aquellos que almacenan numeros decimales, estas se declaran de la siguiente manera:

```vb
'Declaracion de una variable Float'
Dim numero_decimal As Float= 10.5;
```

**Un ejemplo del codigo:**

![Float](/img/Variables5.png)

## Notas Finales

Aqui vimos lo que son las variables de tipo basica, existen mas tipos pero solo hemos visto las mas usadas. En la siguiente leccion veremos como imprimir nuestro valor de las variables en un programa.

> Si quieres mas informacion al respecto puedes checar la seccion de Extras de la guia.


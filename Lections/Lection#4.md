# Operadores Logicos en Gambas

Son aquellos en los que podemos evaluar condiciones que nosotros especifiquemos y revisar si se cumplen o no. En esta seccion veremos algunos de ellos y como usarlos en nuestro codigo

## Operador AND
Se utiliza para evaluar dos condiciones y si ambas se cumplen, entonces se ejecuta el codigo que se encuentra dentro del bloque if.
Normalmente se usa la palabra clave AND.
    
```vb
'Condiciones a utilizar'
Dim condicion as Byte= 10 + 5
Dim condicion_2 As Byte= 20+5
'Evaluacion de la Condicion'
Dim resultado As Boolean = condicion== 15 AND condicion_2 < condicion
```
> Aqui la variable resultado sera **false** ya que  la variable **condicion** es igual a 15 pero la variable **condicion_2** no es menor a la variable **condicion**

![AND](/img/and.png)

> Aqui el resultado seria **true** tambien ya que **condicion_1** es mayor a **condicion_2** y **condicion_2** es menor a **condicion_1**

## Operador OR
Se utiliza para evaluar dos condiciones y si al menos una de ellas se cumple ya que no es necesario que se cumplan mas.
Normalmente se usa la palabra clave OR.
    
```vb
'Condiciones a utilizar'
Dim condicion as Byte= 10 + 5
Dim condicion_2 As Byte= 20+5
'Evaluacion de la Condicion'
Dim resultado As Boolean = condicion== 15 OR condicion_2 < condicion
```
> Aqui el resultado es **true** ya que la variable **condicion** es igual a 15 pero la variable **condicion_2** no es menor a la variable **condicion**

![OR](/img/Or.png)
> Aqui el resultado es **true** ya que la variable **condicion_1** es mayor a **condicion_2** pero  **condicion_2** no es mayor a **condicion_1**

## Operador NOT
Se utiliza para poder darle un valor contrario a una condiciones, es decir, si una condicion es **true** con el operador **NOT** se vuelve **false** y viceversa.

```vb
'Condiciones a utilizar'
Dim condicion as Byte= 10 + 5 //True
'Evaluacion de la Condicion'
Dim resultado As Boolean = Not(condicion== 15)
//False
```
> Aqui el resultado es **false** ya que la variable **condicion** es igual a 15

![NOT](/img/not.png)

## Notas
Si quieres saber mas sobre los Operadores logicos dirigete a la seccion de [Operadores Logicos](/Lections/Extras.md)
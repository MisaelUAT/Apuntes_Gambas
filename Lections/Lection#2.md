# Formas de Imprimir valor de Variables

Cuando nos referimos a imprimir el valor de una variable, nos referimos a mostrar en pantalla el valor que tiene asignado una variable. Aqui te mostrare las diferentes formas de hacerlo.

## Consola
Una consola es uan interfaz textual en la que podemos interactuar con el sistema operativo sin necesidad de tener una interfaz grafica. Existen comandos para poder mostrar nuestros valores:

### Print
Este nos va a ayudar a mostrar todo el contenido que pongamos en ella ya sea texto o valor de variablea. Ejemplo:

```vb
'Impresion de texto'
Print("Hola Mundo")
'Impresion de valor de variable'
Dim nombre As String = "Juan"
Print(nombre)
```

**Se veria asi en  codigo:**

![Print](/img/Consola_print.png)

### Debug 
Este nos va a ayudar a mostrar el valor de una variable en especifico. Ejemplo:

```vb
'Impresion de texto'
Debug "Hola Mundo"
'Impresion de valor de variable'
Dim nombre As String = "Juan"
Debug nombre
```

**Se veria asi en  codigo:**

![Debug](/img/Consola_debug.png)

## Ventana
Una ventana es una interfaz grafica en la que podemos interactuar con el sistema operativo de manera visual.

### Label
Este nos va a ayudar a mostrar todo el contenido que pongamos en ella ya sea texto o valor de variablea. Si quieres utilizarla haz un formulario desde cero y en el explorador de componentes busca la opcion de Label y arrastrala al formulario. Ejemplo:

![Label](/img/Label.png)

**Como se veria en forma grafica:**

![Label](/img/Form1.png)

### Message
Este es un mensaje que se nos muestra al momento de realizar una cierta accion. En este caso trabajaremos con codigo y el formulario tambien.

```vb
'Impresion de texto'
Message("Misael")
'Impresion de valor de variable'
Dim nombre As String = "Juan"
Message(nombre)
```

**Se veria asi en  codigo:**

![Message](/img/Message_code.png)

**Como se veria en forma grafica:**

![Message](/img/Message.png)
[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Listas**

Puede organizar elementos en listas **ordenadas** y **no ordenadas**.


## **Listas ordenadas**

Para crear una **lista ordenada**, agregue líneas con **números seguidos de puntos**. Los números no tienen que estar en orden numérico, pero la lista **debe comenzar con el número uno**.
![listas_01](/IMG/listas_01.jpg "Listas ordenadas")


# **Buenas prácticas con listas ordenadas**

**CommonMark** y algunos otros lenguajes de marcado ligeros le permiten usar un paréntesis \(**\)**\) como delimitador (por ejemplo, **1\) Primer elemento**), pero no todas las aplicaciones **Markdown** lo admiten, por lo que no es una gran opción desde una perspectiva de compatibilidad. Por compatibilidad, **utilice únicamente puntos**.
![listas_02](/IMG/listas_02.jpg "Buenas prácticas")


# **Listas no ordenadas**

Para crear una **lista no ordenada**, **agregue guiones** \(**\-\), **asteriscos** \(**\***\) o **signos más** \(**\+**\) delante de las líneas. 
Sangra uno o más elementos para crear una lista anidada.
![listas_03](/IMG/listas_03.jpg "Listas no ordenadas")


# **Iniciar elementos de lista no ordenada con números**

Si necesita iniciar un elemento de lista no ordenada con un número seguido de un punto, puede utilizar una **barra invertida** \(**\\**\) para escapar el punto.
![listas_04](/IMG/listas_04.jpg "Escapar punto")


# **Buenas prácticas con listas no ordenadas**

Las aplicaciones de **Markdown** no se ponen de acuerdo sobre cómo manejar diferentes delimitadores en la misma lista. 
Por compatibilidad, **no mezcle ni combine delimitadores** en la misma lista; elija uno y manténgalo.
![listas_05](/IMG/listas_05.jpg "Buenas prácticas")


# **Agregar elementos en listas**
Para agregar otro elemento en una **lista** y al mismo tiempo preservar la continuidad de la lista, aplique al elemento una **sangría con cuatro espacios** o una **tabulación**, como se muestra en los siguientes ejemplos.


### **Agregar párrafo**
![listas_06](/IMG/listas_06.jpg "Agregar párrafos en listas")

La salida renderizada se ve así:
![listas_07](/IMG/listas_07.jpg "Salida renderizada")


### **Agregar citas en listas**
![listas_08](/IMG/listas_08.jpg "Agregar citas en listas")

La salida renderizada se ve así:
![listas_09](/IMG/listas_09.jpg "Salida renderizada")


### **Agregar listas en listas**
Puede anidar una **lista no ordenada** en una **lista ordenada** o viceversa.
![listas_10](/IMG/listas_10.jpg "Agregar listas en listas")

La salida renderizada se ve así:
![listas_11](/IMG/listas_11.jpg "Salida renderizada")

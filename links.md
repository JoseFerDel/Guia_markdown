[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Links**

Para crear un **link, o enlace, incluya el texto del **link**, lo que se verá en pantalla, entre **llaves cuadradas** \( **\[ y \]** \) (por ejemplo, **\[Duck Duck Go\]**) y a continuación y si espacios pon la **URL** entre paréntesis (por ejemplo, **\(https:\/\/duckduckgo.com\)**).   
![links_01](/IMG/links_01.jpg "Ejemplo de link")

La salida renderizada se ve así:
![links_02](/IMG/links_02.jpg "Salida renderizada")


## **Agregar títulos a links**

Opcionalmente, puedes agregar un **título** para un **enlace**. 
Este título aparecerá cuando el usuario pase el cursor sobre el enlace. 
Para agregar un título, escríbelo entre comillas después de la **URL**.   
```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

La salida renderizada se ve así:
[Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## **URLs y direcciones de correo electrónico**

Para convertir rápidamente una **URL** o **dirección de correo electrónico** en un **enlace**, enciérralo entre signos **menor que** \( **\<** \) y **mayor que** \( **\>** \).
![links_05](/IMG/links_05.jpg "Convertir en enlace")

La salida renderizada se ve así:
![links_06](/IMG/links_06.jpg "Salida renderizada")


## **Dando formato a links**

Para enfatizar los enlaces, agregue el código deseado antes y después de los corchetes y paréntesis. 
Para indicar enlaces como **código**, agregue un acento abiertos \( **\`** \) antes y despuñes del link y envuelvalo todo entre **llaves cuadradas**.
![links_07](/IMG/links_07.jpg "Formato en links")

La salida renderizada se ve así:
![links_08](/IMG/links_08.jpg "Salida renderizada")


## **Enlaces de estilo de referencia**

Los **enlaces de estilo de referencia** son un tipo especial de enlace que hace que las **URL** sean más fáciles de mostrar y leer en **Markdown**. 

Los **enlaces de estilo de referencia** se construyen en dos partes: 
* La parte que tiene la referencia dentro de tu texto.
y 
* La parte que colocamos en algún otro lugar del archivo con la referencia y la URL a la que se refiere.

### **Formatear la primera parte del enlace**

La parte que pondríamos dentro de nuestro texto tiene la siguienet sintaxis:
### `[Texto del enlace][etiqueta]`


> [Texto del enlace] 
> 	Esto es lo que aparecerá como el texto del enlace en tu documento.
> 
> [etiqueta]  
> 	Es la etiqueta que vamos a utilizar par referirnos a la URL a esta etiqueta (en este punto todavía no hemos definido esa etiqueta).


Por ejemplo:
### `Esto es [el enlace a Google][google].`

La salida renderizada quedaría así:

Esto es [el enlace a Google][google].

Tras escribir "**Esto es**", aparece la frase "**el enlace a Google**" como un vinculo pero el vinculo al que hace referencia, que no se ve en pantalla al renderizar, es la etiqueta \[google\].
Ahora tendremos que definir en otra parte del documento a que hace referencia \[google\].


### **Formatear la segunda parte del enlace**

Aquí es cuando definimos la etiqueta que hemos utilizado antes, o podríamos hacer esto primero para tener la etiqueta lista para varios usos.

La segunda parte de un **enlace de estilo de referencia** tiene los siguientes atributos:

1. La etiqueta, debe ir entre **llaves cuadradas**, seguida inmediatamente por **dos puntos** y al menos **un espacio** (por ejemplo, **\[etiqueta\]: **).
2. La URL del enlace, que opcionalmente puede encerrar entre caracteres menor que y mayor que \( **\< y \>** \).
3. El **título opcional del enlace**, que se puede incluir entre **comillas dobles**, **comillas simples** o **paréntesis**.

La sintaxis sería así:
### `[etiqueta]: URL "Título opcional"`

Esto no se mostrará al renderizar, esta parte del código es solo para establecer la relación entre la etiqueta y la URL a la que hace referencia.

Volviendo al ejemplo anterior, para que la etiqueta \[google\] funcione como un link a la web de google cualquier link que creemos dentro del texto tendremos que poner una línea como esta en alguna parte del texto:

### `[google]: https://www.google.com "Motor de búsqueda"`

Aquí además hemos agregado un título "Motor de búsqueda" que aparecerá si pasamos el puntero del mouse por encima del link.


### **Buenas practicas con links**

Las aplicaciones de **Markdown** no se ponen de acuerdo sobre cómo manejar los espacios en medio de una **URL**. 
Para mayor compatibilidad, intente codificar cualquier espacio en la URL con **\%20**. 
Alternativamente, si su aplicación **Markdown** admite **HTML**, puede usar la etiqueta HTML `a href=`.




















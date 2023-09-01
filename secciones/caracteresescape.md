[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Caracteres de escape**

Para mostrar un carácter literal que de otro modo se usaría para dar formato al texto en un documento **Markdown**, agregue una contra barra ( **\\** ) antes que el carácter (sin espacios).

Ejemplo

`\* Sin escapar el caracter asterisco del principio de esta línea esto sería una lista no ordenada.`


La salida renderizada de esto último sería esta:
> \* Sin escapar el caracter asterisco del principio de esta línea esto sería una lista no ordenada.`

Vemos que el asterisco sigue siendo un asterisco y no ha sido interpretado para dar formato al texto.


## **Caracteres que puedes escapar**

Signo   | Nombre
:---    | :---
\\      | Contrabarra
\`      | Acento grave
\*      | Asterisco
\_      | Barra baja
\{ \}   | 
\[ \]   | Corchetes
\< \>   | Menor que y mayor que
\( \)   | Paréntesis
\#      | Almohadilla
\+      | Signo de suma
\-      | Guión, signo de resta
\.      | Punto
\!      | Signo de exclamación
\|      | Tuberia


Otra forma de escapar la contrabarra \( **\\** \) es utilizando su código HTML `&#124;`

## **HTML**

Muchas aplicaciones de **Markdown** le permiten utilizar etiquetas **HTML** en texto con formato **Markdown**. Esto es útil si prefiere ciertas etiquetas HTML a la sintaxis de **Markdown**. 
Por ejemplo, a algunas personas les resulta más fácil utilizar etiquetas HTML para imágenes. Usar HTML también es útil cuando necesitas cambiar los atributos de un elemento, como especificar el color del texto o cambiar el ancho de una imagen ya que Markdown no hace esto.

Para usar **HTML**, coloque las etiquetas en el texto de su archivo con formato **Markdown**.

Así:
```
Esta palabra está en negrita con formato Markdown --> **Café**
 
Esta palabra está en cursiva con  --> <em>Pistachos</em>
```


La salida renderizada sería esta:

> Esta palabra está en negrita con formato Markdown --> **Café**
>  
> Esta palabra está en cursiva con  --> <em>Pistachos</em>


## **Buenas prácticas con HTML**

Por razones de seguridad, no todas las aplicaciones de **Markdown** admiten **HTML** en los documentos de Markdown. En caso de duda, consulta la documentación de tu aplicación **Markdown**. 
Algunas aplicaciones sólo admiten un subconjunto de etiquetas **HTML**.

Utilice líneas en blanco para separar elementos **HTML** a nivel de bloque como `<div>`, `<table>`, `<pre>` y `<p>` del contenido que haya alrededor. 
Intente no sangrar las etiquetas con tabulaciones o espacios, ya que eso puede interferir con el formato.

No puede utilices la sintaxis de **Markdown** dentro de etiquetas **HTML** a nivel de bloque. Por ejemplo, `<p>cursiva y **negrita**</p>` no funcionará.

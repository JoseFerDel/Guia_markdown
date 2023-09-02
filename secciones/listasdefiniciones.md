[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Listas de definiciones**

Algunos procesadores **Markdown** le permiten crear listas de definiciones de términos y sus definiciones correspondientes. 
Para crear una lista de definiciones, escriba el término en la primera línea y en la siguiente línea escriba **dos puntos seguidos de un espacio** y la definición.

Ejemplo:
```
Primer termino
:Esta es una definición para el primer termino.

Segundo termino
:Esta es una definición del segundo termino.
:Esta es otra definición para el segundo termino.
```

La salida renderizada en formato Markdown se ve así:

Primer termino   
:Esta es una definición para el primer termino.   

Segundo termino   
:Esta es una definición del segundo termino.   
:Esta es otra definición para el segundo termino.   

NOTA: Github no reconce las listas de definiciones de **Markdown**.



En HTML se escribiría así:   
```
<dl>   
    <dt>Primer termino</dt>   
    <dd>Esta es la definición del primer termino</dd>   
    <dt>Segundo termino<dt>   
    <dd>Esta es una definición del segundo termino</dd>   
    <dd>Esta es otra definición para el segundo termino</dd>   
</dl>   
```

Y la salida renderizada en HTML sería esta:   
<dl>   
    <dt>Primer termino</dt>   
    <dd>Esta es la definición del primer termino</dd>   
    <dt>Segundo termino<dt>   
    <dd>Esta es una definición del segundo termino</dd>   
    <dd>Esta es otra definición para el segundo termino</dd>   
</dl>   

NOTA: Github reconoce correctamente las listas de definiciones en formato HTML.

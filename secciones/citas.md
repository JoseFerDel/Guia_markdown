[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Citas**

Para aplicar el **formato de cita**, agregue el caraácter mayor que `>` delante de un párrafo.    
`> No por mucho tempranar amanece más madruga`

La salida renderizada se ve así:
> No por mucho tempranar amanece más madruga.

## **Citas con varios párrafos**

Las **citas** pueden contener **varios párrafos**. Agrega un signo **mayor que** (`>`) en las líneas en blanco entre los párrafos:

```
> No por mucho temporanar amanece más madruga.
>
> El sol tiene cuatro mil quinientos millones de años.
```

La salida renderizada se ve así:

> No por mucho temporanar amanece más madruga.
>
> El sol tiene cuatro mil quinientos millones de años.

## **Citas anidadas**
Las **citas** se pueden anidar. Agrega dos signos **mayor que** ( `>>`) delante del párrafo que desea anidar.

```
> No por mucho temporanar amanece más madruga.
>
>> El sol tiene cuatro mil quinientos millones de años.
```

La salida renderizada se ve así:

> No por mucho temporanar amanece más madruga.
>
>> El sol tiene cuatro mil quinientos millones de años.


## **Citas con otros elementos**

Las **citas** pueden contener **otros elementos** formateados en **Markdown**. 
No se pueden utilizar todos los elementos; deberá experimentar para ver cuáles funcionan.

```
> ## Esta cita está quedando genial.
> 
> - Punto uno
> - Punto dos
>
> **Me encanta** que los planes salgan bien.
```

La salida renderizada se ve así:

> ## Esta cita está quedando genial.
> 
> - Punto uno
> - Punto dos
>
> **Me encanta** que los planes salgan bien.


## **Buenas prácticas con citas**

Por compatibilidad, coloque **líneas en blanco** antes y después de las comillas en bloque.

## Haz esto
```
Intenta poner lineas en blanco antes...     
                                            
> Esto es una cita.                         
                                            
... y después de la cita.                                     
```
    
    
## No hagas esto

```
Sin la línea en blanco esto no se ve bien.
> Esto es a una cita.
No lo hagas.
```
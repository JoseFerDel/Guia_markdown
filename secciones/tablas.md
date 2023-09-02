[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Tablas**

Para agregar una **tabla**, use **tres o más guiones** \( **\-\-\-** \) para crear el **encabezado** de cada columna y use barras verticales, o tuberías, \( **\|** \) para separar cada columna. 
Para mayor compatibilidad, también debes agregar una tubería \( **\|** \) en cada extremo de la fila.

Ejemplo:

```
Encabezado 1 	| 	Encabezado 2
----		|	----
Cosa 1		|	Cosa A
Cosa 2		|	Cosa B
Cosa 3		|	Cosa C
```

Aquí hemos utilizado tambulaciones para que el código sea más facil de leer pero los anchos de celda pueden variar, como se muestra a continuación: 

```
Encabezado 1 | Encabezado 2
---- | ----
Cosa 1 | Cosa A
Cosa 2 | Cosa B
Cosa 3 | Cosa C
```

El resultado renderizado de ambos ejemplos quedaría así:

Encabezado 1    |       Encabezado 2
----            |       ----
Cosa 1          |       Cosa A
Cosa 2          |       Cosa B
Cosa 3          |       Cosa C


## **Alineación**

Puede alinear el texto de las columnas a la **izquierda**, a la **derecha** o al **centro** agregando **dos puntos** \( **\:** \) a la **izquierda**, a la **derecha** o a **ambos lados** de los guiones dentro de la fila del **encabezado**.

```
ALINEACiÓN IZQ 	| 	ALINEACIÓN CEN 	| 	ALINEACIÓN DER
:----		|	:----:		|	----:
Cosa 1		|	Cosa A		|	Cosa Alfa
Cosa 2		|	Cosa B		|	Cosa Beta
Cosa 3		|	Cosa C		|	Cosa Gamma
```

La salida renderizada quedaría así:

ALINEACiÓN IZQ  |       ALINEACIÓN CEN  |       ALINEACIÓN DER
:----           |       :----:          |       ----:
Cosa 1          |       Cosa A          |       Cosa Alfa
Cosa 2          |       Cosa B          |       Cosa Beta
Cosa 3          |       Cosa C          |       Cosa Gamma


## **Formateando texto en tablas**

Puede formatear el texto dentro de las tablas. Por ejemplo, puede agregar enlaces, código (palabras o frases entre comillas invertidas \( **\`** \) únicamente, no bloques de código) y énfasis (Negrita y/o cursiva).

No puede utilizar **encabezados**, **citas**, **listas**, **reglas horizontales**, **imágenes** ni **la mayoría de las etiquetas HTML**.


## **Escapando caracter de tubería en tablas**

Puede mostrar un carácter de barra vertical \( \| \) en una tabla utilizando su código de carácter HTML (`&#124;`) o escapandolo \( `\|` \).



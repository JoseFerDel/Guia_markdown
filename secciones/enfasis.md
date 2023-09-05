[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Énfasis**

Puede agregar **énfasis** poniendo el texto en **negrita** o **cursiva**.


## **Negrita**
Para poner **texto en negrita**, agregue **dos asteriscos o guiones bajos** antes y después de una palabra o frase. 
Para poner en **negrita** parte de una palabra para darle énfasis, agregue **dos asteriscos**, sin espacios, alrededor de las letras.

Markdown                            |   HTML                                            |   Salida renderizada
----                                |   ----                                            |   ----
`Me gusta la letra en **negrita**.`   | `Me gusta la letra en <strong>negrita</strong>.`    |   Me gusta la letra en **negrita**.
`Me gusta la letra en __negrita__.`   | `Me gusta la letra en <strong>negrita</strong>.`    |   Me gusta la letra en __negrita__.

## **Buenas prácticas con negrita**

Las aplicaciones de **Markdown** no se ponen de acuerdo sobre cómo manejar los **guiones bajos** en medio de una palabra. 
Por compatibilidad, **utilice asteriscos** para poner en negrita el centro de una palabra para darle énfasis.

Haz esto                            |   No hagas esto
----                                |   ----
`Solo dos le**tr**as en negrita.`   |   `Solo dos le__tr__as en negrita.`

## **Cursiva**

Para poner texto en **cursiva**, agregue **un asterisco o guión bajo** antes y después de una palabra o frase. 
Para poner en **cursiva** parte de una palabra para darle énfasis, agregue un asterisco sin espacios alrededor de las letras.

Markdown                            |   HTML                                      |   Salida renderizada
----                                |   ----                                      |   ----
`La letra cursiva es *elegante*.`   |   `La letra cursiva es <em>elegante</em>.`  |   La letra cursiva es *elegante*.
`La letra cursiva es _elegante_.`   |   `La letra cursiva es <em>elegante</em>.`  |   La letra cursiva es _elegante_.
`Solo pa*rt*e de la palabra.`       |   `Solo pa<em>rt</em>e de la palabra.`      |   Solo pa*rt*e de la palabra.`

## **Buenas prácticas con cursiva**

Las aplicaciones de **Markdown** no se ponen de acuerdo sobre cómo manejar los guiones bajos en medio de una palabra. Por compatibilidad, **utilice asteriscos** `*` para poner en cursiva la mitad de una palabra para darle énfasis.

Haz esto                        |   No hagas esto
----                            |   ----
`Par*cial*mente en cursiva.`    |   `Par_cial_mente en cursiva.`


## **Negrita y cursiva (juntas)**

Para enfatizar el texto con **negrita y cursiva** al mismo tiempo, agregue **tres asteriscos o guiones bajos** antes y después de una palabra o frase.   
Para poner en **negrita y cursiva** parte de una palabra para darle énfasis agregue **tres asteriscos sin espacios** alrededor de las letras.     

Markdown                                        | HTML                                                      |  Salida renderizada
----                                            | ----                                                      |  ----
`Este texto es ***muy importante***.`            | `Este texto es <em><strong>muy importante</strong></em>.` |  Este texto es ***muy importante***.
`Este texto es ___muy importante___.`            | `Este texto es <em><strong>muy importante</strong></em>.` |  Este texto es ___muy importante___.
`Este texto es __*muy importante*__.`            | `Este texto es <em><strong>muy importante</strong></em>.` |  Este texto es __*muy importante*__.
`Este texto es super***mega***giga importante.` | `Este texto es super<em><strong>mega</strong></em>giga importante.` |  Este texto es super***mega***giga importante.


**Nota:** El orden de las etiquetas em y strong (en HTML) puede invertirse según el procesador Markdown que esté utilizando.


## **Buenas prácticas de negrita y cursiva (juntas)**

Las aplicaciones de **Markdown** no se ponen de acuerdo sobre cómo manejar los **guiones bajos** en medio de una palabra. 
Por compatibilidad, **utilice asteriscos** para poner en **negrita y cursiva** parte de una palabra para darle énfasis.

Haz esto                                        |   No hagas esto
----                                            |   ----
`Este texto es super***mega***giga importante.` |   `Este texto es super___mega___giga importante.`


[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **ID de encabezado**

Muchos procesadores **Markdown** admiten ID personalizados para encabezados; algunos procesadores **Markdown** los agregan automáticamente. 
Agregar **ID personalizados** le permite vincular directamente a los encabezados y modificarlos con **CSS**. 
Para agregar una **ID de encabezado personalizada** incluye la **ID personalizada** entre llaves `{` y `}` en la misma línea que el encabezado.


Ejemplo:
```
### Mi gran encabezado{id-encezado}
```

Esto miso en **HTML** se vería así:
```
<h3 id="id-encabezado">Mi gran encabezado</h3>
```

La salida renderizada de esto sería esta:

### Mi gran encabezado{id-encabezado"}


## **Vinculación a ID de encabezado**

Puede vincular títulos con **ID personalizados** en el archivo creando un vínculo estándar con un signo almohadilla \( **\#** \) seguido del **ID del encabezado personalizado**. 
Estos se conocen comúnmente como **enlaces de anclaje**.

Por ejemplo en **Markdown** sería así:
```
[Texto de ejemplo](#id-encabezado)
```

Y en HTML así:
``` 
<a href="#id-encabezado">Texto de ejemplo</a>
```

La salida renderizada sería esta:
Otros sitios web pueden vincular a

Otros sitios web pueden vincular al encabezado agregando el ID del encabezado personalizado a la URL completa de la página web 

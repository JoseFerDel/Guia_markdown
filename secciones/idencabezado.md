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

---

La salida renderizada del código **Markdown** sería esta:

### Mi gran encabezado{id-encabezado}

---

Y la salida del código HTML sería esta:

<h3 id="id-encabezado">Mi gran encabezado</h3>


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
Para que los enlaces a id de encabezado funcionen deben estar lo suficientemente lejos unos de los otros, alargaré está página con unas imagenes random para que se vea bien como funcionan.

![Gato](/IMG/Markdown/gato_cielo.jpeg "Gato")

![Gato](/IMG/Markdown/Pixel_cell.gif "Gato")

![Gato](/IMG/Markdown/Gato_capucha.jpg "Gato")


La salida renderizada del código **Markdown** sería esta:

[Texto de ejemplo](#id-encabezado)

Y la salida renderizada del código HTML sería esta:   

<a href="#id-encabezado">Texto de ejemplo</a> 

Si hacemos clic en estos enlaces, y este se encuentra lo suficientemente lejos del id de encabezado indicado más arriba (`### Mi gran encabezado{id-encabezado}`), entonces saltaremos a la parte del texto que contiene el id.
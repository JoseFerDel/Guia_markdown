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


**NOTA:** Parece que Github no reconoce las id de encabezado de Markdown.

---

Y la salida del código HTML sería esta:

<h3 id="id-encabezado">Mi gran encabezado</h3>

**NOTA:** Github reconoce correctamente los id de encabezado en HTML.




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

La salida renderizada del código **Markdown** sería esta:

[Texto de ejemplo](#id-encabezado)

Y la salida renderizada del código HTML sería esta:   

<a href="#id-encabezado">Texto de ejemplo</a> 

**NOTA:**
En Github estos links no hacen nada pero si utilizamos un editor Markdown que acepte los id de encabezado, Github no los acepta, al hacer clic en el enlace nos moverá a la parte del texto donde se encuentra el id indicado.
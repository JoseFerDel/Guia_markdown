[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Imágenes**

La forma más básica de insertar una imagen con **Markdown** es introducir el siguiente código formado por dos partes:

**Sintaxis:**
```
![Descripción](ruta_de_la_imagen)
```

Por ejemplo:

Si escibimos este código:

```
Lo siguiente es una imagen:
![Formas_cell](/IMG/Cell_formas.png)
```

La salida renderizada sería esta:

Lo siguiente es una imagen:     
![Formas_cell](/IMG/Markdown/Cell_formas.png)


Opcionalmente, puede agregar un título entre comillas después de la ruta o URL.

```
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
```
El texto final entre comillas se verá al pasar el puntero del mouse por encima de la imagen.

La salida renderizada se ve así:
![Imagenes_03](/IMG/Markdown/Imagenes_03.jpg "Imagen con título")


Imagenes con vinculos 

Para agregar un enlace a una imagen, incluya el código **Markdown** de la imagen entre llaves cuadradas \( **\[** y **\]** \) y luego agregue el enlace entre paréntesis.
```
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://t.ly/BdY68)
```

La salida renderizada se ve así:
[![Imagenes_04](/IMG/Markdown/Imagenes_04.jpg "Imagenes con vinculos")](https://t.ly/BdY68)   
Si hacemos clic en la imagen nos llevará a la web **https://www.flickr.com**

Markdown no permtie especificar la alineación de una imagen, para hacerlo nos apoyaremos en el código HTML:


**Ejemplo para imagen centrada:**
```
<p align="center">
  <img height="600" src="Monje.jpg">
</p>
```


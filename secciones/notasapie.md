[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


## **Notas a pie de página**

Las **notas al pie** le permiten agregar notas y referencias sin saturar el cuerpo del documento. Cuando crea una **nota al pie**, aparece un número en **superíndice** con un enlace donde se agregó la referencia de la **nota al pie**. Los lectores pueden hacer clic en el enlace para saltar al contenido de la **nota al pie** en la parte inferior de la página.

Para crear una **referencia de nota al pie**, agrega un **acento circunflejo** \( **\^** \) y un identificador entre **corchetes** `[^1]`. Los identificadores pueden ser **números** o **palabras**, pero no pueden contener espacios ni tabulaciones. Los identificadores solo correlacionan la referencia de la nota al pie con la nota al pie misma, en el resultado las notas al pie se numeran secuencialmente.

Agregue la **nota al pie** usando otro signo circunflejo ` ^ ` y numere entre corchetes con dos puntos y texto ( Por ejemplo --> `[^1]: Mi nota al pie`). No es necesario poner notas a pie de página al final del documento. Puede colocarlos en cualquier lugar excepto dentro de otros elementos como **listas**, **citas** y **tablas**.


Ejemplo:
```
Esta es una nota al pie simple, [^1] y esta otra es una nota al pie más larga. [^grannnota]


[^1]: Esta es la primera nota al pie.

[^grannota]: Esta la segunda nota al pie con multiples párrafos y código.
    Indentamos los párrafos para incluirlos en la nota al pie.
    `{ mi código }`

    ```
    def función:
        cosas cosas
    ```
```

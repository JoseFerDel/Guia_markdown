[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Bloques de código**

Para crear bloques de código, sangra cada línea del bloque con al menos **cuatro espacios** o una **tabulación**.

Así:
```
	<html>
		<head>
		</head>
	</html>
```

La salida renderizada se ve así:   

	<html>
		<head>
		</head>
	</html>      

**Nota:** Para crear bloques de código sin sangrar líneas, utilice bloques de código delimitados.  
**Ver →** [Bloques de código delimitados](https://github.com/JoseFerDel/Guia_markdown/blob/Zet_main/secciones/codeblocks_delimitados.md)
                                          

## **Palabra o frase como código** 

Para indicar una palabra o frase como código, escríbala entre **acentos graves** ``` ` ```.

Los acentos graves son los que aparecen al punsar esta tecla:     
![Acento_grrave](/IMG/Markdown/acento_grave.jpg "Acento grave") 

Markdown				|	HTML							|	Salida renderizada
----					|	----							|	----
El el terminal escribe \`vim\`.		|	En el terminal escribe \<code\>vim\<\/code\>		|	En el terminal escribe `vim`
				


## **Escapar acentos graves**

Si la palabra o frase que desea indicar como código incluye uno o más **acentos graves** ``` ` ```, puede escaparlos encerrando la palabra o frase entre acentos graves **dobles** ``` `` ```.          


Markdown						|	HTML								|	Salida renderizada	
----							|	----								|	----
\`\`Utiliza \`código\` en tu archivo Markdown.\`\`	|	\<code\>Utiliza \`código\` en tu archivo Markdown.\<\/code\>	|	``Utiliza `código` en tu archivo Markdown.``




## **Código en listas**

Los **bloques de código** normalmente tienen una sangría de **cuatro espacios** o **una tabulación**. Cuando estén en una **lista**, sangra **ocho espacios** o **dos tabulaciones**.

Así:     
```     
1. Abre el archivo.      
2. Encuentra el siguiente bloque de código en la línea 26:       

		<html>     
			<head>     
			</head>     
		</html>      

3. Actualiza el titulo para que coincida con el nombre de la página.     
```      

La salida renderizada quedaría así:      

1. Abre el archivo.      
2. Encuentra el siguiente bloque de código en la línea 26:      

		<html>      
			<head>      
			</head>     
		</html>      

3. Actualiza el titulo para que coincida con el nombre de la página.     

**NOTA:** El bloque de código debe estar separado del resto de la lista por una línea vacía tanto por arriba como por abajo.

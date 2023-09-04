[ÍNDICE](https://github.com/Zet0699/Guia_markdown/blob/Zet_main/README.md)


# **Bloques de código**

Para crear bloques de código, sangra cada línea del bloque con al menos **cuatro espacios** o una **tabulación**.
![codeblocks_01](/IMG/codeblocks_01.jpg "Bloques de código")

Así:
```
	<html>
		<head>
		</head>
	</html>
```

La salida renderizada se ve así:   
![codeblocks_02](/IMG/codeblocks_02.jpg "Salida renderizada")   

	<html>
		<head>
		</head>
	</html>      

**Nota:** Para crear bloques de código sin sangrar líneas, utilice bloques de código delimitados.  
**Ver →** [Bloques de código delimitados](https://github.com/JoseFerDel/Guia_markdown/blob/Zet_main/codeblocks_delimitados.md)


## **Palabra o frase como código** 

Para indicar una palabra o frase como código, escríbala entre **acentos graves** ``` ` ```.
![codeblocks_03](/IMG/codeblocks_03.jpg "Palabra o frase como código")

Markdown				|	HTML							|	Salida renderizada
----					|	----							|	----
\`\`El el terminal escribe \`vim\`.\`\`	|	\`En el terminal escribe \<code\>vim\<\/code\>\`	|	En el terminal escribe 'vim'
				


## **Escapar comillas invertidas**

Si la palabra o frase que desea indicar como código incluye uno o más **acentos graves** \`, puede escaparla encerrando la palabra o frase entre acentos graves dobles \( **\`\`** \).      
![codeblocks_04](/IMG/codeblocks_04.jpg "Escapar acentos abiertos")


Markdown						|	HTML						|	Salida renderizada	
----							|	----						|	----
\`\`Utiliza \`código\` en tu archivo Markdown.\`\`	|	Utiliza `código` en tu archivo Markdown.	|	``Utiliza `código` en tu archivo Markdown.``




## **Código en listas**

Los **bloques de código** normalmente tienen una sangría de **cuatro espacios** o **una tabulación**. Cuando estén en una **lista**, sangra **ocho espacios** o **dos tabulaciones**.
![codeblocks_05](/IMG/codeblocks_05.jpg "Código en listas")

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




La salida renderizada se ve así:
![codeblocks_06](/IMG/codeblocks_06.jpg "Salida renderizada")


# Aula 6 - Conteúdo

## Teoria - Introdução ao CSS Cascating Style Sheet
Cascading Style Sheets (CSS) é uma linguagem de folhas de estilo utilizada para definir a apresentação de documentos escritos em uma linguagem de marcação, como HTML ou XML.

* [Fonte](https://pt.wikipedia.org/wiki/Cascading_Style_Sheets "")

###Incorporação de estilo interno (em head ou body):
```
<head>
	<style>
		body {
		    background-color: linen;
		}

		h1 {
		    color: maroon;
		    margin-left: 40px;
		} 
	</style>
</head>
```
###Incorporação de estilo inline (como atributo de uma tag):
```
<h1 style="color:blue; margin-left:30px;">Título 1</h1>
```

###Incorporação de estilo externo:
```
<head>
	<meta charset="UTF-8">
	<title>Elementos HTML</title>
	<link rel="stylesheet" href="estilo.css">
</head>
```

## Teoria - Cores na web
Cascading Style Sheets (CSS) é uma linguagem de folhas de estilo utilizada para definir a apresentação de documentos escritos em uma linguagem de marcação, como HTML ou XML.

###Sistemas de Cores - RGB (Red, Green e Blue – ou Vermelho, Verde e Azul)

```
h1 {
	color: rgb(0, 0, 255);
}
```

###Sistemas de Cores - Hexadecimal

```
h1 {
	color: #0000ff;
}
```

###Sistemas de Cores - HSL

```
h1 {
	color: hsl(240, 100%, 50%);
}
```

###Conteúdo pendente....

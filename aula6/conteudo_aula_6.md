# Aula 6 - Conteúdo

## Teoria - Introdução ao CSS Cascating Style Sheet
Cascading Style Sheets (CSS) é uma linguagem de folhas de estilo utilizada para definir a apresentação de documentos escritos em uma linguagem de marcação, como HTML ou XML.

* [Fonte](https://pt.wikipedia.org/wiki/Cascading_Style_Sheets)

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

## Teoria - Estrutura CSS
**Seletor:** genericamente, é o elemento HTML identificado por sua tag, ou por uma **classe**, ou por uma **ID**, ou etc., e para o qual a regra será válida, por exemplo:
```
p
h1
form
.minha-classe
#meu-id
```


**Propriedade:** é o atributo do elemento HTML ao qual será aplicada a regra (por exemplo: **font**, **color**, **background**, etc...).

**Valor:** é a característica específica a ser assumida pela propriedade (por exemplo: letra tipo arial, cor azul, fundo verde, etc...)

```
seletor { 
	propriedade: valor; 
}	
```
* [Fonte](http://www.maujor.com/tutorial/sintaxetut.php)

### Seletor ID 
O seletor ID difere do seletor classe, por ser **ÚNICO**. Um seletor ID de determinado nome só pode ser aplicado a UM e somente UM elemento HTML dentro do documento.
![Alt text](highlander_there_can_be_only_one_quote.jpg)

```
#meu-id {
	propriedade: valor;
}
```
* [Fonte](http://www.maujor.com/tutorial/sintaxetut.php)

### Seletor Classe 
O seletor classe permite que mais vários elemetos HTML compartilhem as mesmas propriedades.
**HTML**
```
<h2 class="hero-titulo"></h2>
...
<h3 class="hero-titulo"></h3>
...
<p class="hero-titulo"></p>
```

**CSS**
```
.hero-titulo { 
	color: #000;
	font-size: 30px;
} 
```
No exemplo acima todas as **Tags HTML** com a classe **hero-titulo** compartilham as mesmas propriedades e seus respectivos valores como **color** e **font-size**.

![Alt text](cute-baby-sharing-food-cat-8lo8-ytgifs-o.gif)

* [Fonte](http://www.maujor.com/tutorial/sintaxetut.php)









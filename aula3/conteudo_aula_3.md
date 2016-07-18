# Aula 2 - Conteúdo

## Tags HTML - Âncoras

Âncoras são links que direcionam para uma seçao da página atual ou de outra página.
O Link referência sempre um ID de uma seção ou outro elemento HTML através da estrutura #nome-do-id 
```
<ul>
	<li><a href="#secao1">Titulo 1</a></li>
	<li><a href="#secao2">Titulo 2</a></li>
	<li><a href="#secao3">Titulo 3</a></li>
	<li><a href="#secao4">Titulo 4</a></li>
	<li><a href="#secao5">Titulo 5</a></li>
</ul>

<section id="secao1">...</section>
<section id="secao2">...</section>
<section id="secao3">...</section>
<section id="secao4">...</section>
<section id="secao5">...</section>

```

## Tags HTML - Links Externos
Links externos possuem a propriedade *href=""* normalmente com uma url no formato *http://* e o atributo *target="_blank"* redireciona o link para uma nova aba do navegador:
```
<ul>
	<li><a href="http://g1.globo.com" target="_blank">G1</a></li>
	<li><a href="http://google.com" target="_blank">Google</a></li>
	<li><a href="https://github.com/zeroaheroi" target="_blank">Zero a Herói</a></li>
	<li><a href="http://chocoladesign.com/" target="_blank">Chocoladesign</a></li>
</ul>
```

## Tags HTML - Links Internos - Outros Documentos HTML
Links internos redirecionam para outros documentos HTML *dentro da mesma estrutura de pastas*.
```
<ul>
	<li><a href="home.html">Home</a></li>
	<li><a href="sobre.html">Sobre</a></li>
	<li><a href="fotos.html">Fotos</a></li>
	<li><a href="contato.html">Contato</a></li>
</ul>
```

## Tags HTML - Listas Ordenadas
```
<ol>
	<li>item 1</li>
	<li>item 2</li>
	<li>item 3</li>
	<li>item 4</li>
	<li>item 5</li>
</ol>
```

## Tags HTML - Aninhamento de Listas
```
<ul>
	<li>
		Item 1
		<ul>
			<li>Subitem 1</li>
			<li>Subitem 2</li>
			<li>Subitem 3</li>
		</ul>
	</li>
	<li>Item 2</li>
	<li>Item 3</li>
</ul>
```

## Configuração do Sublime Text 3 e Atalhos de Produtividade

* [Turbinando o Sublime](https://www.youtube.com/watch?v=2rrK2LiS5Eo "")
* [7 Plugins do sublime text que você deveria conhecer](http://tableless.com.br/7-plugins-sublime-text-que-voce-deveria-conhecer/ "")
* [Atalhos do Sublime](https://www.viget.com/articles/my-overused-sublime-text-keyboard-shortcuts "")
* Instalação do Material Theme - [Link](https://github.com/equinusocio/material-theme "")
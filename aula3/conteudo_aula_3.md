# Aula 3 - Conteúdo

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
## Tags HTML - Imagens
Imagens são incluídas através da tag *img* e obrigatóriamente é necessário aplicar o atributo *src* (source / fonte) e o atributo *alt* requisito para melhoria da *acessibilidade* do site e para validação na [W3C](https://validator.w3.org/ "W3C Validator").

### Requisições de imagens externas
```
<img src="http://dogstrainingconcept.com/wp-content/uploads/2013/03/treino_cao.png" alt="Imagem Cão">
```

### Requisições de imagens internas (estrutura de pasta)
```
<img src="silvio.jpg" alt="">
```

## Tags HTML - Combinação entre links e imagens

```
<a href="http://www.sbt.com.br/home/" target="_blank" title="Página do SBT">
	<img src="silvio.jpg" alt="Imagem Silvio Santos">
</a>
```

## Criação de Pasta de projeto - SITE

```
site/
|   |-- home.html             # Título, Imagem e Links
|   |-- sobre.html            # Parágrafos, Título e Links
|   |-- fotos.html            # Galeria de Fotos
|   |-- contato.html          # Contato e Formulários de Contato
|   |
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto

```

## Referências e Materiais de Suporte

* [O poder do atributo “ALT”](http://tableless.com.br/o-poder-do-atributo-alt/ "")
* [Modelo de Acessibilidade em Governo Eletrônico](http://emag.governoeletronico.gov.br/ "")
* [Cartilha Acessibilidade](http://www.w3c.br/pub/Materiais/PublicacoesW3C/cartilha-w3cbr-acessibilidade-web-fasciculo-I.pdf "")
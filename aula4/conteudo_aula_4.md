# Aula 4 - Conteúdo

## Tags HTML - Formulários
Nos formulários os *tipos / types* determinam a validação dos tipos de dados que vão entrar no formulário, o próprio navegador poderá fazer essa validação posteriormente com o atributo *required* 
```
<form>
	<input type="text" placeholder="Digite seu nome completo">
	<input type="email" placeholder="Ex: pedro@email.com.br">
	<input type="text" placeholder="">
	<textarea placeholder="Mensagem:"></textarea>
	<input type="submit" value="Enviar">
</form>
```
## Tags HTML - Formulários com Labels ( Rótulos )
Rótulos são apenas marcações de título para os campos inputs
```
<form>
	<label>Nome:</label>
	<br>
	<input type="text">
	<label>Email:</label>
	<br>
	<input type="email">
	<label>Assunto</label>
	<br>
	<input type="text">
	<label>Mensagem</label>
	<br>
	<textarea></textarea>
	<br>
	<input type="submit" value="Enviar">
</form>
```

## Tags HTML - Formulários com Validação
Validação é a marcação de um *atributo* que faz com que um campo tenha seu preenchimento *obrigatório*. O Atributo *required* deve ser aplicado ao input:
```
<form>
	<label>Nome*</label>
	<br>
	<input type="text" required>
	<label>Email*</label>
	<br>
	<input type="email" required>
	<label>Assunto*</label>
	<br>
	<input type="text" required>
	<label>Mensagem*</label>
	<br>
	<textarea required></textarea>
	<br>
	<input type="submit" value="Enviar">
</form>
```

## Tags HTML - Formulários com valores de campos definidos
É possível aplicar um valor padrão aos inputs através do atributo *value*, aplicável *apenas* aos elementos *input*:
```
<form>
	<label>Nome*</label>
	<br>
	<input type="text" value="Vinícius Ribeiro Fernandes">
	<label>Email*</label>
	<br>
	<input type="email" value="vinicius@zeroaheroi.com.br">
	<label>Assunto*</label>
	<br>
	<input type="text" value="Curso de Front-end Development">
	<label>Mensagem*</label>
	<br>
	<textarea>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur perferendis excepturi quos? Hic vel ratione illo sunt distinctio assumenda fugit repellat quod unde provident. Id molestiae fugiat quos quod quasi?</textarea>
	<br>
	<input type="submit" value="Enviar">
</form>
```

## Tags HTML - Mídias Incorporadas / Iframe
O elemento *iframe* é utilizado para incorporar conteúdos externos dentro de um elemento HTML, sendo possível fazer a vinculações de mídias diversas como *vídeos do youtube*, *vimeo*, *google maps*, *tweets*, entre outros: 
```
<!-- exemplo 1 Youtube-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7iwhEGSjvJU" frameborder="0" allowfullscreen></iframe>

<!-- exemplo 2 - Google Maps-->
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3775.310746105861!2d-41.961844385950286!3d-18.87329068720454!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40fcb8dd43a05b5%3A0xc0877b696b220e30!2sUniversidade+Vale+do+Rio+Doce%2C+Campus+Armando+Vieira!5e0!3m2!1spt-BR!2sbr!4v1468541338286" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

<!-- exemplo 3 - Tweet-->
<blockquote class="twitter-tweet" data-lang="en"><p lang="pt" dir="ltr">Rede social pedia o primeiro filho dos usuários nos termos de serviço - e ninguém ligou <a href="https://t.co/IKE9R9LsMO">https://t.co/IKE9R9LsMO</a> <a href="https://t.co/ZoigsuVnlq">pic.twitter.com/ZoigsuVnlq</a></p>&mdash; B9 (@brains9) <a href="https://twitter.com/brains9/status/753741311937839104">July 15, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<!-- exemplo 4 - Vimeo-->
<iframe src="https://player.vimeo.com/video/174544848" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
```

## Criação de Pasta de projeto - SITE DE BANDA

```
site/
|   |-- home.html             # Título, Imagem e Links
|   |-- sobre.html            # Parágrafos, Título e Links
|   |-- fotos.html            # Galeria de Fotos
|   |-- midias.html           # Galeria de Fotos
|   |-- contato.html          # Contato e Formulários de Contato
|   |
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto
|   |-- imagem_qualquer.jpg   # Imagem local para ser anexada ao projeto

```

## Tags HTML - Introdução aos elementos semânticos do HTML5
É possível aplicar um valor padrão aos inputs através do atributo *value*, aplicável *apenas* aos elementos *input*:
```
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>Title</title>
  </head>
  <body>
    <header>Cabeçalho do site</header>
    <nav>
      <a href="#">Navegação</a>
    </nav>
    <main>
      <article>
        <h1>Título do Artigo</h1>
        <p>Conteúdo</p>
    </article>
	  <aside>
	    <p>Barra lateral (sidebar)</p>
	  </aside>
    </main>
    <footer>Rodapé - Copyright 2016</footer>
  </body>
</html>
```

## Referências e Materiais de Suporte

* [HTML5 - Estrutura semântica](http://tableless.com.br/html5-estrutura-semantica "")
* [HTML5 - Referência](http://tableless.com.br/html5-estrutura-semantica "")
* [Cartilha de Usabilidade do Governo Federal](http://www.egov.ufsc.br/portal/sites/default/files/padroes_brasil_e-gov_-_cartilha_de_usabilidade_v12.pdf"")
* [Site sobre CSS e Padrões Web](http://www.maujor.com/index.php "")
* [Cartilha Acessibilidade](http://www.w3c.br/pub/Materiais/PublicacoesW3C/cartilha-w3cbr-acessibilidade-web-fasciculo-I.pdf "")
* [Abduzeedo](http://abduzeedo.com.br/ "") - contém muitas referências boas tanto para Web quanto para design gráfico e possui alguns tutoriais também.
* [Choco la Design](http://chocoladesign.com/ "") (seção de Web Design) - ótimo site sobre design em geral. Este link vai para a seção de web design que possui artigos e sites para inspiração.
* [One Page Love](https://onepagelove.com/ "") - este é em inglês, mas é bastante intuitivo. Ele é ótimo para se ver antes de criar landing pages (páginas de apresentação rápida de alguma proposta. Utilizadas geralmente para pré-lançamento ou campanha de marketing digital) e hotsites.
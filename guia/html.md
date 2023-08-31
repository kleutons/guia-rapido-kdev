| [🏠 Voltar p/ Inicio](../) | [🏗️ HTML](./html.md) | [💈 CSS](./css.md) | [👨🏻‍💻 JAVAScript](./js.md) |


# Introdução ao HTML
## O que é um HTML?
> **HyperText Markup Language** (Linguagem de Marcação de Hipertexto).

- **Linguagem:** Uma forma de comunicação, estabelecida entre nós e o navegador de Internet (*Google Chrome, Firefox, Safari, Edge, Internet Explorer*, etc.).
- **Marcação:** O HTML "marca" os elementos em uma página, indicando o que é um texto, uma imagem, um vídeo e outros componentes.
- **Hipertexto:** O termo *"hipertexto"* é uma maneira elegante de se referir a um site.

**Em resumo,** o HTML é a tecnologia empregada para identificar e estruturar os elementos presentes em uma página de internet ou site, através do uso de TAG´s.

## Entendendo as TAG´s
TAG´s são como etiquetas. Elas representam os trechos de código que auxiliam na identificação dos elementos em uma página.


**Exemplo de TAG's.**
```html	
<img> -> tag de imagem

<p>Meu parágrafo aqui </p> -> tag parágrafo 

<h1>Meu título aqui</h1>   -> tag de título
```

## Estrutura Básica de um Site ou Página HTML

> Temos 3 TAG's principais, que vão ser a estrutura do nosso site.

`<html> </html>`  -> Todo nosso site fica aqui dentro

`<head> </head>`  -> Aqui são as configurações do nosso site

`<body> </body>`  -> Aqui vai toda a parte vísivel do nosso site

> Na prática, essa é a estrutura basica de um site HTML

```html
<html> 
<head> 
	<title> Título do Meu site </title>
</head>
<body>
	<h1> Meu primeiro Site! </h1>

	<p> Serei um Programador(a) de Sucesso! </p>
</body>
</html>
```

## Principais TAG's HTML (clique na seta para abri)


<details> <br>
<summary>Títulos - h1 até o h6</summary>

Em HTML, os títulos são categorizados de h1 a h6. O h1 representa o título de maior relevância na página, enquanto o h6 é atribuído aos títulos de menor importância.

<pre>
	<code>
&lt;h1&gt; Seu título H1 &lt;/h1&gt;
&lt;h2&gt; Seu título H2 &lt;/h2&gt;
&lt;h3&gt; Seu título H3 &lt;/h3&gt;
&lt;h4&gt; Seu título H4 &lt;/h4&gt;
&lt;h5&gt; Seu título H5 &lt;/h5&gt;
&lt;h6&gt; Seu título H6 &lt;/h6&gt;
	</code>
</pre>


</details>

<details> <br>
<summary>Paragrafo - &lt;p&gt; &lt;/p&gt; </summary>

<pre>
	<code>
&lt;p&gt; Meu parágrafo, texto que você desejar... &lt;/p&gt;
	</code>
</pre>

</details>

<details> <br>
<summary>Negrito - &lt;b&gt; &lt;/b&gt; </summary>

<pre>
	<code>
&lt;p&gt; Seu texto em &lt;b&gt;negrito&lt;/b&gt; ou &lt;strong&gt;Negrito&lt;strong&gt; &lt;/p&gt;
	</code>
</pre>

</details>


<details> <br>
<summary>Itálico  - &lt;i&gt; &lt;/i&gt; </summary>


<pre>
	<code>
&lt;p&gt; Esse é o meu &lt;i&gt;texto em itálico&lt;/i&gt; &lt;/p&gt;
	</code>
</pre>

</details>


<details> <br>
<summary>Título do site  - &lt;title&gt; &lt;/title&gt; </summary>


<pre>
	<code>
&lt;title&gt;Título do Meu site&lt;/title&gt;
	</code>
</pre>

</details>


<details> <br>
<summary>Cabeçalho - &lt;header&gt; &lt;/header&gt; </summary>
Essa tag define um cabeçalho. Ou seja, tudo que estiver dentro dessa tag <code>&lt;header&gt;</code> faz parte de um cabeçalho e pode ser usado dentro de outras sessões. Também pode conter outros elementos dentro da tag, como uma logo, um formulário de pesquisa, e outros.

<pre>
	<code>
&lt;header&gt;
	&lt;h1&gt;Olá&lt;/h1&gt;
&lt;/header&gt;
	</code>
</pre>

</details>

<details> <br>
<summary>Conteúdo Principal  - &lt;main&gt; &lt;/main&gt; </summary>
Essa tag representa o conteúdo principal do seu corpo, ou seja, o conteúdo principal do seu código. 
<pre>
	<code>
&lt;main&gt;
	&lt;h1&gt;Esse é um h1&lt;/h1&gt;
	&lt;h1&gt;Sou um parágrafo&lt;/h1&gt;
	&lt;h1&gt;Sou um botão&lt;/h1&gt;
	&lt;p&gt;Estamos todos dentro da tag main&lt;/p&gt;
&lt;/main&gt;
	</code>
</pre>
</details>


<details> <br>
<summary>Rodapé - &lt;footer&gt; &lt;/footer&gt; </summary>
Essas tags definem um rodapé para a página, geralmente utilizadas no final da página; 
<pre>
	<code>
&lt;footer&gt;
	Algumas informações de copyright ou talvez alguma outra informação 
&lt;/footer&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Sessões da página - &lt;section&gt; &lt;/section&gt; </summary>
Essa tag define uma sessão para sua página.
<pre>
	<code>
&lt;section&gt;
	&lt;h1&gt;Esse é um h1&lt;/h1&gt;
	&lt;p&gt;O resto do contéudo do seu site&lt;/p&gt;
&lt;/section&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Artigos - &lt;article&gt; &lt;/article&gt; </summary>
Essa tag define um artigo da sua página. Ela é utilizada para separar o conteúdo da sua página. É mais utilizada para criação de blogs, um artigo de revista ou jornal, página de conteúdos e etc.
<pre>
	<code>
&lt;article&gt;
	&lt;h1&gt;Tema de Um Artigo&lt;/h1&gt;
	&lt;p&gt;O resto do contéudo do seu artigo&lt;/p&gt;
&lt;/article&gt;
&lt;article&gt;
	&lt;h1&gt;Tema do Segundo Artigo&lt;h1&gt;
	&lt;p&gt;
		O resto do contéudo do seu artigo asdsad asdasdsada erasdas asdeas asdasd adas asdasdsa dafedsa adsa asfsafeacsafa safasf afeasfsa a asdfas
	&lt;/p&gt;
&lt;/article&gt;
	...
	</code>
</pre>
</details>

<details> <br>
<summary>Conteúdo  - &lt;aside&gt; &lt;/aside&gt; </summary>
A <code>&lt;aside&gt;</code> tag define algum conteúdo além do conteúdo em que é colocada. O conteúdo à parte deve estar indiretamente relacionado ao conteúdo principal.
<pre>
	<code>
&lt;p&gt;Texto qualquer para seu paragrafo&gt;	
&lt;aside&gt;
	&lt;h4&gt;Seu Titulo&lt;/h4&gt;
	&lt;p&gt;Texto qualquer para seu paragrafo&gt;
&lt;/aside&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Navegação - &lt;nav&gt; &lt;/nav&gt; </summary>
Essa tag define um conteúdo de navegação. Por isso, é muito utilizado em conjunto com listas e na criação de menus. Ou seja, uma seção com links de navegação.
<pre>
	<code>	
&lt;nav&gt;
	&lt;ul&gt;
		&lt;li&gt;&lt;a href="#"&gt;Página Principal&lt;/a&gt;&lt;/li&gt;
		&lt;li&gt;&lt;a href="#"&gt;Sobre&lt;/a&gt;&lt;/li&gt;
		&lt;li&gt;&lt;a href="#"&gt;Contato&lt;/a&gt;&lt;/li&gt;
	&lt;/ul&gt;
&lt;/nav&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Divisão da página  - &lt;div&gt; &lt;/div&gt; </summary>
Define uma divisão da página. Desta forma, funciona como um container para conteúdo da página. Uma vez que não possui um valor semântico, é muito utilizado para organizar melhor o conteúdo. 
<pre>
	<code>	
&lt;div&gt;
	&lt;p&gt;
		Qualquer tipo de conteúdo aqui. Como &lt;p&gt;, &lt;table&gt; &lt;h1&gt;. Você coloca o que desejar!
	&lt;/p&gt;
&lt;/div&gt;
	...
	</code>
</pre>
</details>

<details> <br>
<summary>Quebra de linha - &lt;br&gt; ou &lt;br /&gt; </summary>
Essa tag não necessita de fechamento. Sua função é a quebra de linha.
<pre>
	<code>	
&lt;p&gt;Primeiro texto &lt;/p&gt; &lt;br&gt;
&lt;p&gt;Segundo texto &lt;/p&gt; &lt;br&gt;
&lt;p&gt;Terceiro texto &lt;/p&gt; &lt;br&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Imagem - &lt;img&gt;</summary>
Tag para colocar imagem no seu código, esse tag não necessita de fechamento. 
<pre>
	<code>	
&lt;h1&gt;Seu Titulo&lt;/h1&gt;
&lt;img src="endereço-sua-foto.jpg" alt="descrição para a foto" &gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Vídeo  - &lt;video&gt;</summary>
É utilizado para incorporar conteúdo de vídeo em um documento HTML. Suporta os sequintes atributos: autoplay, controls, loop, poster, preload, src
<pre>
	<code>	
&lt;h1&gt;Meu vídeo&lt;/h1&gt;
&lt;video width="320" height="240" poster="imagemprevia.jpg" controls autoplay&gt;
&lt;source src="endereço-seu-video.mp4" type="video/mp4"&gt;
&lt;source src="endereço-seu-video.ogg" type="video/ogg"&gt;
Seu navegador não suporta a tag de vídeo.
&lt;/video&gt;
	</code>
</pre>
</details>


<details> <br>
<summary>Áudio  - &lt;audio&gt;</summary>
É utilizado para incorporar conteúdo de vídeo em um documento HTML. Suporta os sequintes atributos: autoplay, controls, loop, muted, preload, src
<pre>
	<code>	
&lt;h1&gt;Meu Áudio&lt;/h1&gt;
&lt;audio controls autoplay&gt;
&lt;source src="endereço-seu-audio.mp3" type="audio/mp3"&gt;
&lt;source src="endereço-seu-audio.ogg" type="audio/ogg"&gt;
Seu navegador não suporta a tag de audio.
&lt;/video&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Incorporando outra página HTML na página atual - &lt;iframe&gt;</summary>
A <code>&lt;iframe&gt;</code> tag especifica um quadro embutido. Um quadro embutido é usado para incorporar outro documento (site) no documento HTML atual.
<pre>
	<code>	
&lt;h1&gt;Exemplo de iframe adicionando o site da Globo:&lt;/h1&gt;
&lt;iframe src="https://www.globo.com/" title="Globo"&gt;
&lt;/iframe &gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Lista Ordenada - &lt;ol&gt;</summary>
Representa uma lista de itens ordenados, ordenadas que podem ser numéricas ou alfabéticas.
<pre>
	<code>	
&lt;ol&gt;
	&lt;li&gt;primeiro item&lt;/li &gt;
	&lt;li&gt;segundo item&lt;/li &gt;
	&lt;li&gt;terceiro item&lt;/li &gt;
&lt;/ol &gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Lista Não Ordenada - &lt;ul&gt;</summary>
Representa uma lista de itens não ordenados.
<pre>
	<code>	
&lt;ul&gt;
	&lt;li&gt;Café&lt;/li &gt;
	&lt;li&gt;Chá&lt;/li &gt;
	&lt;li&gt;Leite&lt;/li &gt;
&lt;/ul &gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Campo para dados em Formulários - &lt;Input type="text"&gt;</summary>
Campo onde você pode inserir dados. 
<pre>
	<code>	
	&lt;input  type="text"&gt;
	&lt;input  type="checkbox"&gt;
	&lt;input  type="date"&gt;
	etc...
	</code>
</pre>
Lista dos Tipos:

- text
- number
- url
- email
- password
- tel
- checkbox
- radio
- time
- date
- datetime-local
- month
- week
- color
- file
- hidden
- image
- range
- reset
- search
- submit
</details>

<details> <br>
<summary>Área de texto - &lt;textarea&gt;</summary>
Geralmente é usado em um formulário para coletar entradas do usuário, como comentários ou revisões.
<pre>
	<code>	
&lt;form&gt;
	&lt;p&gt;&lt;label&gt;Porque eu quero ser um Programador(a):&lt;/label&gt;&lt;/p&gt;
	&lt;textarea rows="4" cols="50"&gt;Sua resposta aqui... &lt;/textarea&gt;
	&lt;br&gt;
	&lt;input  type="submit" value="Enviar"&gt;
&lt;/form&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Lista suspensa Select - &lt;select&gt;&lt;/select&gt;</summary>
Essa tag é usada para criar uma lista suspensa, muito usado em formulários.
<pre>
	<code>	
&lt;form&gt;
	&lt;label for="cars"&gt;Escolha um carro:&lt;/label&gt;
	&lt;select&gt;
		&lt;option value="volvo"&gt;Volvo&lt;/select&gt;
		&lt;option value="audi"&gt;Audi&lt;/select&gt;
		&lt;option value="mecedes"&gt;Mercedes&lt;/select&gt;
		&lt;option value="porsche"&gt;Porsche&lt;/select&gt;
	&lt;/select&gt;
&lt;/form&gt;
	</code>
</pre>
</details>

<details> <br>
<summary>Hiperlink - &lt;a&gt;&lt;/a&gt;</summary>
Define um hiperlink, que é usado para vincular de uma página a outra. O atributo mais importante do <code>&lt;a&gt;</code> elemento é o href atributo, que indica o destino do link.<br>
Atributos: target='_blank' >> abre em uma nova página
<pre>
	<code>	
&lt;a href="https://www.google.com"&gt;
	Clique aqui e vá para o Google
&lt;/a&gt;
	</code>
</pre>
</details>
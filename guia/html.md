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


<details>
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

<details>
<summary>Paragrafo - &lt;p&gt; &lt;/p&gt; </summary>

```html
<p>Meu parágrafo, texto que você desejar...</p>
```
</details>

<details>
<summary>Negrito - &lt;b&gt; &lt;/b&gt; </summary>

```html
<p> Seu texto em <b>negrito</b> ou <strong>Negrito<strong> </p>
```

</details>


<details>
<summary>Itálico  - &lt;i&gt; &lt;/i&gt; </summary>

```
<p> Esse é o meu <i>texto em itálico</i> </p>
```

</details>
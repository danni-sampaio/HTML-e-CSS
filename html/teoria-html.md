# HTML5 - Guia Completo de Estudos

## O que é HTML?

HTML (HyperText Markup Language) é a linguagem de marcação utilizada para criar a estrutura de páginas da web.

Ela organiza textos, imagens, links, vídeos, formulários e diversos outros elementos que são exibidos pelos navegadores.

> HTML não é uma linguagem de programação. É uma linguagem de marcação.

---

# Como funciona o HTML?

O HTML utiliza **tags** para identificar cada elemento da página.

Exemplo:

```html
<h1>Olá, Mundo!</h1>
<p>Este é um parágrafo.</p>
```

Normalmente, uma tag possui abertura e fechamento.

Exemplo:

```html
<p>Texto</p>
```

---

# Estrutura básica

Toda página HTML possui uma estrutura semelhante à seguinte:

```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>

<body>

</body>

</html>
```

## Explicação

### <!DOCTYPE html>

Informa ao navegador que o documento utiliza HTML5.

### `<html>`

Elemento raiz da página.

### `<head>`

Contém informações sobre o documento, como título, favicon e metadados.

### `<body>`

Contém todo o conteúdo visível da página.

---

# Hierarquia de títulos

O HTML possui seis níveis de títulos.

```html
<h1>Título Principal</h1>
<h2>Título</h2>
<h3>Título</h3>
<h4>Título</h4>
<h5>Título</h5>
<h6>Título</h6>
```

Boas práticas:

- Utilize apenas um `<h1>` por página.
- Organize o conteúdo utilizando a hierarquia correta.

---

# Parágrafos

```html
<p>Este é um parágrafo.</p>
```

---

# Quebra de linha

```html
<br>
```

---

# Linha horizontal

```html
<hr>
```

---

# Comentários

```html
<!-- Comentário -->
```

---

# Atributos

Os atributos adicionam informações às tags.

Exemplo:

```html
<a href="https://github.com">GitHub</a>
```

Atributos comuns:

- href
- src
- alt
- id
- class
- title

---

# Links

```html
<a href="https://github.com">
GitHub
</a>
```

Abrir em outra aba:

```html
<a href="https://github.com" target="_blank">
GitHub
</a>
```

---

# Imagens

```html
<img
src="foto.jpg"
alt="Descrição da imagem">
```

Atributos importantes:

- src
- alt
- width
- height

---

# Favicon

```html
<link
rel="shortcut icon"
href="favicon.ico"
type="image/x-icon">
```

---

# Formatação de texto

Negrito

```html
<strong>Texto</strong>
```

Itálico

```html
<em>Texto</em>
```

Marcado

```html
<mark>Texto</mark>
```

Texto pequeno

```html
<small>Texto</small>
```

Texto excluído

```html
<del>Texto</del>
```

Texto inserido

```html
<ins>Texto</ins>
```

Sobrescrito

```html
x<sup>2</sup>
```

Subscrito

```html
H<sub>2</sub>O
```

---

# Símbolos

Exemplos:

```html
&copy;
&reg;
&euro;
&trade;
```

---

# Emojis

```html
&#x1F680;
```

Resultado:

🚀

---

# Listas

## Não ordenada

```html
<ul>
<li>HTML</li>
<li>CSS</li>
</ul>
```

## Ordenada

```html
<ol>
<li>HTML</li>
<li>CSS</li>
</ol>
```

## Lista de definição

```html
<dl>
<dt>HTML</dt>
<dd>Linguagem de marcação.</dd>
</dl>
```

---

# O que ainda vou aprender

- Tabelas
- Áudio
- Vídeo
- Formulários
- Iframes
- Semântica
- Responsividade
- Acessibilidade
- SEO
- Boas práticas

---

# Resumo

HTML é a linguagem responsável por estruturar páginas da web. Utilizando tags, é possível organizar conteúdos, criar links, inserir imagens, listas, formulários e diversos outros elementos que compõem um site moderno.
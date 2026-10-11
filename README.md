# Desenvolvimento Front-End para Web

Repositório com os exercícios desenvolvidos durante as aulas de sábado do curso de Desenvolvimento Front-End para Web. Cada pasta representa uma aula e mostra a evolução do aprendizado: do primeiro "Olá Mundo" em HTML até uma calculadora funcional com JavaScript.

## Tecnologias utilizadas

- HTML5
- CSS3 (CSS interno, externo, Grid e Flexbox)
- JavaScript (manipulação do DOM e eventos)

## Estrutura do repositório

```
aula_de_sabado/
├── Aula_1/   Primeiro contato com HTML
├── Aula_2/   Estrutura e elementos básicos do HTML
├── Aula_3/   Imagens, tabelas, CSS e JavaScript básicos
├── Aula_4/   Links, imagens e divs com CSS
├── Aula_5/   Navegação entre páginas, semântica, formulários e vídeo
├── Aula_6/   CSS externo e classes
├── Aula_7/   Classes, IDs e layout de portal de notícias
├── Aula_8/   Layouts com CSS Grid e Flexbox
└── Aula_9/   JavaScript: alertas e calculadora
```

---

## Aula 1 — Olá Mundo

Primeiro contato com o desenvolvimento web. A pasta contém arquivos simples (`.html` e `.txt`) com a mensagem **"Olá Mundo, Sejam Bem Vindos!"**, usados para entender como um arquivo HTML é criado e aberto no navegador.

**Conceitos:** criação de arquivos, extensão `.html`, exibição de texto no navegador.

---

## Aula 2 — Estrutura básica e elementos do HTML

Introdução à estrutura de uma página HTML5 (`<!DOCTYPE>`, `<html>`, `<head>`, `<body>`) e aos principais elementos de texto. Os exercícios são:

- **index.html** — a "Minha primeira página", com título e parágrafos.
- **Anatomia_tags.html** — explica o que são tags, com parágrafos e destaque de texto em negrito (`<strong>`) e itálico (`<em>`).
- **elementos_titulos.html** — demonstra os seis níveis de títulos, de `<h1>` a `<h6>`.
- **lista.html** — listas ordenadas (`<ol>`) e não ordenadas (`<ul>`).
- **stly.css** e **script.js** — arquivos criados vazios, preparados para as próximas aulas.

**Conceitos:** estrutura do documento, tags, títulos, parágrafos, listas.

---

## Aula 3 — Imagens, tabelas, CSS e JavaScript

Primeiros passos com mídia, dados tabulares e a combinação das três tecnologias da web.

- **exemplo_aula01.html** — página com títulos de tamanhos diferentes e a imagem do mascote Tux (`<img>` com `alt` e `width`).
- **exemplo_aula02.html** — apresenta o trio HTML + CSS + JavaScript: estilo aplicado ao `body` (cor e tamanho de fonte) e uma mensagem enviada ao console com `console.log`.
- **exemplo_aula03.html** — imagem com legenda usando `<figure>` e `<figcaption>`, centralizada com CSS inline.
- **tabelas.html** — tabela com `<thead>`, `<tbody>`, `<th>` e `<td>`, contendo nome, idade e cidade.

**Conceitos:** `<img>`, `<figure>`, tabelas, CSS interno, CSS inline, `<script>`.

---

## Aula 4 — Links, imagens e divisões (div)

- **exemplo_aula01.html** — link externo (`target="_blank"` com `rel="noopener noreferrer"`) e imagem do projeto Minecraft.
- **exemplo_aula02.html** — uso de `<div>` com `id` para dividir a página em seções, separadas por `<hr>`.
- **exemplo_aula03_div_e_css.html** — as mesmas divs estilizadas por `id`: cores de fundo, bordas superiores coloridas, espaçamento (`padding` e `margin`), texto centralizado e bordas arredondadas.

**Conceitos:** hiperlinks, `<div>`, seletores de `id`, modelo de caixa, `border-radius`.

---

## Aula 5 — Projeto de links, semântica e formulários

Projeto com múltiplas páginas interligadas e exercícios de HTML semântico.

**`projetos-links/`** — site simples com três páginas:

- **index.html** — página principal com links para a página do gato, a do cavalo e um link externo para o Google.
- **cavalo.html** — página com foto de cavalo e links para outras páginas.
- **paginas/gato.html** — página dentro de subpasta, com foto de gato e links de volta usando caminhos relativos (`../`).

**`html_forms/`**:

- **exemplo-aula01-paginasemantica.html** — estrutura semântica com `<article>`, `<header>`, `<section>`, `<footer>` e `<time>`.
- **exemplo-aula02-form.html** — formulário de cadastro de estudante com campos de nome, e-mail e senha (todos obrigatórios), além de botões de enviar e limpar.
- **exemplo-aula03-videos.html** — vídeo incorporado com `<video>` e controles do player.

**Conceitos:** caminhos relativos, organização em pastas, tags semânticas, `<form>`, `<label>`, `<input>`, validação com `required`, `<video>`.

---

## Aula 6 — CSS externo e classes

- **exemplo-de-aula01-cssexterno.html** + **estilo.css** — página "Minha primeira página com estilo", que usa uma folha de estilos externa (`<link rel="stylesheet">`) para definir fontes, cores, bordas e a seção principal, com uma imagem de paisagem como plano de fundo (`background-size: cover`).
- **exemplo-de-aula02.html** — uso de classes CSS (`.titulo`, `.caixa01`, `.caixa02`, `.destaque01`, `.destaque02`) para estilizar elementos diferentes de formas diferentes na mesma página.

**Conceitos:** CSS externo, seletores de classe, imagem de fundo, separação entre estrutura (HTML) e estilo (CSS).

---

## Aula 7 — Classes, IDs e Portal da Turma

- **Exemplo-de-aula-1-classeid.html** — compara o uso de **classe** (reutilizável) e **id** (único) em `div` e `span`, com caixas coloridas, bordas arredondadas e margens personalizadas.
- **Exemplo-de-aula02-noticia.html** — página "Portal da turma" com cabeçalho, menu de navegação horizontal (`<nav>` com Flexbox e efeito `:hover`) e um artigo de notícia sobre o início do projeto de página pessoal dos alunos.

**Conceitos:** diferença entre classe e id, `<span>`, `<nav>`, `display: flex`, pseudoclasse `:hover`, layout de portal de notícias.

---

## Aula 8 — Layouts com Grid e Flexbox

- **exemplo-de-aula01-gridt.html** + **style01.css** — "Portal Front-End" com layout em **CSS Grid**: cabeçalho, barra lateral de navegação, conteúdo principal e rodapé, organizados com `grid-template-areas`. Os conteúdos (HTML, CSS, Formulários e Tabelas) aparecem em cards responsivos (`repeat(auto-fit, minmax(300px, 1fr))`), em um tema escuro com tons de roxo.
- **exemplo-de-aula02-flext.html** — "Portal de Tecnologia", com menu de navegação e seções sobre Início, HTML, CSS e Contato, preparado para o estudo de **Flexbox**.

**Conceitos:** CSS Grid, áreas de grid, layout responsivo, cards, `box-sizing`, Flexbox.

---

## Aula 9 — JavaScript

- **exemplo-de-aula01-alerta.html** — mostra onde o JavaScript pode ser incorporado na página: um `alert()` no cabeçalho e um `document.write()` no corpo, que insere um parágrafo estilizado.
- **exemplo-de-aula02-calc.html** + **estilo.css** + **script.js** — **Calculadora de operações**. O usuário informa dois valores, escolhe a operação (soma, subtração, multiplicação ou divisão) e clica em "Calcular" para ver o resultado. O script valida se os dois valores foram preenchidos e se uma operação foi escolhida, exibindo alertas caso contrário. A interface tem formulário centralizado, borda dupla e tema verde.

**Conceitos:** `alert`, `document.write`, `getElementById`, `querySelector`, `addEventListener`, `switch`, validação de formulário, arquivo JS externo com `defer`.

---

## Como executar

Não há instalação nem dependências. Basta baixar o repositório e abrir o arquivo `.html` desejado no navegador (ou usar a extensão Live Server do VS Code).

## Autor

Robson de Araújo Andrade — Guarulhos, SP.

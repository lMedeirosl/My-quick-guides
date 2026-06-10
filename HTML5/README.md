# HTML5 My Guide

# Estrutura do Documento

```bash
<html>      → Raiz do documento
<head>      → Metadados (não visível)
<body>      → Conteúdo visível
<title>     → Título da aba
<meta>      → Metadados (charset, SEO, viewport)
<link>      → Links externos (CSS, ícones)
<style>     → CSS interno
<script>    → JavaScript
<base>      → URL base para links relativos
```

---

# Seções e Layout (Semântica HTML5)

```bash
<header>    → Cabeçalho de seção ou página
<nav>       → Navegação
<main>      → Conteúdo principal (único)
<section>   → Seção temática
<article>   → Conteúdo independente
<aside>     → Conteúdo lateral
<footer>    → Rodapé
```

---

# Texto e Conteúdo

```bash
<h1> a <h6> → Títulos
<p>         → Parágrafo
<br>        → Quebra de linha
<hr>        → Linha horizontal
<pre>       → Texto pré-formatado
<blockquote>→ Citação em bloco
<q>         → Citação curta
<address>   → Informações de contato
```

---

# Formatação de Texto

```bash
<strong> → Ênfase forte (semântica)
<em>     → Ênfase
<b>      → Negrito (visual)
<i>      → Itálico (visual)
<u>      → Sublinhado
<mark>   → Texto destacado
<small>  → Texto menor
<del>    → Texto deletado
<ins>    → Texto inserido
<sub>    → Subscrito
<sup>    → Sobrescrito
```

---

# Listas

```bash
<ul> → Lista não ordenada
<ol> → Lista ordenada
<li> → Item da lista
<dl> → Lista de definição
<dt> → Termo
<dd> → Definição
```

---

# Links e Navegação

```bash
<a>    → Link
```

---

# Imagens e Mídia

```bash
<img>     → Imagem
<picture> → Imagem responsiva
<source>  → Fonte de mídia
<figure>  → Conteúdo ilustrativo
<figcaption> → Legenda
```

---

# Áudio e Vídeo (HTML5)

```bash
<audio>  → Áudio
<video>  → Vídeo
<track>  → Legendas
```

---

# Tabelas

```bash
<table> → Tabela
<thead> → Cabeçalho
<tbody> → Corpo
<tfoot> → Rodapé
<tr>    → Linha
<th>    → Cabeçalho de célula
<td>    → Célula
<caption> → Título da tabela
<colgroup> → Grupo de colunas
<col> → Coluna
```

---

# Formulários

```bash
<form>     → Formulário
<input>    → Campo de entrada
<textarea> → Texto longo
<button>   → Botão
<select>   → Seleção
<option>   → Opção
<optgroup> → Grupo de opções
<label>    → Rótulo
<fieldset> → Grupo de campos
<legend>   → Título do grupo
<datalist> → Sugestões
<output>   → Resultado
```

---

# Elementos Interativos

```bash
<details> → Conteúdo expansível
<summary> → Título do details
<dialog>  → Modal
```

---

# Scripts e Templates

```bash
<canvas>  → Desenho via JS
<svg>     → Gráficos vetoriais
<template>→ Conteúdo reutilizável
<slot>    → Web Components
```

---

# Conteúdo Embutido

```bash
<iframe> → Conteúdo externo
<embed>  → Conteúdo embutido
<object> → Objeto externo
<param>  → Parâmetro de objeto
```

---

# Metadados e Outros

```bash
<noscript> → Conteúdo sem JS
<progress> → Barra de progresso
<meter>    → Medidor
<time>     → Data/hora semântica
<bdi>      → Isolamento de direção
<bdo>      → Direção do texto
<wbr>      → Quebra de palavra
```

---

# Tags OBSOLETAS (NÃO usar no HTML5)

```bash
<font>, <center>, <marquee>, <big>, <strike>, <frameset>, <frame>
```

## Tags HTML5 “esquecidas” (mas importantes)

### Formulários (além das óbvias)

```bash
<fieldset>  → Agrupa campos relacionados
<legend>    → Título do fieldset
<datalist>  → Lista de sugestões para inputs
<output>    → Exibe resultado de um cálculo
```

Exemplo:

```bash
<input list="navegadores">
<datalist id="navegadores">
  <option value="Chrome">
  <option value="Firefox">
</datalist>
```

---

### Acessibilidade e Semântica Avançada

```bash
<time> → Data/hora semântica
<mark> → Destaque contextual
<abbr> → Abreviação com significado
<cite> → Referência de obra
```

```bash
<time datetime="2026-01-27">27 de janeiro</time>
<abbr title="HyperText Markup Language">HTML</abbr>
```

---

### Direção e Idiomas (quase ninguém lembra)

```bash
<bdi> → Isola direção de texto (RTL/LTR)
<bdo> → Força direção do texto
```

```bash
<bdo dir="rtl">Texto invertido</bdo>
```

---

### Layout invisível / comportamento de texto

```bash
<wbr> → Sugere quebra de palavra
```

```bash
supercalifragilistic<wbr>expialidocious
```

---

### Elementos Interativos pouco usados

```bash
<details> → Conteúdo expansível
<summary> → Título do details
<dialog>  → Modal nativo
```

```bash
<details>
  <summary>Ver mais</summary>
  Conteúdo escondido
</details>
```

---

### Medição e Status

```bash
<meter>    → Medida com intervalo conhecido
<progress> → Progresso de tarefa
```

```bash
<progress value="70" max="100"></progress>
<meter value="0.6"></meter>
```

---

### Web Components / Avançado

```bash
<template> → Conteúdo não renderizado
<slot>     → Slot para componentes
```


---

### Conteúdo Embutido “secundário”

```bash
<param> → Parâmetro para <object>
```

---

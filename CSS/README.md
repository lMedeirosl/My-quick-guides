# CSS

## Seletores

```css
* { margin: 0; }              /* todos os elementos */
p { color: red; }             /* tag */
.texto { font-size: 16px; }   /* classe */
#titulo { font-weight: bold; }/* id */

div p { color: blue; }        /* descendente */
div > p { color: green; }     /* filho direto */
div + p { color: orange; }    /* irmão imediato */
div ~ p { color: purple; }    /* irmãos gerais */

input[type="text"] { border: 1px solid black; }

a:hover { color: red; }
input:focus { outline: none; }

p::before { content: "→ "; }
p::after { content: " ←"; }

li:nth-child(2) { color: red; }
div:not(.ativo) { opacity: 0.5; }
```

---

## Box Model

```css
width: 200px;
height: 100px;

min-width: 150px;
max-width: 500px;
min-height: 80px;
max-height: 300px;

margin: 10px;
margin-top: 10px;
margin-right: 20px;
margin-bottom: 10px;
margin-left: 20px;

padding: 15px;
padding-top: 10px;

border: 2px solid black;
border-width: 2px;
border-style: dashed;
border-color: red;
border-radius: 8px;

box-sizing: border-box;
```

---

## Display & Position

```css
display: block;
display: inline;
display: inline-block;
display: flex;
display: grid;
display: none;

position: static;
position: relative;
position: absolute;
position: fixed;
position: sticky;

top: 10px;
right: 0;
bottom: 20px;
left: 5px;

z-index: 10;
```

---

## Flexbox

```css
display: flex;

flex-direction: row;
flex-direction: column;

flex-wrap: wrap;
flex-flow: row wrap;

justify-content: center;
align-items: center;
align-content: space-between;

gap: 10px;

flex: 1;
flex-grow: 2;
flex-shrink: 1;
flex-basis: 200px;

order: 2;
align-self: flex-end;
```

---

## Grid

```css
display: grid;

grid-template-columns: 1fr 2fr;
grid-template-rows: auto 100px;
grid-template-areas:
  "header header"
  "menu content";

grid-column: 1 / 3;
grid-row: 2 / 3;
grid-area: content;

justify-items: center;
align-items: center;
place-items: center;

justify-content: space-between;
align-content: center;
place-content: center;

gap: 20px;
```

---

## Texto & Fontes

```css
color: #333;

font-family: Arial, sans-serif;
font-size: 16px;
font-weight: 700;
font-style: italic;
font-variant: small-caps;

line-height: 1.5;
letter-spacing: 2px;
word-spacing: 5px;

text-align: center;
text-transform: uppercase;
text-decoration: underline;
text-shadow: 2px 2px 5px black;

white-space: nowrap;
overflow-wrap: break-word;
```

---

## Fundo & Cores

```css
background: red;
background-color: #f0f0f0;
background-image: url("img.png");
background-repeat: no-repeat;
background-size: cover;
background-position: center;
background-attachment: fixed;

opacity: 0.7;
```

---

## Imagens & Objetos

```css
object-fit: cover;
object-position: center;
image-rendering: crisp-edges;
```

---

## Overflow & Scroll

```css
overflow: hidden;
overflow-x: scroll;
overflow-y: auto;

scroll-behavior: smooth;
```

---

## Transições

```css
transition: all 0.3s ease;
transition-property: background-color;
transition-duration: 0.5s;
transition-timing-function: ease-in-out;
transition-delay: 0.2s;
```

---

## Animações

```css
animation: fade 2s infinite;

animation-name: fade;
animation-duration: 2s;
animation-iteration-count: infinite;
animation-direction: alternate;
animation-fill-mode: forwards;
animation-timing-function: ease-in-out;

@keyframes fade {
  from { opacity: 0; }
  to { opacity: 1; }
}
```

---

## Transformações

```css
transform: rotate(45deg);
transform-origin: center;

transform: translateX(50px);
transform: scale(1.2);
transform: skew(10deg);
```

---

## Efeitos Visuais

```css
box-shadow: 0 4px 10px rgba(0,0,0,0.3);
filter: blur(5px);
backdrop-filter: blur(10px);
```

---

## Listas & Tabelas

```css
list-style: none;
list-style-type: square;
list-style-position: inside;
list-style-image: url("icon.png");

border-collapse: collapse;
border-spacing: 5px;
caption-side: bottom;
```

---

## Cursor & Interação

```css
cursor: pointer;
pointer-events: none;
user-select: none;
```

---

## Responsividade

```css
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}

@supports (display: grid) {
  div { display: grid; }
}
```

---

## Variáveis CSS

```css
:root {
  --cor-primaria: #7b5cf0;
}

button {
  background-color: var(--cor-primaria);
}
```

---

## At-Rules

```css
@import url("style.css");

@font-face {
  font-family: MinhaFonte;
  src: url("fonte.woff2");
}

@layer base {
  body { margin: 0; }
}
```

---


Só dizer o próximo passo.

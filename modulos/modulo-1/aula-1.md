# 📘 Módulo 1 – Introdução ao CSS

## Aula 1.1 – O que é CSS?

**CSS (Cascading Style Sheets)** é a linguagem responsável pela camada de apresentação visual dos sites. Enquanto o HTML estrutura o conteúdo, o CSS define a aparência – cores, tamanhos, alinhamentos, posicionamentos, fontes e muito mais.

* "Cascata" significa que estilos podem ser sobrepostos conforme regras de prioridade.
* As versões mais utilizadas são **CSS2** e **CSS3**.

---

## Aula 1.2 – Modos de aplicação do CSS

### 1. CSS Inline (evitar)

Estilo aplicado diretamente na tag HTML:

```html
<p style="text-align: justify">Texto justificado</p>
```

### 2. CSS Interno (não recomendado para grandes projetos)

```html
<head>
  <style>
    p {
      text-align: justify;
    }
  </style>
</head>
```

### 3. CSS Externo (ideal)

```html
<head>
  <link rel="stylesheet" href="estilo.css">
</head>
```

**Vantagem:** Ao editar o arquivo `.css`, todas as páginas que o importam são atualizadas.

---

## Aula 1.3 – Sintaxe do CSS

```css
seletor {
  propriedade1: valor1;
  propriedade2: valor2;
  /* Comentário */
}
```

### Exemplo:

```css
p {
  text-align: justify;
  color: red;
  font-size: 16px;
}
```

### Comentários:

```css
/* Comentário de uma linha */
/*
   Comentário
   de várias linhas
*/
```

---

## Aula 1.4 – Seletores básicos

### 1. Seletor por TAG

Aplica o estilo a todas as tags especificadas:

```css
h1, h2, h3 {
  font-size: 20px;
}
```

### 2. Seletor por CLASSE

Define estilos reutilizáveis por várias tags:

```css
.negrito {
  font-weight: bold;
}
```

Uso no HTML:

```html
<p class="negrito">Texto em negrito</p>
```

### 3. Seletor por ID

Estilo exclusivo para um elemento:

```css
#frmLogin {
  background-color: #00f;
  margin-top: 16px;
}
```

Uso no HTML:

```html
<form id="frmLogin">...</form>
```

---

## Aula 1.5 – Introdução ao Box Model

Todo elemento HTML é tratado como uma "caixa" com 4 áreas:

* **Content** (conteúdo)
* **Padding** (espaço interno)
* **Border** (borda)
* **Margin** (espaço externo)

### Exemplo CSS:

```css
footer {
  background-color: white;
  border: solid 2px;
  margin: 100px 100px 100px 100px;
  padding: 30px 10px 0 250px;
}
```

---

## 🧪 Atividade Prática

* Reproduza a figura do Box Model com HTML e CSS.
* Utilize a cor `#98bf21` como fundo de um `div` e experimente aplicar `margin`, `padding`, `border` e `height`.

---

## 🔗 Referências

* [W3C Brasil – CSS2](http://www.w3c.br/divulgacao/guiasreferencia/css2/)
* [W3Schools – CSS Reference](https://www.w3schools.com/cssref/default.asp)

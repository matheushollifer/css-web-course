# Exercício: Layout com Flexbox

## Objetivo

Criar um layout responsivo utilizando Flexbox com três seções principais: cabeçalho, conteúdo e rodapé.

---

## Instruções

1. Crie um arquivo `index.html` e adicione a seguinte estrutura:

```html
<body>
  <header class="cabecalho">Cabeçalho</header>
  <main class="principal">
    <section class="esquerda">Menu</section>
    <section class="conteudo">Conteúdo</section>
    <section class="direita">Extras</section>
  </main>
  <footer class="rodape">Rodapé</footer>
</body>
```

2. Crie um arquivo `style.css` e importe no HTML com:

```html
<link rel="stylesheet" href="style.css">
```

3. No CSS, utilize Flexbox para:

* Tornar o `main.principal` um contêiner flexível
* Alinhar os três blocos (`esquerda`, `conteudo`, `direita`) em linha
* Definir que o conteúdo ocupe mais espaço (ex: `flex: 2`) e os outros menos (ex: `flex: 1`)

Exemplo:

```css
.principal {
  display: flex;
  height: 300px;
}

.esquerda, .conteudo, .direita {
  padding: 10px;
  color: white;
  font-weight: bold;
  text-align: center;
}

.esquerda { background: #e74c3c; flex: 1; }
.conteudo { background: #3498db; flex: 2; }
.direita  { background: #2ecc71; flex: 1; }
```

---

## Desafio extra (opcional)

* Altere a direção dos blocos para `column` em telas pequenas (mobile)
* Utilize `media queries` para tornar o layout responsivo

---

## Entrega

* Envie os arquivos `index.html` e `style.css` no formato `.zip` ou em um repositório do GitHub.

---

Dica: use o site [flexboxfroggy.com](https://flexboxfroggy.com) para revisar os conceitos!

# 🧪 Exercício – Compreendendo o Box Model com CSS

## Objetivo

Reproduzir visualmente o modelo de caixa (Box Model) utilizando HTML e CSS. Este exercício permite visualizar de forma clara as camadas **Margin**, **Border**, **Padding** e **Content**.

---

## 💡 Instruções

Você deverá criar uma estrutura de `<div>`s aninhadas, onde cada nível representa uma camada do Box Model. O CSS será utilizado para aplicar margens, bordas, preenchimento (padding) e cor de fundo.

---

## 🧱 Estrutura Esperada

Cada `div` deve ter:

* Uma borda visível (dashed ou solid);
* Um `padding` para afastar o conteúdo da borda;
* Uma `margin` para afastar a caixa externa da interna;
* Um `background-color` contrastante para destacar a camada.

---

## 📂 Arquivos fornecidos

* `index.html` – estrutura base do exercício.
* `style.css` – regras CSS aplicadas a cada camada.

### 🔗 Exemplo de estrutura HTML:

```html
<div class="div_d">Margin
  <div class="div_c">Border
    <div class="div_b">Padding
      <div class="div_a">Content</div>
    </div>
  </div>
</div>
```

### 🎨 Trecho de style.css:

```css
.div_d {
  margin: 100px 30%;
  padding: 25px;
  background-color: white;
  border: dashed;
}
.div_c {
  margin: 5px;
  padding: 25px;
  background-color: #98bf21;
  border: solid;
}
/* ... continue para div_b e div_a */
```

---

## 📌 Atividade Proposta

1. Crie os arquivos `index.html` e `style.css`.
2. Replique a estrutura de camadas usando as classes `.div_d`, `.div_c`, `.div_b` e `.div_a`.
3. Teste no navegador e observe as separações entre cada camada.
4. Experimente alterar valores de `padding`, `margin` e `border` para entender seu efeito visual.

---

## ✅ Entregável

* Submeta seu exercício via GitHub, Google Drive ou outro meio indicado pelo professor.
* A visualização correta das camadas e organização do código serão avaliadas.

---

> 💬 Dica: Use o **DevTools (F12)** do navegador para inspecionar cada `div` e ver as dimensões e propriedades aplicadas.

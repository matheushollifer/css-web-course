**MÓDULO 2 – FLEXBOX (CSS3)**
Monitoria - Desenvolvimento de Páginas Web
Curso: Tecnologia em Sistemas para Internet
Campus: IFSudesteMG - Barbacena

---

### ✅ OBJETIVO

Compreender e aplicar o modelo de layout **Flexbox** do CSS para construir interfaces responsivas e organizadas com menos código e mais controle visual.

---

### 📁 ESTRUTURA HTML BASE

```html
<div class="elementos">
  <div class="item i1">1</div>
  <div class="item i2">2</div>
  <div class="item i3">3</div>
</div>
```

---

### 🎨 ESTILO CSS BASE

```css
.elementos {
  border: 2px solid black;
  height: 300px;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
}

.item {
  text-align: center;
  padding: 15px;
}

.i1 { background-color: red; }
.i2 { background-color: green; }
.i3 { background-color: blue; }
```

---

### 🔄 PROPRIEDADES FLEXBOX IMPORTANTES

* **display: flex;** → ativa o layout flexível no contêiner

* **flex-direction:** controla a direção dos itens

  * `row` (horizontal)
  * `row-reverse`
  * `column` (vertical)
  * `column-reverse`

* **justify-content:** alinha os itens no eixo principal

  * `flex-start` | `flex-end` | `center`
  * `space-between` | `space-around` | `space-evenly`

* **align-items:** alinha os itens no eixo cruzado

  * `flex-start` | `flex-end` | `center` | `stretch`

---

### 🎮 ATIVIDADE SUGERIDA

Acesse o jogo interativo **Flexbox Froggy** para praticar os conceitos aprendidos:

> [https://flexboxfroggy.com](https://flexboxfroggy.com)

---

### 👥 CONTATO

* **Monitor:** Matheus Ferreira
* **Professor:** Rafael Alencar


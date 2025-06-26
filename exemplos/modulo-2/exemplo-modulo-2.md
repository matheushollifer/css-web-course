# Exemplo prático com Flexbox

Este exemplo acompanha o Módulo 2 da monitoria de Desenvolvimento de Páginas Web.

## Estrutura HTML

```html
<div class="elementos">
  <div class="item i1">Item 1</div>
  <div class="item i2">Item 2</div>
  <div class="item i3">Item 3</div>
</div>
```

## Estilo CSS

```css
.elementos {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  height: 200px;
  border: 2px solid black;
  padding: 10px;
}

.item {
  flex: 1;
  margin: 5px;
  text-align: center;
  padding: 20px;
  font-weight: bold;
  color: white;
}

.i1 { background-color: crimson; }
.i2 { background-color: seagreen; }
.i3 { background-color: steelblue; }
```

## O que observar

* `display: flex;` transforma o contêiner `.elementos` em flexível
* `flex-direction: row;` alinha os itens na horizontal
* `justify-content: space-between;` distribui espaço entre os itens
* `align-items: center;` centraliza os itens verticalmente
* `flex: 1;` faz os itens crescerem igualmente

## Resultado esperado

Três caixas coloridas lado a lado, com espaço entre elas, alinhadas ao centro do contêiner.

---

Este exemplo é uma base para experimentar diferentes valores das propriedades Flexbox.

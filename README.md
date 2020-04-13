<p align="center">
  <img alt="aceleradevreact" src="./assets/logo.svg" width="700px"/>
</p>

<h3 align="center">
:computer: :running:  Acelera Dev React  :running: :computer:
</h3>

## :pushpin: BEM (Block Element Modifier)

A sigla BEM significa block, element e modifier, é uma metodologia que é aplicada na nomenclatura das `classes` CSS dos nossos elementos HTML.

<strong>Estrutura:</strong>

```
.card__item--active
 ^--^  ^--^  ^----^
 |     |     |
 |     |     +-> Modifier.
 |     |
 |     +-> Element
 |
 +-> Block
```

O `__` indica um `element` e o `--` indica um modifier. Tudo que vem antes do `__` é um block.

<strong>Exemplo da estrutura em HTML:</strong>

```
<div class="card">
  <ul class="card__list">
    <li class="card__item card__item--active">Figma</li>
    <li class="card__item">Invision</li>
    <li class="card__item">Adobe XD</li>
  </ul>
</div>
```

## :computer: Exemplo prático

Nesse projeto usamos o BEM (Block Element Modifier), a fim de padronizar a nomenclatura das classes desse card.

<p align="center">
  <img alt="project" src="./assets/screen.png" height="500px"/>
</p>

---

Made by :blue_heart: by [Larissa Araújo](https://github.com/arauj0)

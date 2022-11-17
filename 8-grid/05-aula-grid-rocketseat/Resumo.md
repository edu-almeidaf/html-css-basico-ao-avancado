# CSS GRID

## GRID

- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou colun a ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid

---

## PROPRIEDADES

Vamos separar em 2 grupos:
`container` e `items`

---

### CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap;
    - grid-row-gap;
    - -grid-collumn-gap;
- grid-template-areas.

... e mais 4 propriedades de **alinhamento**

---

## ITEM(s)

- grid-collumn;
    - grid-column-start;
    - grid-column-end;
- grid-row;
    - grid-row-start;
    - grid-row-end;
- grid-area.

... e mais 2 propriedades de **alinhamento**

---

# Grid: Alinhamento

Existem 6 propriedades para alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separrá-los em 2 grupos:
1. `justify` e `align`
   `content`   `items` e `self`

---

## Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

o **eixo x** é o posicionamento horizontal, da esquerda para a direita.

o **eixo y** é o posicionamento vertical, de cima para baixo.

---

## Content, Items e Self

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`, nós observamos nossas propriedades.

---

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço de fora do grid.
 
O uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que a área definida. (Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o tamanho da área do grid).

Podemos usar **7 valores**:

1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

---

### Items

`justify-items` e `align-items` vai permitir alinhar os ítens do nosso grid, em qualquer espaço disponível, na célula onde ele habitar.

Podemos usar **4 valores**:
1. start
2. end
3. center
4. stretch

---

### Self

`justify-self` e `align-self` vai nos permitir alinhar o ítem em si.

Faz a mesma coisa que o `justify-items` e `align-items`, porém aplicado diretamente no ítem de um grid.
## Aula 17

>**Posisionamento, Layouts e Realações**
>
>- Posicionamento de elementos em CSS
>- Layouts
>- Displays
>- Relacioanmento
>- Especificidade do seletor


### Posicionamento de elementos em CSS
O posicionamento de elementos em CSS pode ser feito de várias maneiras. Algumas das principais técnicas são:

  * Posicionamento estático (default): é a posição padrão dos elementos e não é necessário especificá-lo explicitamente. O elemento é posicionado conforme a 
  ordem do HTML e os valores de margem, preenchimento e tamanho definidos no CSS.

  * Posicionamento relativo: o elemento é posicionado em relação à sua posição original. É possível utilizar propriedades como top, bottom, left e right para 
  definir a posição em relação a essa posição original.

  * Posicionamento absoluto: o elemento é posicionado em relação ao elemento pai mais próximo que possua um posicionamento relativo ou absoluto. É possível utilizar 
  as mesmas propriedades do posicionamento relativo para definir a posição em relação a esse elemento pai.

  * Posicionamento fixo: o elemento é posicionado em relação à janela de visualização do navegador e permanece fixo enquanto a página é rolada. É possível utilizar 
  as mesmas propriedades do posicionamento relativo para definir a posição em relação à janela.

  * Posicionamento pegajoso (sticky): o elemento é posicionado em relação ao elemento pai mais próximo que possua um posicionamento relativo, absoluto ou fixo, mas 
  se comporta como um elemento fixo quando atinge uma determinada posição de rolagem. É possível utilizar as mesmas propriedades do posicionamento relativo para 
  definir a posição em relação a esse elemento pai.

Para definir o posicionamento de um elemento em CSS, é necessário utilizar a propriedade "position" e especificar um dos valores mencionados acima. Por exemplo:

```
/* Posicionamento relativo */
.elemento {
  position: relative;
  top: 20px;
  left: 50px;
}

/* Posicionamento absoluto */
.elemento {
  position: absolute;
  top: 0;
  left: 0;
}

/* Posicionamento fixo */
.elemento {
  position: fixed;
  top: 10px;
  right: 10px;
}

/* Posicionamento pegajoso */
.elemento {
  position: sticky;
  top: 0;
}
```

### Layouts com CSS

Com CSS, é possível criar diferentes layouts para as páginas web, desde layouts simples até layouts complexos e responsivos. Algumas das técnicas mais 
utilizadas para criar layouts com CSS são:

  * Modelo de caixa: é a técnica mais básica e consiste em definir o tamanho, a borda e o preenchimento de um elemento utilizando as propriedades "width", 
  "height", "border" e "padding".

  * Layout em grade: é possível criar layouts em grade utilizando propriedades como "display: grid" e "grid-template-columns", que permitem definir a 
  estrutura de colunas e linhas da grade.

  * Layout flexível: é possível criar layouts flexíveis utilizando propriedades como "display: flex" e "justify-content", que permitem distribuir os 
  elementos horizontalmente na página.

  * Posicionamento absoluto: como mencionado anteriormente, é possível utilizar o posicionamento absoluto para posicionar elementos em um layout.

  * Media queries: é possível utilizar as media queries para criar layouts responsivos, adaptando o layout às diferentes resoluções de tela. Por exemplo, 
  é possível definir diferentes estilos para dispositivos móveis e desktops.

Algumas outras técnicas avançadas que podem ser utilizadas para criar layouts complexos com CSS incluem o uso de variáveis CSS, animações e transições, 
e o uso de frameworks CSS como Bootstrap e Foundation.

Exemplo de layout em grade com CSS:

```
.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 20px;
}

.item {
  border: 1px solid black;
  padding: 10px;
}
```

Nesse exemplo, o elemento "container" é definido como uma grade de três colunas, cada uma com tamanho igual ("1fr"). A propriedade "grid-gap" 
define o espaçamento entre as colunas. Cada elemento "item" dentro do container será posicionado automaticamente na grade.


### Display em CSS

A propriedade "display" em CSS é utilizada para definir como um elemento HTML deve ser exibido na página. Existem vários valores possíveis para a 
propriedade "display", cada um com um comportamento específico:

  * block: o elemento é exibido como um bloco, ocupando toda a largura disponível na página. Um elemento "block" sempre inicia em uma nova linha e pode 
  ter margens, preenchimentos e bordas.

  * inline: o elemento é exibido inline, ao lado do elemento anterior. Um elemento "inline" não pode ter margens, preenchimentos ou bordas na parte 
  superior ou inferior e seu tamanho é definido pelo conteúdo.

  * inline-block: o elemento é exibido inline, mas pode ter margens, preenchimentos e bordas. É uma combinação das propriedades "inline" e "block".

  * flex: o elemento é exibido como um contêiner flexível, permitindo um layout flexível de seus filhos. É possível utilizar as propriedades "justify-content" e 
  "align-items" para alinhar e distribuir os elementos filhos.

  * grid: o elemento é exibido como um contêiner de grade, permitindo um layout em grade dos elementos filhos. É possível utilizar as propriedades 
  "grid-template-columns" e "grid-template-rows" para definir a estrutura da grade.

  * table: o elemento é exibido como uma tabela, permitindo o uso de elementos como "table-row" e "table-cell" para criar tabelas HTML.

  * none: o elemento não é exibido na página.

Existem outros valores possíveis para a propriedade "display", mas estes são os mais comuns. É importante notar que a propriedade "display" pode ser utilizada em conjunto com outras propriedades CSS para criar layouts complexos e responsivos. Por exemplo, é possível utilizar a propriedade "display: flex" para criar um layout flexível e utilizar as media queries para adaptar o layout a diferentes resoluções de tela.

### Relacionamento pai-filho em CSS
Em CSS, o relacionamento pai-filho é importante para definir a hierarquia dos elementos na página e aplicar estilos específicos a cada um deles.

O relacionamento pai-filho é estabelecido quando um elemento HTML é aninhado dentro de outro elemento HTML. Por exemplo:

```
<div class="pai">
  <p class="filho">Este é um parágrafo dentro da div pai.</p>
</div>
```

Nesse exemplo, a div "pai" é o elemento pai e o parágrafo "filho" é o elemento filho.

Para aplicar estilos específicos ao elemento filho, podemos utilizar o seletor filho, que consiste em especificar o seletor do elemento pai, 
seguido de um espaço e o seletor do elemento filho. Por exemplo:

```
.pai .filho {
  color: red;
}
```

Nesse exemplo, estamos aplicando a cor vermelha apenas ao elemento "filho" dentro da div "pai".

Também é possível utilizar o seletor filho direto (>) para aplicar estilos apenas ao elemento filho direto de um elemento pai, ignorando elementos 
aninhados mais profundamente. Por exemplo:

css
Copy code
.pai > .filho {
  color: blue;
}
Nesse exemplo, estamos aplicando a cor azul apenas ao elemento "filho" diretamente dentro da div "pai", ignorando elementos aninhados mais profundamente.

O relacionamento pai-filho é muito importante em CSS para aplicar estilos específicos a elementos em diferentes partes da página e também para criar 
estilos responsivos que se ajustam dinamicamente ao tamanho e à estrutura dos elementos pai e filho.

### O que e selector specificity em css

Em CSS, o selector specificity (especificidade do seletor) é uma forma de determinar qual estilo deve ser aplicado a um elemento quando há 
mais de um seletor que pode afetá-lo. A especificidade do seletor é calculada a partir de quatro componentes:

  * Número de IDs: cada ID presente no seletor adiciona um ponto à especificidade do seletor.
  * Número de classes, atributos e pseudoclasses: cada classe, atributo ou pseudoclasse presente no seletor adiciona um ponto à especificidade do seletor.
  * Número de elementos e pseudoelementos: cada elemento ou pseudoelemento presente no seletor adiciona um ponto à especificidade do seletor.
  * Importância: um seletor com a propriedade "important" adiciona uma especificidade alta ao estilo e prevalece sobre outros estilos para o mesmo elemento.

A especificidade do seletor é importante para determinar qual estilo deve ser aplicado quando há conflitos entre os estilos. Quando dois ou mais estilos são aplicados ao mesmo elemento, o estilo com a maior especificidade será aplicado. Se dois ou mais estilos têm a mesma especificidade, o estilo que aparece por último no arquivo CSS será aplicado.

Por exemplo, suponha que temos as seguintes regras CSS:

```
#id {
  color: red;
}

.classe {
  color: blue;
}

p {
  color: green;
}
```

Se um elemento HTML tiver o atributo "id" com o valor "id" e também tiver a classe "classe", a cor do texto será azul, pois a especificidade do seletor 
".classe" (uma classe) é maior do que a especificidade do seletor "#id" (um ID). Se o mesmo elemento não tivesse a classe "classe", mas fosse um elemento 
"p", a cor do texto seria verde, pois a especificidade do seletor "p" (um elemento) é menor do que a especificidade do seletor ".classe" (uma classe) e do 
seletor "#id" (um ID).

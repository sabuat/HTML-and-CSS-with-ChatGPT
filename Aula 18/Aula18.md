## Aula 18

> **Entendendo o Flexbox**
> 
>- Display Flex
>-Propriedades do Flex


### Display flex em CSS

"Display flex" é uma propriedade do CSS que permite que os elementos de um contêiner sejam organizados em uma linha ou coluna, e ajustados de acordo 
com o tamanho do contêiner. É muito útil para criar layouts responsivos e flexíveis. Para aplicar essa propriedade em um elemento, é necessário definir a
propriedade "display" como "flex". Por exemplo:

``` 
.container {
  display: flex;
}
``` 
Com essa propriedade, todos os elementos filhos do contêiner se tornam itens flexíveis e podem ser posicionados de várias maneiras usando outras 
propriedades do flexbox, como "flex-direction", "justify-content" e "align-items".

### Propriedades do Flex

As propriedades do Flexbox em CSS podem ser agrupadas em quatro categorias:

1. Propriedades no contêiner flex:
    
    * display
    * flex-direction
    * flex-wrap
    * justify-content
    * align-items
    * align-content

2. Propriedades em cada item flex:
    
    * order
    * flex-grow
    * flex-shrink
    * flex-basis
    * flex
    
3. Propriedades para alinhar os itens dentro do contêiner flex:
    
    * align-self
    
4. Propriedades para a exibição em linha e altura:
    
    * display
    * width
    * height
    * margin
    * padding
    
Algumas propriedades têm efeitos diferentes quando aplicadas a contêineres flex e itens flex. Por exemplo, "align-items" define a alinhamento 
vertical dos itens dentro do contêiner, enquanto "align-self" é usado para definir o alinhamento vertical de um item específico.

A maioria das propriedades do Flexbox são usadas para criar layouts flexíveis e responsivos, permitindo que os itens sejam ajustados automaticamente de 
acordo com o tamanho do contêiner pai. O Flexbox é muito útil para criar layouts de página, menus de navegação, galerias de imagens e muito mais.

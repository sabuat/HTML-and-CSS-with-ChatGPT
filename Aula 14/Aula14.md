## Aula 14

>  **Box Model em CSS**
>
>- Como funciona o Box Model no CSS
>- 

### Como funciona o Box Model no CSS

O Box Model é um conceito fundamental em CSS que descreve como cada elemento HTML é representado como um retângulo na página, com suas propriedades de largura, 
altura, margens, bordas e preenchimento (padding) definindo sua aparência visual.

O modelo de caixa tem quatro componentes principais:

  - **Conteúdo (content)**: é o espaço dentro do elemento onde o conteúdo real é exibido, como texto, imagens ou outros elementos.

  - **Preenchimento (padding)**: é a área entre o conteúdo e a borda do elemento. Ele adiciona espaço interno dentro do elemento e pode ser usado para criar espaçamento entre o conteúdo e a borda.

  - **Bordas (border)**: são linhas que cercam o elemento e o separam do conteúdo e do preenchimento. As bordas podem ser definidas com várias propriedades, como largura, estilo e cor.

  - **Margens (margin)**: é a área entre a borda do elemento e outros elementos da página. As margens adicionam espaço externo ao elemento e podem ser usadas para criar espaçamento entre elementos adjacentes.

Cada um desses componentes é considerado ao calcular a aparência visual do elemento na página. A largura total do elemento é a soma da largura do conteúdo, do 
preenchimento, da borda e da margem.

O Box Model é uma parte essencial do layout da página em CSS e permite que os desenvolvedores controlem a aparência visual dos elementos de maneira granular.

### Box sizing

O box-sizing é uma propriedade CSS que controla como o tamanho total de um elemento é calculado, incluindo o seu conteúdo, preenchimento (padding) e bordas (border). 
Existem dois valores possíveis para a propriedade box-sizing:

```
* content-box (padrão): O tamanho total do elemento é calculado adicionando a largura e a altura do conteúdo, do preenchimento e das bordas. 
Neste caso, qualquer valor de preenchimento ou borda adicionado ao elemento aumentará seu tamanho total.

* border-box: O tamanho total do elemento é calculado adicionando a largura e altura do conteúdo e do preenchimento, mas subtraindo a largura das bordas. 
Neste caso, o tamanho do elemento permanece o mesmo, independentemente de qualquer preenchimento ou borda adicionado.
```

O valor border-box é frequentemente usado pelos desenvolvedores web porque permite que eles controlem o tamanho total do elemento de maneira mais previsível e 
consistente. 

    Por exemplo, se você definir uma largura de 300 pixels para um elemento com box-sizing: border-box e adicionar 
    10 pixels de preenchimento e 5 pixels de borda, o tamanho total do elemento ainda será de 300 pixels, com o 
    conteúdo redimensionado para caber dentro da área disponível.

Já se você usar box-sizing: content-box para o mesmo elemento, os 10 pixels de preenchimento e 5 pixels de borda adicionados aumentarão o tamanho total 
do elemento para 320 pixels, o que pode causar problemas de layout em alguns casos.

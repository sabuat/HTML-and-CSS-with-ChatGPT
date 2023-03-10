## Aula 12

> **Cores em CSS**
>
>- Resetar estilo precarregado
>- Cores em CSS: Nomes, Hexadecimal, RGB, RGBA, HSL, HSLA

## Resetar estilo precarregado

Para redefinir o estilo padrão em CSS, você pode usar o seletor universal * e definir suas propriedades para o valor padrão. 
Por exemplo, para redefinir todos os estilos, você pode adicionar o seguinte código ao seu arquivo CSS:

```
* {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font-family: inherit;
  vertical-align: baseline;
}
```

Isso redefine as margens, preenchimentos, bordas, tamanho da fonte e família da fonte para o valor padrão, além de alinhar o texto verticalmente à 
linha de base. Observe que isso também redefinirá todos os estilos personalizados definidos anteriormente. Portanto, use com cuidado.


Existe também um arquivo comummente usado na web para redefinir estilos padrões do navegador, chamado "normalize.css".

O arquivo normalize.css contém um conjunto de regras CSS que normaliza a renderização em diferentes navegadores, garantindo que os elementos HTML
tenham estilos consistentes e coerentes em todos os navegadores modernos. Em outras palavras, ele redefine estilos padrões para fornecer uma base mais 
consistente para o desenvolvimento de sites.

O arquivo normalize.css é bastante conhecido e amplamente utilizado na comunidade de desenvolvimento web. Você pode encontrá-lo e baixá-lo em vários sites e 
repositórios do GitHub. Para usá-lo, basta incluí-lo em seu arquivo HTML ou CSS, antes de incluir qualquer outro arquivo CSS personalizado.

### Cores em CSS

As cores em CSS podem ser especificadas de várias maneiras. Aqui estão algumas maneiras comuns de especificar cores em CSS:

* _Nome da cor:_ Você pode usar o nome de uma cor para especificar a cor que deseja. Por exemplo, red, blue, green, etc.

* _Valor hexadecimal:_ Você também pode especificar a cor usando um valor hexadecimal, que é uma combinação de seis caracteres que representam as intensidades de vermelho, verde e azul (RGB) da cor. Por exemplo, #FF0000 é vermelho e #00FF00 é verde.

* _Valor RGB:_ Você pode especificar uma cor usando os valores de vermelho, verde e azul (RGB) da cor. Por exemplo, rgb(255, 0, 0) é vermelho e rgb(0, 255, 0) é verde.

* _Valor RGBA:_ Semelhante ao valor RGB, o valor RGBA permite especificar uma cor com os valores de vermelho, verde e azul, bem como um valor de opacidade. Por exemplo, rgba(255, 0, 0, 0.5) é vermelho com 50% de opacidade.

* _HSL e HSLA: _HSL significa Hue (matiz), Saturation (saturação) e Lightness (luminosidade) e é outra maneira de especificar cores em CSS. HSLA é semelhante ao valor RGBA, mas usa os valores de Hue, Saturation e Lightness para especificar a cor. Por exemplo, hsl(0, 100%, 50%) é vermelho e hsla(120, 100%, 50%, 0.5) é verde-azulado com 50% de opacidade.

Você também pode usar a palavra-chave transparent para tornar uma cor totalmente transparente. Além disso, você pode usar a propriedade opacity para ajustar a 
opacidade de um elemento, mas isso afetará todos os elementos dentro desse elemento.

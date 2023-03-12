## Aula 13

> **Fontes em CSS**
>
>- Fontes em CSS
>- Atributos para as fontes em CSS

### Fontes em CSS

Em CSS (Cascading Style Sheets), existem várias formas de definir fontes para o seu texto. As fontes são importantes para a legibilidade e aparência do seu site. 
  Aqui estão algumas das formas de definir fontes em CSS:

* Usando fontes da web:

Para usar fontes personalizadas que não estão disponíveis nos computadores dos usuários, você pode baixá-las de um site de fontes da web e adicioná-las ao seu site.
  Para fazer isso, use a regra @font-face em seu CSS:

```
@font-face {
  font-family: 'Nunito';
  src: url('nunito.woff2') format('woff2'),
       url('nunito.woff') format('woff');
}
```

Nesse exemplo, a fonte Nunito é baixada de arquivos WOFF e WOFF2 armazenados na pasta do seu site. Agora você pode usá-la em outros estilos de texto:

```
body {
  font-family: 'Nunito', sans-serif;
}
```

* Usando fontes do sistema:

Você também pode usar as fontes disponíveis no sistema do usuário. Isso pode ser útil para garantir a compatibilidade com as fontes que os usuários já têm 
em seus dispositivos. Para fazer isso, simplesmente especifique as fontes que deseja usar em uma lista, separadas por vírgulas:

```
body {
  font-family: Arial, sans-serif;
}
```
Nesse exemplo, o navegador tentará usar a fonte Arial, se disponível. Se não, ele tentará usar uma fonte sans-serif genérica.

* Usando fontes do Google Fonts:

O Google Fonts é um serviço gratuito que oferece uma ampla variedade de fontes da web para uso em seus sites. Para usá-lo, basta escolher as fontes 
que deseja usar em seu site no site do Google Fonts e, em seguida, adicionar um link para elas em seu HTML. Por exemplo:

```
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
```

Em seguida, você pode usar a fonte em seus estilos de texto:

```
body {
  font-family: 'Open Sans', sans-serif;
}
```

### Atributos para as fontes em CSS

Aqui está uma lista dos principais atributos de fontes em CSS:

  * font-family: Define a família de fontes a ser usada, como "Arial", "Times New Roman", "Helvetica", etc.

  * font-size: Define o tamanho da fonte, como "12px", "1.5rem", "2em", etc.

  * font-weight: Define a espessura da fonte, como "normal", "bold", "bolder", "lighter", "100", "200", "300", "400", "500", "600", "700", "800" ou "900".

  * font-style: Define o estilo da fonte, como "normal", "italic" ou "oblique".

  * line-height: Define a altura da linha de texto, como "1.5", "1.2", "normal", etc.

  * text-decoration: Define a decoração do texto, como "none", "underline", "overline", "line-through", etc.

  * text-transform: Define a transformação do texto, como "none", "uppercase", "lowercase", "capitalize", etc.

  * letter-spacing: Define o espaçamento entre letras, como "normal", "0.2em", "-1px", etc.

  * word-spacing: Define o espaçamento entre palavras, como "normal", "0.5em", "-2px", etc.

  * text-shadow: Define a sombra do texto, como "none", "1px 1px 1px black", "0 0 10px #ccc", etc.

  * font-variant: Define variantes da fonte, como "normal", "small-caps", etc.

Esses são apenas alguns dos atributos disponíveis para personalizar a aparência do texto em CSS. Além disso, há muitos outros atributos para personalizar a 
aparência geral de um elemento HTML, como cor de fundo, bordas, margens, preenchimento, etc.
  
### Unidades usadas em CSS

  Em CSS, existem várias unidades que podem ser usadas para definir tamanhos, distâncias e outras medidas. Aqui estão as principais unidades em CSS:

1. Unidades de comprimento:
  * px: Pixel, uma unidade de medida que se refere ao tamanho de um único ponto na tela.
  * em: Tamanho relativo à fonte do elemento pai.
  * rem: Tamanho relativo à fonte do elemento raiz (ou seja, do html).
  * vh: Viewport height, o tamanho da viewport em altura.
  * vw: Viewport width, o tamanho da viewport em largura.
  * vmin: A menor dimensão da viewport (altura ou largura).
  * vmax: A maior dimensão da viewport (altura ou largura).
  * %: Porcentagem, um valor relativo à medida de um elemento pai.

2. Unidades de tempo:
  * s: Segundos.
  * ms: Milissegundos.

 3. Unidades de ângulo:
  * deg: Graus.
  * rad: Radianos.
  * turn: Uma volta completa (360 graus).

4. Unidades de cor:
  * rgb(): Representação de cor em RGB (Red, Green, Blue).
  * rgba(): Representação de cor em RGBA (Red, Green, Blue, Alpha - transparência).
  * #: Representação de cor em hexadecimal.

5. Unidades de resolução:
  * dpi: Dots per inch, ou pontos por polegada.
  * dpcm: Dots per centimeter, ou pontos por centímetro.
  
Essas são as principais unidades em CSS, mas existem outras unidades específicas para propriedades e situações específicas. É importante escolher a unidade 
correta para cada situação, a fim de garantir que a aparência do seu site seja consistente em diferentes dispositivos e tamanhos de tela.

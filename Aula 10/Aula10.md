## Aula 10

> **Conhecendo o CSS**
>
>- Como o CSS funciona com HTML
>- Inserindo CSS em seu documento HTML

### Como o CSS funciona com HTML

O _CSS (Cascading Style Sheets)_ funciona com o _HTML (Hypertext Markup Language)_ permitindo que os desenvolvedores de web criem estilos visuais para seus 
documentos HTML.

O _HTML_ é a linguagem usada para estruturar o conteúdo e definir a semântica de uma página web. Já o CSS é uma linguagem de estilo que é usada para
controlar a apresentação visual do conteúdo HTML.

O _CSS_ funciona através da seleção de elementos HTML e a aplicação de estilos a eles. Isso é feito via regras CSS definidas em um arquivo separado ou no 
próprio documento HTML.

Por exemplo, se um desenvolvedor deseja alterar a cor do texto em um parágrafo em um documento HTML, ele pode criar uma regra CSS para selecionar o 
elemento ``<p>`` e definir a cor do texto usando a propriedade color.

Exemplo de uma regra CSS que define a cor do texto de um parágrafo:

```
p {
  color: blue;
}
```

O CSS também permite a criação de layouts, controle sobre o posicionamento e dimensionamento dos elementos, animações e outras interações visuais.

Em resumo, o CSS funciona com o HTML permitindo que os desenvolvedores criem estilos visuais para seus documentos HTML, tornando-os mais atraentes e 
fáceis de usar para os usuários finais.

### Inserindo CSS em seu documento HTML

Existem três maneiras principais de inserir CSS em um documento HTML: usando **estilos inline, estilos incorporados ou estilos externos**.


* Estilos Inline
Os estilos inline são definidos diretamente na tag HTML usando o atributo "style". Isso serve para aplicar estilos individuais a elementos específicos.

_Exemplo:_

```
<p style="color: blue;">Este texto é azul.</p>
```


* Estilos Incorporados
Os estilos incorporados são definidos dentro da tag <head> do documento HTML, usando a tag <style>. Isso permite que você defina estilos para vários elementos em uma única seção.

_Exemplo:_

```
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
``` 
 
  
* Estilos Externos
Os estilos externos são definidos em um arquivo CSS separado e vinculados ao documento HTML usando a tag <link> dentro da seção <head> do documento HTML.

_Exemplo:_

```
  <link rel="stylesheet" type="text/css" href="estilos.css">
```

Neste exemplo, o arquivo "estilos.css" contém as definições CSS para todos os elementos HTML no documento. É uma boa prática usar arquivos CSS externos, 
  pois isso ajuda a manter o código organizado e facilita a manutenção a longo prazo.

Independentemente do método escolhido, é importante seguir as melhores práticas para escrever CSS limpo e bem estruturado, o que pode ajudar a melhorar a
  legibilidade do código e tornar a manutenção mais fácil no futuro.

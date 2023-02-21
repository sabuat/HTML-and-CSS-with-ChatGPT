## Aula 4

> **Melhorando o texto e criando listas**
>
>- As tags: . Line Break (br)
>- Adicionando negrito e itálico com as tags Strong (strong) e Emphasis (em)
>- Listas não ordenadas (ul)
>- Listas ordenadas (ol)
>- Listas de definições (dl)

### Tag ``<strong>`` e ``<em>``

As tags ``<strong>`` e ``<em>`` são usadas no HTML para enfatizar o texto dentro de uma página da web. No entanto, elas têm diferentes significados semânticos.

A tag ``<strong>`` é usada para dar ênfase forte ao texto, geralmente mudando seu estilo para torná-lo mais visível e destacado. 
  Por exemplo, você pode usar a tag <strong> para destacar um ponto importante em um parágrafo, ou para tornar um título ou subtítulo mais proeminente na página.
  
Por outro lado, a tag ``<em>`` é usada para dar ênfase enfática ou expressiva ao texto. 
  Ela geralmente é interpretada pelos navegadores como colocando o texto em itálico, embora a aparência final dependa do estilo aplicado na página.

Embora a aparência final das tags <strong> e <em> possa variar dependendo do estilo aplicado na página, 
  é importante lembrar que elas têm significados semânticos distintos e devem ser usadas de acordo com a intenção do autor. 
  A tag <strong> é usada para dar ênfase forte, enquanto a tag <em> é usada para dar ênfase enfática ou expressiva.
  
### Diferença entre ul e ol no HTML?
``<ul>`` e ``<ol>`` são elementos HTML usados para criar listas.

A diferença entre eles é que ``<ul>`` é uma lista não ordenada (unordered list) e ``<ol>`` é uma lista ordenada (ordered list).

Em uma lista não ordenada, os itens são apresentados com marcadores, geralmente pontos. 
Já em uma lista ordenada, os itens são numerados ou apresentados com letras.

Aqui está um exemplo de uma lista não ordenada:

```
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
```

E aqui está um exemplo de uma lista ordenada:


``<ol>``

  ``<li>Item 1</li>``

  ``<li>Item 2</li>``

  ``<li>Item 3</li>``

``</ol>``

Em ambos os exemplos, cada item da lista é definido com o elemento ``<li>`` (item de lista).

### O que é uma dl em html?
``<dl>`` é um elemento HTML que representa uma lista de definição (definition list). 
É utilizado para criar uma lista de termos e suas respectivas definições. A lista de definição é composta por uma série de pares de termos e suas definições.

Cada par de termo e definição é definido com os elementos ``<dt>`` e ``<dd>``, 
respectivamente. O elemento ``<dt>`` é usado para definir o termo (ou item) da lista de definição, enquanto o elemento 
``<dd>`` é usado para definir a descrição ou definição do termo.

Aqui está um exemplo simples de como criar uma lista de definição com a utilização do elemento ``<dl>``:

``<dl>``

  ``<dt>Termo 1</dt>``
  ``<dd>Descrição 1</dd>``
  ``<dt>Termo 2</dt>``
  ``<dd>Descrição 2</dd>``
  ``<dt>Termo 3</dt>``
  ``<dd>Descrição 3</dd>``
``</dl>``

No exemplo acima, criamos uma lista de definição com três pares de termos e suas respectivas definições. 
É importante notar que a lista de definição pode ter quantos pares de termos e definições forem necessários.


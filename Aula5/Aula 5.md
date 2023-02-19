## Aula 5

> **Links**
>
> - A tag Anchor (a)
> - Como criar links internos e externos

### *Como funciona a tag anchor em HTML?*

A tag "anchor" ou "âncora" em HTML é usada para criar um link que leva a outra seção da mesma página ou para outra página da web. 
A tag anchor é representada pelo elemento ``<a>`` em HTML e funciona da seguinte forma:

O atributo "href" é usado para especificar o destino do link. Isso pode ser uma URL completa para outra página da web ou 
um identificador exclusivo para uma seção específica da página atual.

O texto dentro da tag anchor é exibido como o texto do link.

Por exemplo, para criar um link que leva a uma seção específica da mesma página, você pode usar o seguinte código HTML:

>``<a href="#secao1">Ir para a Seção 1</a>``
>...
>``<h2 id="secao1">Seção 1</h2>``

Neste exemplo, o valor do atributo "href" é "#secao1", que é um identificador exclusivo para a seção 1 da página. 
Quando o usuário clica no link, ele será levado diretamente para a seção 1 da mesma página.

Além disso, a tag anchor também pode ser usada para criar links para outras páginas da web, como neste exemplo:

>``<a href="https://www.exemplo.com">Visite Exemplo.com</a>``

Neste caso, o valor do atributo "href" é a URL completa para a página que você deseja vincular. 
Quando o usuário clica no link, ele será levado para a página vinculada.

### *href*
O atributo "href" em HTML é usado para especificar o destino de um link criado com a tag "a" (âncora).
O valor do atributo "href" é geralmente uma URL (Uniform Resource Locator) que identifica o endereço da página da web, imagem, 
vídeo, arquivo de áudio ou qualquer outro recurso que você deseja vincular.

A sintaxe básica da tag "a" com o atributo "href" é a seguinte:

> ``<a href="URL">Texto do link</a>``

Aqui, "URL" é a localização do recurso que você deseja vincular e "Texto do link" é o texto que será exibido como o link no navegador. 
Quando um usuário clica no link, ele é levado para a página ou recurso especificado pela URL.

Além de especificar uma URL absoluta (ou seja, uma URL completa que começa com "http://" ou "https://"), 
o atributo "href" também pode aceitar outros tipos de valores, incluindo:

* URLs relativas: essas são URLs que se referem a um local relativo ao arquivo HTML atual. Por exemplo, se a página atual estiver em "http://www.exemplo.com/pasta1/pagina.html", uma URL relativa de "pasta2/arquivo.html" apontaria para "http://www.exemplo.com/pasta1/pasta2/arquivo.html".

* IDs de âncora: esses são identificadores exclusivos que especificam um local específico na mesma página. Por exemplo, se houver uma seção na mesma página com o ID "secao1", uma URL de "#secao1" apontaria para essa seção específica.

* URLs de e-mail: essas são URLs que abrem o programa de e-mail padrão do usuário com um novo e-mail criado. O valor do atributo "href" é o endereço de e-mail do destinatário.

* JavaScript: o atributo "href" pode ser usado com o código JavaScript para criar links que executam ações em vez de navegar para outra página. Por exemplo, você pode criar um link que exibe uma caixa de diálogo quando clicado.

Em resumo, o atributo "href" em HTML é usado para criar links que permitem aos usuários navegar para outras páginas da web, recursos ou executar ações no navegador usando JavaScript.

### *Como funciona a tag section?*

A tag "section" em HTML é usada para agrupar um conjunto de elementos relacionados em uma seção temática, 
tornando mais fácil para os desenvolvedores e usuários compreenderem e navegar no conteúdo. A tag "section" é um elemento de bloco em HTML e pode conter qualquer tipo de conteúdo, como texto, imagens, listas, formulários, outras seções e assim por diante.

A tag "section" é usada para dividir o conteúdo de uma página em seções separadas com base no contexto e significado do conteúdo, 
o que pode ajudar a tornar a página mais acessível e legível. Por exemplo, em uma página de blog, você pode usar a tag "section" para agrupar as
postagens em seções separadas, como "últimas postagens", "mais populares" e "categorias".

### Criando referencias internas

Para criar referências internas em uma página HTML, você pode usar a tag ``<a>`` em conjunto com o atributo "href" e 
  o caractere especial "#" para indicar o elemento na página para o qual deseja criar a referência.

A seguir estão os passos para criar uma referência interna:

* Adicione um ID único a um elemento HTML na página para o qual deseja criar uma referência interna. Você pode fazer isso usando o atributo "id". Por exemplo:

* Crie um link para essa seção na página usando a tag ``<a>`` com o atributo "href" definido como "#" seguido do ID do elemento. Isso criará um link clicável que leva o usuário diretamente para a seção 1 da página quando clicado.

É importante notar que o ID do elemento e a referência interna devem corresponder exatamente, incluindo letras maiúsculas e minúsculas, para que a referência interna funcione corretamente. Além disso, o elemento com o ID deve estar na mesma página em que a referência interna é criada.

## Aula 6

> **Links**
>
> - Adicionando imagens com a tag Image (img)
> - Adicionando videos com a tag Video

### Como insertar images no HTML

Para inserir imagens em uma página HTML, você pode usar a tag <img> e especificar o caminho ou a URL da imagem no atributo "src". 
Aqui está um exemplo básico de como inserir uma imagem:

``<img src="caminho/da/minha/imagem.jpg" alt="Minha imagem">``

Neste exemplo, a imagem é especificada com a tag ``<img>``. O atributo "src" é usado para especificar o caminho ou a URL da imagem. 
O atributo "alt" é usado para fornecer um texto alternativo que é exibido caso a imagem não possa ser carregada ou para fins de acessibilidade.

Certifique-se de substituir "caminho/da/minha/imagem.jpg" pelo caminho correto da imagem em seu computador ou pela URL da 
imagem em um servidor. Além disso, você pode ajustar outros atributos, como largura, altura e estilo, 
conforme necessário, para personalizar a aparência da imagem em sua página HTML.

Os atributos mais comuns da tag ``<img>`` são:

- **src**: especifica o caminho ou a URL da imagem.
- **alt**: fornece um texto alternativo que é exibido caso a imagem não possa ser carregada ou para fins de acessibilidade.
- **width e height**: especifica a largura e a altura da imagem em pixels.
- **title**: fornece um texto que é exibido quando o cursor do mouse está sobre a imagem.
- **style**: permite definir estilos CSS para a imagem, como margens, bordas e alinhamento.

Além desses atributos, existem outros que permitem que você personalize ainda mais a aparência da imagem, como border, align, hspace e vspace.

É importante lembrar que, para que uma imagem seja exibida corretamente em uma página HTML, o caminho ou a URL da imagem deve ser 
especificado corretamente no atributo "src". Se a imagem não puder ser encontrada no caminho especificado, ela não será exibida.

O atributo "alt" também é muito importante, pois fornece uma descrição da imagem para pessoas com deficiência visual ou 
para situações em que a imagem não pode ser carregada. É recomendado que sempre inclua um texto alternativo para todas as imagens em suas páginas HTML.

### A tag ``<video>`` de HTML

A tag ``<video>`` é usada em HTML para incorporar arquivos de vídeo em uma página web. 
Essa tag é um elemento de conteúdo, o que significa que precisa de uma tag de abertura ``<video>`` e uma de fechamento ``</video>``, 
e permite a inclusão de diferentes fontes e formatos de vídeo para garantir a compatibilidade em diferentes navegadores e dispositivos.

O atributo "controls" é adicionado para que os controles padrão do player de vídeo sejam exibidos (play, pause, volume, etc). As tags ``<source>``
são usadas para especificar diferentes fontes e formatos de vídeo que serão exibidos de acordo com a compatibilidade do navegador. 

Além desses atributos, a tag ``<video>`` possui outros atributos que permitem personalizar o player de vídeo, como width, height, poster, 
autoplay, loop, preload, entre outros.

É importante lembrar que o tamanho do arquivo de vídeo pode ser muito grande, o que pode afetar o desempenho da página. 
Portanto, é recomendável otimizar o tamanho do arquivo de vídeo e, se necessário, usar técnicas de carregamento sob demanda para garantir 
que a página seja carregada rapidamente.

### A tag iframe

A tag ``<iframe>`` é usada em HTML para incorporar uma página web ou outro conteúdo em uma página HTML. 
Essa tag é um elemento de conteúdo, o que significa que precisa de uma tag de abertura ``<iframe>`` e uma de fechamento ``</iframe>``.

Aqui está a sintaxe básica da tag ``<iframe>``:

``<iframe src="url_do_site"></iframe>``

O atributo "src" é usado para especificar a URL do site que deve ser incorporado na página. A tag também possui outros atributos que permitem 
personalizar o tamanho, borda, largura e altura da área de visualização do conteúdo incorporado.

Um uso comum da tag ``<iframe>`` é incorporar conteúdo de sites de terceiros, como mapas, vídeos e redes sociais. 
No entanto, é importante lembrar que a incorporação de conteúdo de sites externos pode afetar o desempenho da página e a segurança do usuário. 
Portanto, é recomendável usar essa tag com cuidado e verificar se o conteúdo incorporado é seguro e confiável.

Além disso, alguns sites podem bloquear a incorporação de seu conteúdo em outras páginas da web por motivos de segurança ou direitos autorais. 
Por isso, é importante verificar as políticas de incorporação de conteúdo do site antes de usá-lo em uma página HTML.

## Aula 11

> **Seletores em CSS**
>
>- Como selecionar elementos HTML com CSS
>- Seletores de classe e ID

### Seletores de classe e ID
Os seletores de classe e ID são dois dos seletores mais comuns em CSS. 
Eles permitem selecionar elementos HTML com base em sua classe ou ID atribuído. Aqui está uma breve descrição de cada um:

_Seletor de classe:_
O seletor de classe é usado para selecionar elementos HTML com base em sua classe atribuída. Para usar o seletor de classe, 
basta adicionar um ponto antes do nome da classe. 

_Seletor de ID:_
O seletor de ID é usado para selecionar um elemento HTML específico com base em seu ID atribuído. Para usar o seletor de ID, 
basta adicionar um hashtag antes do nome do ID. 

É importante lembrar que os IDs devem ser únicos em uma página HTML, enquanto as classes podem ser usadas em vários elementos HTML.
Além disso, é uma boa prática usar as classes para estilizar grupos de elementos semelhantes e os IDs para selecionar elementos específicos que
precisam de estilos personalizados.

### Como selecionar elementos HTML com CSS

Para selecionar elementos HTML com CSS, você pode usar os seletores CSS. Os seletores CSS são usados para selecionar os elementos que você 
deseja estilizar ou manipular. Aqui estão alguns exemplos de seletores CSS comuns:

* _Selecionando elementos por nome de tag:_
```
/* Seleciona todos os elementos <p> */
p {
  color: red;
}
```

* _Selecionando elementos por classe:_
```
/* Seleciona todos os elementos com a classe "destaque" */
.destaque {
  font-weight: bold;
}
```

* _Selecionando elementos por ID:_
```
/* Seleciona o elemento com o ID "titulo" */
#titulo {
  font-size: 24px;
}
```

* _Selecionando elementos por atributo:_
```
/* Seleciona todos os elementos com o atributo "href" */
a[href] {
  color: blue;
}
```

* _Selecionando elementos por pseudoclasse:_
```
/* Seleciona o link quando o mouse passa sobre ele */
a:hover {
  text-decoration: underline;
}
```


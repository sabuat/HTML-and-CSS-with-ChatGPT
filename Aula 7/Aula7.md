## Aula 7

>**Tabelas + Resumão**
>
>- A tag Table (table)
>- As tags Table Row (tr), Table Header Cell (th) e Table Data Cell (td)
>- Verificando o estudado até agora

### Lista das 40 tag mais utilizadas em HTML

|       1       |       2       |       3       |       4       |       5       |
|---------------|:-------------:|:-------------:|:-------------:|:-------------:|
|``<!DOCTYPE>`` |``<div>``      |``<ol>``       |``<input>``    |``<span>``     |
|``<html>``     |``<p>``        |``<table>``    |``<label>``    |``<br>``       |
|``<head>``     |``<img>``      |``<tr>``       |``<select>``   |``<hr>``       |
|``<title>``    |``<a>``        |``<th>``       |``<option>``   |``<script>``   |
|``<meta>``     |``<ul>``       |``<td>``       |``<button>``   |h1 - h6        |
|``<body>``     |``<li>``       |``<form>``     |``<textarea>`` |``<iframe>``   |
|``<nav>``      |``<header>``   |``<footer>``   |``<section>``  |``<em>``       |

### Como criar uma tabela no HTML

Para criar uma tabela em HTML, você pode usar as tags ``<table>``, ``<tr>``, ``<th>`` e ``<td>`` da seguinte maneira:

Comece criando a tag ``<table>`` para iniciar a tabela:

```
<table>
</table>
```

Em seguida, crie as linhas da tabela usando a tag <tr>:

```
<table>
  <tr>
  </tr>
  <tr>
  </tr>
</table>
```
  
Dentro de cada linha, crie as células usando as tags <th> para cabeçalhos e <td> para dados:

```
<table>
  <tr>
    <th>Nome</th>
    <th>Idade</th>
    <th>Profissão</th>
  </tr>
  <tr>
    <td>João</td>
    <td>30</td>
    <td>Engenheiro</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>25</td>
    <td>Advogada</td>
  </tr>
</table>
```

É importante lembrar que as tags ``<th>`` são usadas para criar o cabeçalho da tabela e ``<td>`` para os dados. 
  É possível personalizar a tabela com estilos CSS para deixá-la mais bonita e funcional.


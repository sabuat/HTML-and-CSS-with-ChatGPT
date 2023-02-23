## Aula 7

> **Criando Formularios**
>
>- A tag Table (table)
>- As tags Table Row (tr), Table Header Cell (th) e Table Data Cell (td)
>- Verificando o estudado até agora

Estrutura básica de um formulário em HTML
A estrutura básica de um formulário em HTML consiste em um conjunto de elementos que permitem aos usuários inserir dados e enviá-los para um servidor para processamento.

Aqui está um exemplo de uma estrutura básica de formulário em HTML:

```
<!DOCTYPE html>
  <html>
    <head>
      <title>Exemplo de formulário</title>
    </head>
    <body>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome"><br><br>
        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem"></textarea><br><br>
        <input type="submit" value="Enviar">
      </form>
    </body>
  </html>
```

### Explicação:

``<form>``: Define o formulário que permite a entrada de dados.
``<label>``: Rótulo para o campo de entrada, associado ao atributo for do input.
``<input>``: Campo de entrada que permite ao usuário inserir dados.
type="text": Define que o campo é do tipo texto.
type="email": Define que o campo é do tipo e-mail, com validação.
id e name: Atributos que identificam o campo de entrada.
``<textarea>``: Campo de entrada para inserção de texto longo.
``<input type="submit">``: Botão para enviar o formulário.

### A tag input em HTML

A tag ``<input>`` em HTML é usada para criar um campo de entrada para o usuário inserir informações em um formulário. 

Os atributos mais comuns da tag ``<input>`` são:

* type: Define o tipo de campo de entrada. Alguns dos valores possíveis são text, password, email, number, checkbox, radio, submit, reset, entre outros.

* name: Define o nome do campo de entrada, que é usado para identificar o campo quando o formulário é enviado para o servidor.

* value: Define o valor inicial do campo de entrada. O valor padrão varia de acordo com o tipo do campo de entrada.

* placeholder: Define um texto que aparece dentro do campo de entrada antes do usuário digitar algum texto.

* required: Especifica se o campo é obrigatório e não pode ser deixado em branco.

* readonly: Especifica se o campo é somente leitura e não pode ser editado pelo usuário.

* disabled: Especifica se o campo está desativado e não pode ser usado pelo usuário.

* maxlength: Especifica o número máximo de caracteres que podem ser inseridos no campo.

* min e max: Especificam o valor mínimo e máximo permitido em campos do tipo number.

* pattern: Especifica uma expressão regular que o valor inserido no campo deve corresponder.


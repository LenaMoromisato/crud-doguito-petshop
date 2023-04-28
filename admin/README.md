# Curso JS na web: CRUD com JavaScript assíncrono

> Status do projeto: em andamento

Conteúdo do curso:

* Fazer requisições utilizando **XMLHttpRequest**;
* Lidar com **promises**;
* Fazer uma requisição http utilizando **XMLHttpRequest** para buscar todos os clientes do servidor;
* Refatorar o código utilizando **promises** melhorando a leitura do código;
* Utilizar **template literals** para criar um template html;
* Entender a ordem de execução do código JavaScript;
* Puxar dados do servidor utilizando a função **fetch api** ao invés do **XMLHttpRequest** para modernizar o código;
* Refatorar as responsabilidades do código pensando na manutenção da aplicação no futuro;
* Usar a método **closest** para encontrar o elemento do DOM mais próximo ao que queremos remover;
* Criar um cliente utilizando o verbo http **POST**;
* Remover um elemento do dom com método **remove()**;
* Deletar um cliente utilizando o verbo http **DELETE**;
* Fazer uma query string utilizando a propriedade **searchParams.get()** para encontrar um id;
* Criar uma IIFE ou função auto executável;
* Editar os dados utilizando o verbo http **PUT**.

-----

## Server:

abrir a pasta admin no vscode e 
rodar o json server: 
```js
json-server --watch db.json
```

Rodar: browser-sync start --server --file . --host --port 5000 --startPath admin/telas/lista_cliente.html

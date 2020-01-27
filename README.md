<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  Desafio 1: Conceitos do NodeJS
</h3>

## Descrição

API de gerenciamento de projetos e tarefas


## Tecnologias

* [Node.js](https://nodejs.org/pt-br/)
* [Express.js](https://www.npmjs.com/package/express)


## Rotas

* `POST /projects:` Adiciona um projeto, com os atributos **id** e **title**.

* `GET /projects:` Rota que lista todos projetos e suas tarefas;

* `PUT /projects/:id:` Atualiza os dados de um projeto pelo id.

* `DELETE /projects/:id:` Deleta um projeto pelo id.

* `POST /projects/:id/tasks:` Adiciona uma tarefa. Aceita o atributo **tasks** no formato de array de strings.


## Utilização

Após baixar o projeto pelo git clone, realize os seguintes passos:

```console
cd projects_and_tasks
yarn install
yarn dev
```

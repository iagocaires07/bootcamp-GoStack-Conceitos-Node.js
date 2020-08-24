﻿# 🚀Bootcamp GoStack Conceitos Node.js
 
## Conteúdos aboradados no nível 01:

- Utilizando o Node.js no back-end;
- O que é o Node.js?
  * O Node.js é uma plataforma onde desenvolvemos o backend em JavaScriptl. Podemos construímos também 
  as regras de negócio, rotas e integrações.
- Características do Node.js: 
  * Arquitetura Event-loop;
  * Call Stack;
  * Single-Thrad;
  * Non-Blocking I/O
 
 ## API Rest
- O que é ? 
  * Uma API Rest é uma aplicação que podemos ter vários cliente utilizando-a. Nela, somente nos preucupamos 
  em retornar os dados pedidos em uma requisição, e o cliente que consome a api fica responsável por processar 
  os dados.

## Métodos HTTP: 
- O que são?
  * São as "rotas" por onde o cliente faz a requisição a nossa API. Por ela é enviado dados utilizados para busca,
  criação, filtragem e para deletar um dados.
- Método GET:
  * Utilizamos para buscar um dado/informação.
- Método POST:
  * Utilizamos para criar um dado/informação.
- Método PUT: 
  * Utilizamos para atualizar um dado/informação.
- Método DELET: 
  * Utilizamos para deletar um dado/informação.

## HTTP Codes: 
  * São códigos que retornam status de requisições.
- 1xx: Informational.
- 2xx: Sucess.
  * 200: Sucess;
  * 201: Created.
- 3xx: Redirection.
  * 301: Moved Permanentle;
  * 302: Moved
- 4xx: Client Error.
  * 400: Bad Request;
  * 401: Not Fund.
- 5xx: Server Error.
  * 500: Internal Server Error

## Tipos de parâmetros:
- São formas do cliente enviar informações.
  * Query Params: Usado para filtros e paginação;
  * Route Params: Usado para identificar recursos (Atualizar/ Deletar);
  * Request Body: Usado para enviar o conteúdo que está no body da requisição.

## Middleware: 
  * É um interceptador de requisições que pode interceptar a requisição ou alterar dados da requisição. O utilizamos queando desejamos que 
  um trecho de código seja adisparado automáticamente em uma ou mais rotas.

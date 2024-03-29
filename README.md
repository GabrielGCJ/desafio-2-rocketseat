# Desafio 02: Chapter I - Trabalhando com middlewares
Este é o primeiro chapter no desafio 02 da Rocket Ignite, um programa de capacitação intensiva em desenvolvimento de software.

![image](https://user-images.githubusercontent.com/91347602/232902040-1eb12147-f163-4dd8-bf03-0d2cd96cefb7.png)

### Objetivo:

- O objetivo deste desafio é implementar uma API RESTful com Node.js, TypeScript, Express e com testes usando o Jest para gerenciamento de tarefas (to-do list).

### Deve ser possivel:

- Criação de um usuário com `name` e `username`.
- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;
- Deve ser possível alternar entre plano grátis e PRO.
- No plano grátis deve ser possível que o usuário possa criar até no máximo dez todos e no plano Pro seja possível criar todos ilimitados
- Testar as middlewares
---

### Para rodar o projeto:

Clone este repositório em sua máquina:

`git clone https://github.com/GabrielGCJ/desafio-2-rocketseat.git`

Entre na pasta do projeto:

`cd desafio-2-rocketseat`

Instale o projeto:

`yarn install`

Rode o projeto:

`yarn dev`

Caso queira rodar os testes:

`yarn test`

Acesse o endereço localhost porta 3333 em seu navegador ou ferramenta de testes para interagir com a API:

http://localhost:3333

---

### Para testar as utilidades da API é importante o uso de uma aplicação de API Client como Postman ou Insomnia.

![image](https://user-images.githubusercontent.com/91347602/232907354-81bfa735-8b77-45b0-a624-9964122a11bc.png)

### https://www.postman.com/downloads/

### https://insomnia.rest/download

---
A API implementada durante este chapter possui os seguintes endpoints:

![image](https://user-images.githubusercontent.com/91347602/233255492-f74df8d2-ffc6-4f75-9a93-3d0ce39d1d82.png)

Cada endpont é representado deve enviar um conjunto de parametros para funcionar corretamente.

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Socket.io](https://socket.io/)

Projeto da nextlevelweek 5, rota de nodeJS, onde foi criado um chat para atendimento de clientes em tempo real.

Como executar

- Clone o repositório
- Caso ainda não tenha o arquivo `database.sqlite` dentro da pasta `src/database`, crie esse arquivo e rode `yarn typeorm migration:run` para criar as tabelas do banco de dados.
- Rode o `yarn dev` para iniciar a aplicação.

Por fim, a aplicação estará disponível em `http://localhost:3333`
